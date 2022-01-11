---
layout: page
title: Projects
permalink: /projects/
---

### Rethinking software engineering levels

In mid 2019 I took on a 50%-time role as "Advancement and Learning Facilitator" in Broad's Data Sciences Platform. One of my big projects in this role was to **redesign our software engineering ladder** in collaboration with our engineering managers.

➡ You can read the **writeup of that process [here](/levels){:target="_blank"}**.

### A new file format for genomic data

Genomic data is huge - often hundreds of gigabytes per sequence file. For sequencing centers such as the Broad Insitute's [Genomics Platform](https://www.broadinstitute.org/reading-and-editing-biology/genomics-platform){:target="_blank"}, the cost of keeping historical data around can be very high, even when moving to cold storage.

I took a three month sabbatical to see if lossy compression could be used without affecting the data's usefulness for scientific analysis. I wrote a **compression algorithm that reduced file sizes to 4%** and ~28% the size of its lossy competitor, and travelled to Basel, Switzerland to present it at the Global Alliance for Genomics & Health's 6th Plenary Meeting.

➡ **Watch [the talk](https://www.youtube.com/watch?v=TaqFBgaZHmE&t=13920s){:target="_blank"}** or **flip through [the slides](https://docs.google.com/presentation/d/1EAG3Mz_Rwszn1xzvLFlFDtZJKeTfTcqo/edit){:target="_blank"}**.

### Reducing integration test runtime from 55 minutes to 15 minutes

Our integration tests relied heavily on creating clean [Google Cloud Platform projects](https://developers.google.com/apps-script/guides/cloud-platform-projects){:target="_blank"} for test isolation. Project creation itself takes a few seconds but there were some group creation and population steps that were eventually consistent, emphasis on the _eventually_. This resulted in erratic test timeouts when Google was feeling slow that day, and slowly the timeout was increased as tests repeatedly failed.

One day I overheard someone say "I guess I'll increase the timeout to 20 minutes". I turned horror into initiative and wrote a tech doc to pool the projects within an hour. Within a week I'd built a prototype and within a month [the microservice](https://github.com/broadinstitute/gpalloc){:target="_blank"} was deployed to our test environment. Our test runtime dropped over 70% as a result.

### How much does Boston Police Department spend on surveillance equipment?

A project I did for the ACLU of Massachusetts' tech division, cross-referencing BPD's spending data (sourced from the City of Boston's [Checkbook Explorer](https://spending.data.boston.gov/){:target="_blank"}) against companies listed on the [Surveillance Industry Index](https://sii.transparencytoolkit.org/){:target="_blank"}.

➡ **GitHub repo with Jupyter notebook [here](https://github.com/helgridly/bpd-sii){:target="_blank"}**.


### Is there profit to be made trading SPAC warrants?

In late 2020 there was a craze in the financial markets for SPACs (special purpose acquisition companies, essentially shell companies that would search for a startup to merge with, launching the startup while avoiding the IPO process). Warrants are cheap financial instruments attached to SPACs, and are thus a way to potentially make big returns on small investments. There were many stories of traders doing this, so I scraped a _lot_ of data to find out if trading them was generally profitable. The short answer is "yes, if you have a time machine" -- soon after I did the analysis, the craze blew up, the market oversaturated, and this investment strategy got even more risky.

➡ **Writeup [here](https://elgridly.tech/finstuff/SPAC-warrants/){:target="_blank"}**.

### A quick look at the 2017 Alabama special Senate election

The Doug Jones v. Roy Moore special Senate election in AL was close, and a particular breakdown of the vote totals went viral on social media. I decided to do a little digging of my own, and concluded that the biggest driver for the election was turnout, not race or gender.

➡ **Writeup [here](https://docs.google.com/document/d/1eMpj1ZRfNhrW7pOCyq7jdnYA6_WT508jIT3Ku4TRr0U/edit#){:target="_blank"}.**

### Other things

I also have many projects that got shelved, so if you'd ever like to discuss using FEC data to track political donations, or the time I wrote a Solidity parser while investigating the extremely scammy end of the crypto market, do ask!
