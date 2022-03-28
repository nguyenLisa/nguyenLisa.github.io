---
layout: post
title:  "Explaining static analysis with rule graphs"
display_date:   "Feb 2022"
authors: "Lisa Nguyen Quang Do, Eric Bodden"
venue: "TSE"
categories: explainability MUDARRI
links: "[[pdf](assets/docs/papers/tse20-1.pdf)][[proceedings](https://ieeexplore.ieee.org/document/9106860)][[implementation](https://github.com/secure-software-engineering/mudarri)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
As static data-flow analysis becomes able to report increasingly complex bugs, using an evergrowing set of complex internal rules encoded into flow functions, the analysis tools themselves grow more and more complex. In result, for users to be able to effectively use those tools on specific codebases, they require special configurations—a task which in industry is typically performed by individual developers or dedicated teams. To efficiently use and configure static analysis tools, developers need to build a certain understanding of the analysis’ rules, i.e., how the underlying analyses interpret the analyzed code and their reasoning for reporting certain warnings.

In this article, we explore how to assist developers in understanding the analysis’ warnings, and finding weaknesses in the analysis’ rules. To this end, we introduce the concept of rule graphs that expose to the developer selected information about the internal rules of data-flow analyses. We have implemented rule graphs on top of a taint analysis, and show how the graphs can support the abovementioned tasks. Our user study and empirical evaluation show that using rule graphs helps developers understand analysis warnings more accurately than using simple warning traces, and that rule graphs can help developers identify causes for false positives in analysis rules.

### Artifacts
- [User study results](assets/docs/artifacts/mudarri_study_results.xslx_.numbers).


```
@ARTICLE{9106860,
  author={Nguyen Quang Do, Lisa and Bodden, Eric},
  journal={IEEE Transactions on Software Engineering}, 
  title={Explaining Static Analysis With Rule Graphs}, 
  year={2022},
  volume={48},
  number={2},
  pages={678-690},
  doi={10.1109/TSE.2020.2999534}
}
```