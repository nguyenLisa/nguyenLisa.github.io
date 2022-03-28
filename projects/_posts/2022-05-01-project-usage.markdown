---
layout: post
title:  "Developer usage of static analysis tools"
display_date:   "2019 - 2022"
categories: industry-survey user-study
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Past research in the usability of static analysis tools has focused on usability issues encountered by software developers, and the causes of those issues in analysis tools. We adopt a user-centered approach, to understand how developers use analysis tools, which decisions they make, what they look for when making those decisions, and the motivations behind their strategies.

Through a survey of 87 developers in industry, we report on the usage context and motivations of developers for using static analysis tools in practice, and explain how they motivate different usage strategies.

In another study, we focus on four static analysis tools and perform a heuristic walkthrough and a user study to identify recurring problems in the UIs of static analysis tools.

Those two studies allow us to derive new tool requirements that closely support software developers, and open novel avenues for further static-analysis research such as collaborative problem-solving for analysis warnings.

In a position paper, we discuss the application of those requirements to SWAN, a security-focused static-analysis tool for the Swift programming language.

<!--- ![project-usage.png](/assets/images/project-usage.png) --->

### Artifacts
- Developer survey:
  - [Survey questions](assets/docs/artifacts/gpa_survey_questions.pdf).
  - [Anonymized survey answers](assets/docs/artifacts/gpa_survey_results.pdf).
- Heuristic walkthrough and user study:
  - [Evaluation guide](https://figshare.com/s/087f103905189f1a7ca0).
  - [List of issues](https://figshare.com/s/71d97832ae3b04e0ff1a).
  - [Security tool interface dimensions](https://figshare.com/s/5255acbe659d3097d8a2).
  - The user study questions and some anonymized answers are in the paper’s appendix.

### Publications
- CACM 2022: [Designing UIs for static analysis tools: evaluating tool design guidelines with SWAN](publication-cacm.html) (Daniil Tiganov, Lisa Nguyen Quang Do, Karim Ali).
- TSE 2022: [Why do software developers use static analysis tools? A user-centered study of developer needs and motivations](publication-why-do-swes.html) (Lisa Nguyen Quang Do, James R. Wright, Karim Ali).
- SOUPS 2020: [Why can’t Johnny fix vulnerabilities: a usability evaluation of static analysis tools for security](publication-johnny.html) (Justin Smith, Lisa Nguyen Quang Do, Emerson Murphy-Hill).
