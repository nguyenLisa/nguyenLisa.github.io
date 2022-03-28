---
layout: post
title:  "Automated benchmark management"
display_date:   "2015 - 2020"
categories: benchmark methodology
date:   1970-01-01 00:00:00 +0000 # Do not use. Only there because posts require a date.
---
ABM (automated benchmark management) is a methodology and a web application for automating the creation and maintenance of benchmark suites.

When empirically testing one’s tools, one can either use well established benchmark suites, create one’s own micro-benchmark, or mine open-source repositories for real-life projects. In the first case, benchmark suites are often created by hand for one single purpose and remain unchanged for years, making them ill-adapted to the tool under test, and non-representative of real-life software.

In the second case, tool authors also crafting the benchmark is often considered a threat to the validity of the evaluation. 

The ABM methodology has been designed to semi-automatically build and maintain benchmark collections that correspond to a user specification. It mines GitHub for up-to-date projects, runs user-specified filters, and rules out those projecs that do not fit, nor are not buildable. The final collection is the source code and executables of buildable, current, and user-specific GitHub projects.

![project-benchmark.png](/assets/images/project-benchmark.png)

### Artifacts
- [Old web page](http://www.st.informatik.tu-darmstadt.de/artifacts/webapps/)

### Publications
- SOAP 2016: [Toward an automated benchmark management system](publication-abm.html) (Lisa Nguyen Quang Do, Michael Eichberg, Eric Bodden).