---
layout: post
title:  "Boomerang"
display_date:   "2014 - 2026"
categories: pointer-analysis on-demand
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Boomerang is a demand-driven flow and context-sensitive pointer analysis for Java written in the IFDS framework.

Pointer analysis is a building block of static analysis. Be it for building call graphs, or to guarantee the soundness of other analyses, points-to and alias information are important to provide. The format of points-to and alias analyses do not return all-alias information, meaning that in order to find all variables that alias to another, the user should iterate over all existing variables in the program, and query the analysis for each of them. Boomerang is the first analysis that provides all-alias sets. It is also an on-demand analysis, which allows it to return results quickly.

![project-boomerang.png](/assets/images/project-boomerang.png)

### Publications
- ECOOP 2016: [Boomerang: Demand-Driven Flow- and Context-Sensitive Pointer Analysis for Java](publication-boomerang.html) (Johannes Späth, Lisa Nguyen Quang Do, Eric Bodden).