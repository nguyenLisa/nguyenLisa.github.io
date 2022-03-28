---
layout: post
title:  "SwanAssist: semi-automated detection of code-specific, security-relevant methods"
display_date:   "Nov 2019"
authors: "Goran Piskachev, Lisa Nguyen Quang Do, Oshando Johnson, Eric Bodden"
venue: "ASE Demo"
categories: configuration
links: "[[pdf](assets/docs/papers/ase19tool.pdf)][[proceedings](https://dl.acm.org/doi/10.1109/ASE.2019.00110)][[implementation](https://github.com/secure-software-engineering/swan)][[video](https://www.youtube.com/watch?v=fSyD3V6EQOY)]"
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
To detect specific types of bugs and vulnerabilities, static analysis tools must be correctly configured with security-relevant methods (Srm), e.g., sources, sinks, sanitizers and authentication methods---usually a very labour-intensive and error-prone process. This work presents the semi-automated tool SWANAssist, which aids the configuration with an IntelliJ plugin based on active machine learning. It integrates our novel automated machine-learning approach SWAN, which identifies and classifies Java Srm. SWANAssist further integrates user feedback through iterative learning. SWANAssist aids developers by asking them to classify at each point in time exactly those methods whose classification best impact the classification result. Our experiments show that SWANAssist classifies Srm with a high precision, and requires a relatively low effort from the user.

```
@inproceedings{10.1109/ASE.2019.00110,
  author = {Piskachev, Goran and Do, Lisa Nguyen Quang and Johnson, Oshando and Bodden, Eric},
  title = {SWANAssist: Semi-Automated Detection of Code-Specific, Security-Relevant Methods},
  year = {2019},
  isbn = {9781728125084},
  publisher = {IEEE Press},
  url = {https://doi.org/10.1109/ASE.2019.00110},
  doi = {10.1109/ASE.2019.00110},
  abstract = {To detect specific types of bugs and vulnerabilities, static analysis tools must be correctly configured with security-relevant methods (Srm), e.g., sources, sinks, sanitizers and authentication methods---usually a very labour-intensive and error-prone process. This work presents the semi-automated tool SWANAssist, which aids the configuration with an IntelliJ plugin based on active machine learning. It integrates our novel automated machine-learning approach SWAN, which identifies and classifies Java Srm. SWANAssist further integrates user feedback through iterative learning. SWANAssist aids developers by asking them to classify at each point in time exactly those methods whose classification best impact the classification result. Our experiments show that SWANAssist classifies Srm with a high precision, and requires a relatively low effort from the user. A video demo of SWANAssist can be found at https://youtu.be/fSyD3V6EQOY. The source code is available at https://github.com/secure-software-engineering/swan.},
booktitle = {Proceedings of the 34th IEEE/ACM International Conference on Automated Software Engineering},
  pages = {1094–1097},
  numpages = {4},
  keywords = {machine-learning, program analysis},
  location = {San Diego, California},
  series = {ASE '19}
}

```