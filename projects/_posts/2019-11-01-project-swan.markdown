---
layout: post
title:  "Swan and SwanAssist"
display_date:   "2018 - 2019"
categories: configuration ML
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
Swan is a semi-automated method for determining which methods of a given codebase or library can be involved in specific vulnerabilities.

To detect specific security vulnerabilities, data-flow analyses must be configured with specific methods. For example, executeQuery() can be a sink for CWE-89 (SQL injection), but not for CWE-601 (open redirect). Determining which Security-Relevant Methods (SRM) match which vulnerabilities can be difficult. Most data-flow analysis tools are configured with manually generated SRM lists, which can be incomplete, especially when analyzing new or custom code.

With Swan, we automatically determine which methods of a given codebase or library can be used for specific vulnerabilities, using a machine-learning approach that can detect sources, sinks, sanitizers, and authentication methods, and further classify those SRMs in different CWE categories.

Furthermore, we present SwanAssist, an IntelliJ plugin that allows the developer to manually train the classifier through active learning, thus improving the precision of the approach.

![project-swan.png](/assets/images/project-swan.png)

### Publications
- ISSTA 2019: [Codebase-adaptive detection of security-relevant methods](publication-swan.html) (Goran Piskachev, Lisa Nguyen Quang Do, Eric Bodden).
- ASE 2019 demo: [SwanAssist: semi-automated detection of code-specific, security-relevant methods](publication-swanassist.html) (Goran Piskachev, Lisa Nguyen Quang Do, Oshando Johnson, Eric Bodden).
