---
layout: post
title:  "Just-in-time static analysis (TR)"
display_date:   "Aug 2016"
venue:   "Tech report"
authors: "Lisa Nguyen Quang Do, Karim Ali, Benjamin Livshits, Eric Bodden, Justin Smith, Emerson Murphy-Hill"
categories: user-study Cheetah
links: "[[pdf](assets/docs/papers/tr16.pdf)][[link](https://dataverse.scholarsportal.info/dataset.xhtml?persistentId=doi:10.7939/DVN/10859)][[implementation](https://github.com/secure-software-engineering/cheetah)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
We present the concept of Just-In-Time (JIT) static analysis that interleaves code development and bug fixing in an integrated development environment. Unlike traditional static analysis tools, a JIT analysis tool presents warnings to code developers over time, providing the most relevant results quickly, and computing less relevant results incrementally later. We describe general guidelines for designing JIT analyses. We also present a general recipe for turning static data- flow analyses into JIT analyses through a concept of layered analysis execution illustrated through Cheetah, a JIT taint analysis for Android applications. Our empirical evaluation of Cheetah on real-world applications shows that our approach returns warnings quickly enough to avoid disrupting a developer’s workflow, a finding confirmed by developers in our user study.

### Artifacts
- [User study documents](assets/docs/artifacts/JITA_UserStudy.pdf)
  - Survey template, participants’ responses, interview protocol.

```
@techreport{Tr2016Cheetah,
  author = {Lisa Nguyen Quang Do and Karim Ali and Benjamin Livshits and Eric Bodden and Justin Smith and Emerson Murphy-Hill},
  title = {Just-in-Time Static Analysis},
  month = aug,
  year = 2016,
  institution = {University of Alberta Dataverse},
  url = {http://bodden.de/pubs/dal16jit-tr.pdf},
  doi = {http://dx.doi.org/10.7939/DVN/10859},
}
```