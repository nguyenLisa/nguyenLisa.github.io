---
layout: post
title:  "VisuFlow"
display_date:   "2016 - 2018"
categories: survey user-study VisuFlow
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
VisuFlow is a debugging environment designed to support static analysis writers understand and debug an analysis. It is written as an Eclipse plugin, and supports static data-flow analyses written on top of the Soot analysis framework.

In more recent research, we have looked into how to make incremental static analysis for changes on the analysis code rather than the analysed code. Stay tuned for more!

![project-debugging.png](/assets/images/project-debugging.png)

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

### Publications
- TSE 2020: [Debugging static analysis](publication-debugging.html) (Lisa Nguyen Quang Do, Stefan Krüger, Patrick Hill, Karim Ali, Eric Bodden).
- ICSE 2018 demo: [VisuFlow: a debugging environment for static analyses](publication-debugging-demo.html) (Lisa Nguyen Quang Do, Stefan Krüger, Patrick Hill, Karim Ali, Eric Bodden).
