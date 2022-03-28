---
layout: post
title:  "Just-in-time static analysis"
display_date:   "Jul 2017"
venue:   "ISSTA"
authors: "Lisa Nguyen Quang Do, Karim Ali, Benjamin Livshits, Eric Bodden, Justin Smith, Emerson Murphy-Hill"
categories: user-study Cheetah
awards: "Distinguished paper award, Artifact evaluated"
links: "[[pdf](assets/docs/papers/issta17.pdf)][[proceedings](https://dl.acm.org/doi/10.1145/3092703.3092705)][[implementation](https://github.com/secure-software-engineering/cheetah)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
We present the concept of Just-In-Time (JIT) static analysis that interleaves code development and bug fixing in an integrated development environment. Unlike traditional batch-style analysis tools, a JIT analysis tool presents warnings to code developers over time, providing the most relevant results quickly, and computing less relevant results incrementally later.

In this paper, we describe general guidelines for designing JIT analyses. We also present a general recipe for transforming static data-flow analyses to JIT analyses through a concept of layered analysis execution. We illustrate this transformation through CHEETAH, a JIT taint analysis for Android applications.

Our empirical evaluation of CHEETAH on real-world applications shows that our approach returns warnings quickly enough to avoid disrupting the normal workflow of developers. This result is confirmed by our user study, in which developers fixed data leaks twice as fast when using CHEETAH compared to an equivalent batch-style analysis. 

### Artifacts
- [User study documents](assets/docs/artifacts/JITA_UserStudy.pdf)
  - Survey template, participants’ responses, interview protocol.


```
@inproceedings{10.1145/3092703.3092705,
  author = {Nguyen Quang Do, Lisa and Ali, Karim and Livshits, Benjamin and Bodden, Eric and Smith, Justin and Murphy-Hill, Emerson},
  title = {Just-in-Time Static Analysis},
  year = {2017},
  isbn = {9781450350761},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3092703.3092705},
  doi = {10.1145/3092703.3092705},
  abstract = { We present the concept of Just-In-Time (JIT) static analysis that interleaves code development and bug fixing in an integrated development environment. Unlike traditional batch-style analysis tools, a JIT analysis tool presents warnings to code developers over time, providing the most relevant results quickly, and computing less relevant results incrementally later. In this paper, we describe general guidelines for designing JIT analyses. We also present a general recipe for transforming static data-flow analyses to JIT analyses through a concept of layered analysis execution. We illustrate this transformation through CHEETAH, a JIT taint analysis for Android applications. Our empirical evaluation of CHEETAH on real-world applications shows that our approach returns warnings quickly enough to avoid disrupting the normal workflow of developers. This result is confirmed by our user study, in which developers fixed data leaks twice as fast when using CHEETAH compared to an equivalent batch-style analysis. },
booktitle = {Proceedings of the 26th ACM SIGSOFT International Symposium on Software Testing and Analysis},
  pages = {307–317},
  numpages = {11},
  keywords = {Just-in-Time, Static analysis, Layered analysis},
  location = {Santa Barbara, CA, USA},
  series = {ISSTA 2017}
}
```