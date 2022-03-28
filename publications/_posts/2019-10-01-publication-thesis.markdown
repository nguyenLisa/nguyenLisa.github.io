---
layout: post
title:  "Doctoral thesis – User-centered tool design for data-flow analysis"
display_date:   "Oct 2019"
awards: "Summa cum laude, UPB doctoral dissertation award, Zonta club Paderborn award"
venue: "Paderborn university"
authors: "Lisa Nguyen Quang Do"
categories: thesis
links: "[[pdf](assets/docs/papers/thesis.pdf)][[doi](https://digital.ub.uni-paderborn.de/doi/10.17619/UNIPB/1-820)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
In the past decades, static analysis tools have been known to have specific user-experience issues such as a high number of false positives, a lack of responsiveness, or the poor warning descriptions that they provide. Their increasing use in industry makes those issues more relevant, especially as static analysis tools become more powerful, detect more complex bugs and vulnerabilities, and support an increasing number of languages, third-party libraries and coding concepts. The way in which an analysis interprets the code it analyzes may differ from how the developer views the analyzed code, causing major user-experience issues such as warning misunderstandings or wrong fixes.

To address user-experience issues in static analysis tools, we apply the user-centered design methodology, first aiming to understand the users’ motivations for using the tools, and what they need to easily interact with them. With this knowledge, we then derive design recommendations for building static analysis tools, which differ from the ones identified in past studies that only focus on the user-experience issues themselves. Finally, we prototype and evaluate tools for static analysis following the recommendations, showing the usefulness of the user-centered process.

In this thesis, we focus on two groups of users. First, we study analysis developers—who write the code of a static analysis—to discover how to assist them in writing and debugging static analysis code. Through a survey of professional analysis developers, we show that current development tools do not sufficiently support static analysis development. To help analysis developers handle two codebases (the analysis code and the analyzed code), we identify desirable design requirements for a debugging tool for static analysis, such as displaying internal analysis results, providing graph visualizations, or introducing two sets of breakpoints for the two code- bases. We apply some of those requirements in VisuFlow, a coding environment we designed specifically for static analysis. Through a user study, we were able to show that VisuFlow allows analysis developers to debug static analyses more efficiently than with currently used coding environments.

Second, we focus on software developers—who write the code that is analyzed by an analysis tool—and report on developer motivations and strategies through a study consisting of a survey of professional developers, a study of analysis logs from a large software company, and a small-scale cognitive walkthrough. Through our study, we discover that the usage of static analysis tools in industry is heavily influenced by time constraints: the decisions made by software developers depend on how much time they can allocate to understanding and fixing analysis warnings. We thus derive a set of design recommendations for analysis tools, such as improving the responsiveness of the tools to provide developers with quicker updates, including developer knowledge in the analysis to reduce the rate of false positives, or improving the explainability of analysis results to help developers understand warnings more efficiently. We address some of those recommendations through the Just-in-Time Static Analysis concept with which developers can guide the analysis towards results of interest, postponing other paths for later. This allows our implementation, Cheetah, to be responsive enough to be integrated in an Integrated Development Environment. Focusing at the overlooked use case of analysis configuration, we address other recommendations through the concept of rule markers. The concept is used to expose internal analysis information to the developer and help them better understand how the analysis works and why it reports certain results, so that they can adjust the analysis rules. Through user studies and empirical evaluations, we show that when addressing our design recommendations, the two concepts of Just-in-Time analysis and rule markers allow developers to perform their tasks better than with current tools. 

Through this thesis, we motivate the need for more user-centered approaches for addressing decades-old user-experience issues in static analysis, putting the user at the center of the design process in order to create tools that suit their needs.

```
@phdthesis{thesisnqd,  
  author = {Nguyen Quang Do, Lisa},  
  title = {User-Centered Tool Design for Data-Flow Analysis},  
  school = {Paderborn University},  
  year = {2019},  
  url = {https://digital.ub.uni-paderborn.de/doi/10.17619/UNIPB/1-820},  
  doi = {10.17619/UNIPB/1-820},  
}
```