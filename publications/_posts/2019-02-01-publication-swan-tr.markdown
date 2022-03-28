---
layout: post
title:  "Codebase-adaptive detection of security-relevant methods (TR)"
display_date:   "Feb 2019"
authors: "Goran Piskachev, Lisa Nguyen Quang Do, Eric Bodden"
venue: "Tech report"
categories: configuration ML SWAN
links: "[[pdf](assets/docs/papers/tr19_swan.pdf)][[link](https://www.hni.uni-paderborn.de/publikationen/publikationen/?tx_hnippview_pi1[publikation]=9859)][[implementation](https://github.com/secure-software-engineering/swan)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
More and more companies use static analysis to perform regular code reviews to detect security vulnerabilities in their code, configuring them to detect various types of bugs and vulnerabilities such as the SANS top 25 or the OWASP top 10. For such analyses to be as precise as possible, they must be adapted to the code base they scan. The particular challenge we address in this paper is to provide analyses with the correct security-relevant methods (Srm): sources, sinks, etc. 

We present SWAN, a fully-automated machine-learning approach to detect sources, sinks, validators, and authentication methods for Java programs. SWAN further classifies the Srm into specific vulnerability classes of the SANS top 25. To further adapt the lists detected by SWAN to the code base and to improve its precision, we also introduce SWANAssist, an extension to SWAN that allows analysis users to refine the classifications. On twelve popular Java frameworks, SWAN achieves an average precision of 0.826, which is better or comparable to existing approaches. 

Our experiments show that SWANAssist requires a relatively low effort from the developer to significantly improve its precision.

```
@techreport{hniid=9859,
  author = {Piskachev, Goran and Nguyen, Lisa and Bodden, Eric},
  title = {Codebase-Adaptive Detection of Security-Relevant Methods},
  number = {tr-ri-19-356},
  institution = {Heinz Nixdorf Institut},
  month = feb,
  year = {2019},
}
```