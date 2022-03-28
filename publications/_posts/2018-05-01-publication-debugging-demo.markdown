---
layout: post
title:  "VisuFlow: a debugging environment for static analyses"
display_date:   "May 2018"
authors: "Lisa Nguyen Quang Do, Stefan Krüger, Patrick Hill, Karim Ali, Eric Bodden"
venue: "ICSE Demo"
categories: user-study
links: "[[pdf](assets/docs/papers/icse18demo.pdf)][[proceedings](https://dl.acm.org/doi/10.1145/3183440.3183470)][[implementation](https://github.com/VisuFlow)][[video](https://www.youtube.com/watch?v=51iimUDaOPQ)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Code developers in industry frequently use static analysis tools to detect and fix software defects in their code. But what about defects in the static analyses themselves? While debugging application code is a difficult, time-consuming task, debugging a static analysis is even harder. We have surveyed 115 static analysis writers to determine what makes static analysis difficult to debug, and to identify which debugging features would be desirable for static analysis.

Based on this information, we have created Visuflow, a debugging environment for static data-flow analysis. Visuflow is built as an Eclipse plugin, and supports analyses written on top of the program analysis framework Soot. The different components in Visuflow provide analysis writers with visualizations of the internal computations of the analysis, and actionable debugging features to support debugging static analyses.


```
@inproceedings{10.1145/3183440.3183470,
  author = {Nguyen Quang Do, Lisa and Kr\"{u}ger, Stefan and Hill, Patrick and Ali, Karim and Bodden, Eric},
  title = {VISUFLOW: A Debugging Environment for Static Analyses},
  year = {2018},
  isbn = {9781450356633},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3183440.3183470},
  doi = {10.1145/3183440.3183470},
  abstract = {Code developers in industry frequently use static analysis tools to detect and fix software defects in their code. But what about defects in the static analyses themselves? While debugging application code is a difficult, time-consuming task, debugging a static analysis is even harder. We have surveyed 115 static analysis writers to determine what makes static analysis difficult to debug, and to identify which debugging features would be desirable for static analysis. Based on this information, we have created Visijflow, a debugging environment for static data-flow analysis. Visuflow is built as an Eclipse plugin, and supports analyses written on top of the program analysis framework Soot. The different components in Visuflow provide analysis writers with visualizations of the internal computations of the analysis, and actionable debugging features to support debugging static analyses. A video demo of Visuflow is available online: https://www.youtube.com/watch?v=BkEfBDwiuH4},
  booktitle = {Proceedings of the 40th International Conference on Software Engineering: Companion Proceeedings},
  pages = {89–92},
  numpages = {4},
  keywords = {IDE, survey, empirical software engineering, user study, static analysis, debugging},
  location = {Gothenburg, Sweden},
  series = {ICSE '18}
}
```