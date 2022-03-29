---
layout: post
title:  "Why can't Johnny fix vulnerabilities: a usability evaluation of static analysis tools for security"
display_date:   "Aug 2020"
authors: "Justin Smith, Lisa Nguyen Quang Do, Emerson Murphy-Hill"
venue: "SOUPS"
categories: heuristic-walkthrough
links: "[[pdf](assets/docs/papers/soups20.pdf)][[proceedings](https://dl.acm.org/doi/10.5555/3488905.3488918)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Static analysis tools can help prevent security incidents, but to do so, they must enable developers to resolve the defects they detect. Unfortunately, developers often struggle to interact with the interfaces of these tools, leading to tool abandonment, and consequently the proliferation of preventable vulnerabilities. Simply put, the usability of static analysis tools is crucial.

The usable security community has successfully identified and remedied usability issues in end user security applications, like PGP and Tor browsers, by conducting usability evaluations. Inspired by the success of these studies, we conducted a heuristic walkthrough evaluation and user study focused on four security-oriented static analysis tools. Through the lens of these evaluations, we identify several issues that detract from the usability of static analysis tools. The issues we identified range from workflows that do not support developers to interface features that do not scale. We make these findings actionable by outlining how our results can be used to improve the state-of-the-art in static analysis tool interfaces.

### Artifacts
- [Evaluation guide](https://figshare.com/s/087f103905189f1a7ca0).
- [List of issues](https://figshare.com/s/71d97832ae3b04e0ff1a).
- [Security tool interface dimensions](https://figshare.com/s/5255acbe659d3097d8a2).
- The user study questions and some anonymized answers are in the paper’s appendix.

```
@inbook{10.5555/3488905.3488918,
  author = {Smith, Justin and Do, Lisa Nguyen Quang and Murphy-Hill, Emerson},
  title = {Why Can't Johnny Fix Vulnerabilities: A Usability Evaluation of Static Analysis Tools for Security},
  year = {2020},
  isbn = {978-1-939133-16-8},
  publisher = {USENIX Association},
  address = {USA},
  abstract = {Static analysis tools can help prevent security incidents, but to do so, they must enable developers to resolve the defects they detect. Unfortunately, developers often struggle to interact with the interfaces of these tools, leading to tool abandonment, and consequently the proliferation of preventable vulnerabilities. Simply put, the usability of static analysis tools is crucial. The usable security community has successfully identified and remedied usability issues in end user security applications, like PGP and Tor browsers, by conducting usability evaluations. Inspired by the success of these studies, we conducted a heuristic walkthrough evaluation and user study focused on four security-oriented static analysis tools. Through the lens of these evaluations, we identify several issues that detract from the usability of static analysis tools. The issues we identified range from workflows that do not support developers to interface features that do not scale. We make these findings actionable by outlining how our results can be used to improve the state-of-the-art in static analysis tool interfaces.},
  booktitle = {Proceedings of the Sixteenth USENIX Conference on Usable Privacy and Security},
  articleno = {13},
  numpages = {18}
}
```