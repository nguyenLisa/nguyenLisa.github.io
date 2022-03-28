---
layout: post
title:  "Debugging static analysis (TR)"
display_date:   "Jan 2018"
authors: "Lisa Nguyen Quang Do, Stefan Krüger, Patrick Hill, Karim Ali, Eric Bodden"
venue: "Tech report"
categories: survey user-study VisuFlow
links: "[[link](https://arxiv.org/abs/1801.04894)][[implementation](https://github.com/VisuFlow)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
To detect and fix bugs and security vulnerabilities, software companies use static analysis as part of the development process. However, static analysis code itself is also prone to bugs. To ensure a consistent level of precision, as analyzed programs grow more complex, a static analysis has to handle more code constructs, frameworks, and libraries that the programs use. While more complex analyses are written and used in production systems every day, the cost of debugging and fixing them also increases tremendously.

To better understand the difficulties of debugging static analyses, we surveyed 115 static analysis writers. From their responses, we extracted the core requirements to build a debugger for static analysis, which revolve around two main issues: (1) abstracting from two code bases at the same time (the analysis code and the analyzed code) and (2) tracking the analysis internal state throughout both code bases. Most current debugging tools that our survey participants use lack the capabilities to address both issues.

Focusing on those requirements, we introduce VisuFlow, a debugging environment for static data-flow analysis that is integrated in the Eclipse development environment. VisuFlow features graph visualizations that enable users to view the state of a data-flow analysis and its intermediate results at any time. Special breakpoints in VisuFlow help users step through the analysis code and the analyzed simultaneously. To evaluate the usefulness of VisuFlow, we have conducted a user study on 20 static analysis writers. Using VisuFlow helped our sample of analysis writers identify 25% and fix 50% more errors in the analysis code compared to using the standard Eclipse debugging environment. 

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
@misc{https://doi.org/10.48550/arxiv.1801.04894,
  doi = {10.48550/ARXIV.1801.04894},
  url = {https://arxiv.org/abs/1801.04894},
  author = {Nguyen Quang Do, Lisa and Krüger, Stefan and Hill, Patrick and Ali, Karim and Bodden, Eric},
  keywords = {Software Engineering (cs.SE), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Debugging Static Analysis},
  publisher = {arXiv},
  year = {2018},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```