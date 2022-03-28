---
layout: post
title:  "Cheetah: just-in-time taint analysis for Android apps"
display_date:   "May 2017"
venue:   "ICSE demo"
authors: "Lisa Nguyen Quang Do, Karim Ali, Benjamin Livshits, Eric Bodden, Justin Smith, Emerson Murphy-Hill"
categories: user-study
links: "[[pdf](assets/docs/papers/icse17demo.pdf)][[proceedings](https://dl.acm.org/doi/10.1109/ICSE-C.2017.20)][[implementation](https://github.com/secure-software-engineering/cheetah)][[video](https://www.youtube.com/watch?v=i_KQD-GTBdA)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Current static-analysis tools are often long-running, which causes them to be sidelined into nightly build checks. As a result, developers rarely use such tools to detect bugs when writing code, because they disrupt their workflow.

In this paper, we present Cheetah, a static taint analysis tool for Android apps that interleaves bug fixing and code development in the Eclipse integrated development environment. Cheetah is based on the novel concept of Just-in-Time static analysis that discovers and reports the most relevant results to the developer fast, and computes the more complex results incrementally later. Unlike traditional batch-style static-analysis tools, Cheetah causes minimal disruption to the developer's workflow.


```
@inproceedings{10.1109/ICSE-C.2017.20,
  author = {Nguyen Quang Do, Lisa and Ali, Karim and Livshits, Benjamin and Bodden, Eric and Smith, Justin and Murphy-Hill, Emerson},
  title = {Cheetah: Just-in-Time Taint Analysis for Android Apps},
  year = {2017},
  isbn = {9781538615898},
  publisher = {IEEE Press},
  url = {https://doi.org/10.1109/ICSE-C.2017.20},
  doi = {10.1109/ICSE-C.2017.20},
  abstract = {Current static-analysis tools are often long-running, which causes them to be sidelined into nightly build checks. As a result, developers rarely use such tools to detect bugs when writing code, because they disrupt their workflow. In this paper, we present Cheetah, a static taint analysis tool for Android apps that interleaves bug fixing and code development in the Eclipse integrated development environment. Cheetah is based on the novel concept of Just-in-Time static analysis that discovers and reports the most relevant results to the developer fast, and computes the more complex results incrementally later. Unlike traditional batch-style static-analysis tools, Cheetah causes minimal disruption to the developer's workflow. This video demo showcases the main features of Cheetah: https://www.youtube.com/watch?v=i_KQD-GTBdA.},
  booktitle = {Proceedings of the 39th International Conference on Software Engineering Companion},
  pages = {39–42},
  numpages = {4},
  location = {Buenos Aires, Argentina},
  series = {ICSE-C '17}
}
```