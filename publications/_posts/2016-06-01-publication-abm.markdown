---
layout: post
title:  "Toward an automated benchmark management system"
display_date:   "Jun 2016"
venue:   "SOAP"
authors: "Lisa Nguyen Quang Do, Michael Eichberg, Eric Bodden"
categories: benchmark
links: "[[pdf](assets/docs/papers/soap16.pdf)][[proceedings](https://dl.acm.org/doi/10.1145/2931021.2931023)][[implementation](https://github.com/ABenchM/abm)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
The systematic evaluation of program analyses as well as software-engineering tools requires benchmark suites that are representative of real-world projects in the domains for which the tools or analyses are designed. Such benchmarks currently only exist for a few research areas and even where they exist, they are often not effectively maintained, due to the required manual effort. This makes evaluating new analyses and tools on software that relies on current technologies often impossible. 

We describe ABM, a methodology to semi-automatically mine software repositories to extract up-to-date and representative sets of applications belonging to specific domains. The proposed methodology facilitates the creation of such collections and makes it easier to release updated versions of a benchmark suite. Resulting from an instantiation of the methodology, we present a collection of current real-world Java business web applications. The collection and methodology serve as a starting point for creating current, targeted benchmark suites, and thus helps to better evaluate current program-analysis and software-engineering tools. 


```
@inproceedings{10.1145/2931021.2931023,
  author = {Nguyen Quang Do, Lisa and Eichberg, Michael and Bodden, Eric},
  title = {Toward an Automated Benchmark Management System},
  year = {2016},
  isbn = {9781450343855},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/2931021.2931023},
  doi = {10.1145/2931021.2931023},
abstract = { The systematic evaluation of program analyses as well as software-engineering tools requires benchmark suites that are representative of real-world projects in the domains for which the tools or analyses are designed. Such benchmarks currently only exist for a few research areas and even where they exist, they are often not effectively maintained, due to the required manual effort. This makes evaluating new analyses and tools on software that relies on current technologies often impossible. We describe ABM, a methodology to semi-automatically mine software repositories to extract up-to-date and representative sets of applications belonging to specific domains. The proposed methodology facilitates the creation of such collections and makes it easier to release updated versions of a benchmark suite. Resulting from an instantiation of the methodology, we present a collection of current real-world Java business web applications. The collection and methodology serve as a starting point for creating current, targeted benchmark suites, and thus helps to better evaluate current program-analysis and software-engineering tools. },
booktitle = {Proceedings of the 5th ACM SIGPLAN International Workshop on State Of the Art in Program Analysis},
  pages = {13–17},
  numpages = {5},
  keywords = {ABM methodology, benchmark suite, collection, automated},
  location = {Santa Barbara, CA, USA},
  series = {SOAP 2016}
}
```