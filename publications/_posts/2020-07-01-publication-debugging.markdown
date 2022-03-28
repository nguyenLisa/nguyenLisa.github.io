---
layout: post
title:  "Debugging static analysis"
display_date:   "Jul 2020"
authors: "Lisa Nguyen Quang Do, Stefan Krüger, Patrick Hill, Karim Ali, Eric Bodden"
venue: "TSE"
categories: survey user-study VisuFlow
links: "[[pdf](assets/docs/papers/tse18.pdf)][[proceedings](https://ieeexplore.ieee.org/document/8453858)][[implementation](https://github.com/VisuFlow)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Static analysis is increasingly used by companies and individual code developers to detect and fix bugs and security vulnerabilities. As programs grow more complex, the analyses have to support new code concepts, frameworks and libraries. However, static-analysis code itself is also prone to bugs. While more complex analyses are written and used in production systems every day, the cost of debugging and fixing them also increases tremendously.

To understand the difficulties of debugging static analysis, we surveyed 115 static-analysis writers. From their responses, we determined the core requirements to build a debugger for static analyses, which revolve around two main issues: abstracting from both the analysis code and the code it analyses at the same time, and tracking the analysis internal state throughout both code bases. Most tools used by our survey participants lack the capabilities to address both issues.

Focusing on those requirements, we introduce Visuflow, a debugging environment for static data-flow analysis. Visuflow features graph visualizations and custom breakpoints that enable users to view the state of an analysis at any time. In a user study on 20 static-analysis writers, Visuflow helped identify 25 and fix 50 percent more errors in the analysis code compared to the standard Eclipse debugging environment.

### Artifacts
- [Survey questions](assets/docs/artifacts/visuflow-survey-questions.pdf)
- [Survey results](assets/docs/artifacts/visuflow-survey-answers.xlsx)
  - The first sheet contains the raw answers.
  - Each of the other sheets contains the answers to one question and their corresponding classification information.
- [User study questionnaire](assets/docs/artifacts/visuflow-study-questionnaire.pdf)
- [User study results](assets/docs/artifacts/visuflow-user-study-results.xlsx)
  - The first sheet contains the focus times on the different views of the coding environments.
  - The second sheet contains the number of errors found by the participants.
  - The third sheet contains the raw answers to the user study questionnaire.
  - Each of the other sheets contains the answers to one question of the questionnaire and their corresponding classification information.


```
@ARTICLE{8453858,
  author={Nguyen Quang Do, Lisa and Krüger, Stefan and Hill, Patrick and Ali, Karim and Bodden, Eric},
  journal={IEEE Transactions on Software Engineering}, 
  title={Debugging Static Analysis}, 
  year={2020},
  volume={46},
  number={7},
  pages={697-709},
  doi={10.1109/TSE.2018.2868349}
}
```