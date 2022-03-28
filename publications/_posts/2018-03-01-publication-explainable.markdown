---
layout: post
title:  "Explainable Static Analysis"
display_date:   "Mar 2018"
venue:   "SE explainable software"
authors: "Eric Bodden, Lisa Nguyen Quang Do"
categories: position explainability
links: "[[pdf](assets/docs/papers/explainable_software18.pdf)][[proceedings](https://dl.gi.de/handle/20.500.12116/21160)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Static code analysis is an important tool that aids in the early detection of programming errors, e.g. functional flaws, performance bottlenecks or security vulnerabilities. Past research in static analysis has mainly focused on the precise and efficient detection of programming mistakes, allowing new analyses to return more accurate results in a shorter time. However, end-user experience or static analysis tools in industry shows high abandonment rates. Previous work has discovered that current analysis tools are ill-adapted to meet the needs of their users, taking a long time to yield results and causing warnings to be frequently misinterpreted. This can quickly make the overall benefit of static analyses deteriorate.

In this work, we argue for the need of developing a line of research on aiding users of static analysis tools, e.g., code developers, to better understand the findings reported by those tools. We outline how we plan to address this problem space by a novel line of research that ultimately seeks to change static analysis tools from being tools for static analysis experts to tools that can be mastered by general code developers. To achieve this goal, we plan to develop novel techniques for formulating, inspecting and debugging static analyses and the rule sets they validate programs against.

```
@inproceedings{mci/Bodden2018,
  author = {Bodden, Eric AND Nguyen Quang Do, Lisa},
  title = {Explainable Static Analysis},
  booktitle = {Software Engineering und Software Management 2018},
  year = {2018},
  editor = {Tichy, Matthias AND Bodden, Eric AND Kuhrmann, Marco AND Wagner, Stefan AND Steghöfer, Jan-Philipp} ,
  pages = { 205-208 },
  publisher = {Gesellschaft für Informatik},
  address = {Bonn}
} 
```