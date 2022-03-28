---
layout: post
title:  "Boomerang: Demand-Driven Flow- and Context-Sensitive Pointer Analysis for Java"
display_date:   "Jul 2016"
venue:   "ECOOP"
authors: "Johannes Späth, Lisa Nguyen Quang Do, Eric Bodden"
categories: pointer-analysis on-demand
awards: "Artifact evaluated"
links: "[[pdf](assets/docs/papers/ecoop16.pdf)][[proceedings](https://drops.dagstuhl.de/opus/volltexte/2016/6116/)][[implementation](https://github.com/johspaeth/boomerang-artifact)][[video](https://www.youtube.com/watch?v=aTt4M2_TGPI)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Many current program analyses require highly precise pointer information about small, targeted parts of a given program. This motivates the need for demand-driven pointer analyses that compute information only where required. Pointer analyses generally compute points-to sets of program variables or answer boolean alias queries. However, many client analyses require richer pointer information. For example, taint and typestate analyses often need to know the set of all aliases of a given variable under a certain calling context. With most current pointer analyses, clients must compute such information through repeated points-to or alias queries, increasing complexity and computation time for them.

This paper presents Boomerang, a demand-driven, flow-, field-, and context-sensitive pointer analysis for Java programs. Boomerang computes rich results that include both the possible allocation sites of a given pointer (points-to information) and all pointers that can point to those allocation sites (alias information). For increased precision and scalability, clients can query Boomerang with respect to particular calling contexts of interest.

Our experiments show that Boomerang is more precise than existing demand-driven pointer analyses. Additionally, using Boomerang, the taint analysis FlowDroid issues up to 29.4x fewer pointer queries compared to using other pointer analyses that return simpler pointer information. Furthermore, the search space of Boomerang can be significantly reduced by requesting calling contexts from the client analysis. 


```
@InProceedings{spth_et_al:LIPIcs:2016:6116,
  author =	{Johannes Sp{\"a}th and Lisa Nguyen Quang Do and Karim Ali and Eric Bodden},
  title =	{Boomerang: Demand-Driven Flow- and Context-Sensitive Pointer Analysis for Java},
  booktitle =	{30th European Conference on Object-Oriented Programming (ECOOP 2016)},
  pages =	{22:1--22:26},
  series =	{Leibniz International Proceedings in Informatics (LIPIcs)},
  ISBN =	{978-3-95977-014-9},
  ISSN =	{1868-8969},
  year =	{2016},
  volume =	{56},
  editor =	{Shriram Krishnamurthi and Benjamin S. Lerner},
  publisher =	{Schloss Dagstuhl--Leibniz-Zentrum fuer Informatik},
  address =	{Dagstuhl, Germany},
  URL =		{http://drops.dagstuhl.de/opus/volltexte/2016/6116},
  URN =		{urn:nbn:de:0030-drops-61164},
  doi =		{10.4230/LIPIcs.ECOOP.2016.22},
  annote =	{Keywords: Demand-Driven; Static Analysis; IFDS; Aliasing; Points-to Analysis}
}
```