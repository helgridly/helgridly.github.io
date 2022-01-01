---
layout: page
title: Resume
showtitle: false
permalink: /resume/
---

# Employment

### Sabbatical

Extended period of time off to decompress and reset.

---

### Principal Software Engineer - Foundation Medicine Inc.
**04.2020 - 04.2021**

I worked as a Tech Lead for a contractor-based team for a few months before switching over to a development team building v2 of FMI’s core Medical Reporting microservices.

As Tech Lead:
* Replaced a... "suboptimal" build process (one branch per sprint, manual build and promotion, dependencies on packages that no longer exist, build system = zip copy of a devops repo from a deleted SCM) with a Gitflow-like model, and built out the CI infrastructure to support it
* Helped organization understand that our FDA-mandated software validation did not require long merge freezes if we split “build an artifact” from “deploy the artifact”
* Debugging critical issues leading to validation failures (QA deleting data during tests; dropped promises)

As IC:
* Gathered requirements across multiple groups and stakeholders for a rules engine implementation (project shelved for later)
* Identified our numerous approvals processes as instances of general “business process automation” problem, built a microservice on top of off-the-shelf software to extract approval processes from the store of record, decoupling modifications to process from software upgrades
* Became de-facto DevOps liaison; wrote a lot of CloudFormation and Jenkins pipelines to build and deploy the team’s services

---

### Principal Software Engineer - Broad Institute of MIT and Harvard
**01.2017 - 04.2020**

I worked on [Terra](https://terra.bio) and its ecosystem since their inception in 2015. It’s a cloud-based system that allows genomics researchers to manage scientific tools and datasets and run their analyses at large scale. Architecturally, it’s a set of microservices running in Docker on Google Cloud; typically services are written in Scala/Slick/MySQL (I’ve done lots of this), with a frontend in ClojureScript (not me).

I contributed as an engineer, did systems design, led a team, mentored junior engineers, did R&D, and championed career advancement and learning inside our organization. Proudest moment: working with engineering managers to redefine our group’s software engineering levels to provide clarity and consistency when giving career feedback. I’ve found leading teams and mentoring and growing developers the most rewarding part of my career so far.

* As Advancement and Learning Facilitator, built out new career leveling rubrics for Associate to Principal SWE, and created 10% time program for self-driven projects
* Presented at GATK Workshop in Pretoria, South Africa; put together a series of exercises to walk attendees through learning WDL
* As Tech Lead for four developers, built Leonardo, a webservice to spin up Spark clusters on Google Cloud Dataproc installed with Jupyter Notebooks and Hail to enable analysts to explore and compute against their data interactively; handed off project to another TL once it was stable
* Rapid developed a microservice to pool Google Cloud Platform projects in test infrastructure, dropping integration test runtime from 55 to 15 minutes
* Took a three month sabbatical to investigate lossy compression of sequencing data, created a file format ~4% the size of its source BAM file, and gave a talk on it at the GA4GH 6th Plenary Meeting
* Built out a new Python microservice on Google App Engine on a tight deadline
* Reached #1 ranking of all-time messages in the Broad's Slack workspace, with over 115,000 messages posted over ~4.5 years.

#### Senior Software Engineer - Broad Institute of MIT and Harvard
**09.2013 - 12.2016**

* Helped write much of the workspace and analysis-submission service for Terra
* Scrum master fill-in for six months
* Ancient history: built a 3-month rapid prototype of a cloud-based workflow execution engine backed by Apache Aurora and Mesos; analysis for a $4m project to determine the statistical power of a new sequencing technique; development and support for the internal predecessor to terra.bio

---

### Gameplay Programmer - Splash Damage
**06.2011 - 05.2013**

* Titles worked on: [redacted secret project], _Batman: Arkham Origins_
* Hired for expertise with Unreal Engine as studio was transitioning from other technology. Documented common pitfalls and best practices; first point of contact for programmers asking advice about engine features and quirks
* Developed networked, scriptable, automated functional testing framework which now runs with every build made by the continuous integration system and has been ported to multiple projects
* Worked with designers to prototype and implement gameplay mechanics, give suggestions and feedback on feasibility, and explain how to tweak behavior using exposed variables
* Responsible for monitoring and improving performance, identifying hotspots and handing out or implementing optimizations

---

### Gameplay Programmer - Ninja Theory
**10.2008 - 06.2011**

* Titles worked on: _Enslaved: Odyssey to the West_, _DmC: Devil May Cry_
* Created extensible developer UI used across the studio for debugging purposes and enabling cheats
* Worked with designers to create, maintain and debug checkpoint system to trigger save games; wrote save game system including custom serializer; wrote stat tracking system and handled awarding in-game achievements
* Three months of performance and optimization work: finding expensive assets and notifying content creators; identifying bottlenecks in code and refactoring/caching results as necessary

# Education

### M.Eng. Computing, 1st Class Honors, Imperial College London 
**2004 – 2008**

Won Departmental Project Prize for Excellence and Best Presentation award for final year project on [dynamically modifying MIDI files during playback to suit mood](https://doczz.net/doc/444358/acronym---a-computational-re-orchestration-to-nuance-your...)

### Introduction to Biochemistry - Harvard Extension School
**Fall 2014**


