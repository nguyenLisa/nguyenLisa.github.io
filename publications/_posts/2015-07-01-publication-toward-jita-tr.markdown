---
layout: post
title:  "Toward a Just-in-Time Static Analysis"
display_date:   "Jul 2015"
venue:   "Tech report"
authors: "Lisa Nguyen Quang Do, Karim Ali, Benjamin Livshits, Eric Bodden"
categories: Cheetah
links: "[[pdf](assets/docs/papers/tr15.pdf)][[link](https://www.microsoft.com/en-us/research/publication/toward-just-time-static-analysis/)][[implementation](https://github.com/secure-software-engineering/cheetah)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
We present the concept of Just-In-Time (JIT) static analysis that interleaves code development and bug fixing in an integrated development environment. Unlike traditional static analysis tools, a JIT analysis tool presents warnings to code developers over time, providing the most relevant results quickly, and computing less relevant results incrementally later. This paper outlines general guidelines for designing JIT analyses. We also present a general recipe for turning static data-flow analyses into JIT analyses through a concept of layered analysis execution illustrated through Cheetah, a JIT taint analysis for Android applications. Our evaluation of Cheetah on real-world applications and our user study show that JIT analyses are able to present those warnings that are of importance to the code developers just-in-time, allowing them to start fixing problems immediately, without losing their context. Furthermore, study participants consistently reported higher satisfaction levels with Cheetah compared to its traditional counterpart.

```
@misc{do2015toward,
  author = {Nguyen Quang Do, Lisa and Ali, Karim and Bodden, Eric and Livshits, Ben},
  title = {Toward a Just-in-Time Static Analysis},
  year = {2015},
  month = {July},
  abstract = {We present the concept of Just-In-Time (JIT) static analysis that interleaves code development and bug fixing in an integrated development environment. Unlike traditional static analysis tools, a JIT analysis tool presents warnings to code developers over time, providing the most relevant results quickly, and computing less relevant results incrementally later. This paper outlines general guidelines for designing JIT analyses. We also present a general recipe for turning static data-flow analyses into JIT analyses through a concept of layered analysis execution illustrated through Cheetah, a JIT taint analysis for Android applications. Our evaluation of Cheetah on real-world applications and our user study show that JIT analyses are able to present those warnings that are of importance to the code developers just-in-time, allowing them to start fixing problems immediately, without losing their context. Furthermore, study participants consistently reported higher satisfaction levels with Cheetah compared to its traditional counterpart.},
  url = {https://www.microsoft.com/en-us/research/publication/toward-just-time-static-analysis/},
  edition = {Technical University of Darmstadt Technical Report TUD-CS-2015-1167},
  note = {Technical University of Darmstadt Technical Report TUD-CS-2015-1167},
}
```