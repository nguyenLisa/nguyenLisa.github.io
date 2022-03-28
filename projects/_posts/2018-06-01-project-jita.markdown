---
layout: post
title:  "Just in time analysis"
display_date:   "2016 - 2018"
categories: user-study Cheetah
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
The Just-in-time analysis concept aims at making static analysis more usable to the end user, often the code developer. It allows analysis writers to encode prioritization properties into the analysis. At runtime, certain paths are analyzed before others, allowing important results to be returned first. Cheetah is an implementation of the Just-in-Time analysis concept for taint analysis for Android applications. It is integrated in the Eclipse IDE as a plugin.

![project-jita.png](/assets/images/project-jita.png)

### Artifacts
- [User study documents](assets/docs/artifacts/JITA_UserStudy.pdf)
  - Survey template, participants’ responses, interview protocol.

### Publications
- ISSTA 2017: [Debugging static analysis](publication-jita.html) (Lisa Nguyen Quang Do, Stefan Krüger, Patrick Hill, Karim Ali, Eric Bodden).
- ICSE 2017 demo: [Cheetah: just-in-time taint analysis for Android apps](publication-cheetah.html) (Lisa Nguyen Quang Do, Karim Ali, Benjamin Livshits, Eric Bodden, Justin Smith, Emerson Murphy-Hill).
