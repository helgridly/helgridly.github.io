---
layout: page
title: Writing
permalink: /writing/
---

A collection of pieces of technical writing I've done: some for work, some not.

## Genomics crash course

I wrote a crash course in genomics and cancer biology for software engineers joining Broad's [Data Sciences Platform](https://www.broadinstitute.org/data-sciences-platform){:target="_blank"}. The group's work was building scientific software for genomics researchers, often working on cancer treatments and diagnostics. New hires often found this deeply meaningful work, but the need to learn specialized domain knowledge on top of the usual new-hire rampup often caused overwhelm. Having had no formal bio training I had to learn this myself, and figured writing down what I knew would be a useful resource for others.

➡ **Google doc [here](https://docs.google.com/document/d/1-C_BI4mx0Amjxac7G908Wtmfuc_N8O4_UqSDPiZu_bo/edit?usp=sharing){:target="_blank"}.** Assumes a high-school level of biology. I also gave a version of this as a lunch talk, but it was never recorded.

## Functional programming in Scala, without too much category theory

Our group had been using Scala for a couple of years but not particularly idiomatically. We had a couple of new hires who wanted to push us more in the FP direction, but much of the FP-in-Scala community uses a lot of category-theory-speak. This caused consternation amongst some of us who thought that the `|+|` operator might be useful, but had an allergy to words like "semigroup" and "applicative".

I fought my way through the jargon and wrote an introduction to the new operators that skipped over most of the category theory. Unfortunately in the process of doing so, I ended up learning some category theory, so I wrote a version explaining that, too.

Assumes a working knowledge of Scala. These documents were written in mid-2017, and FP in Scala has since moved away from cryptic syntax like `<*>` towards more friendly things, so they're probably no longer useful as learning aids.

➡ **[Scala, without the category theory](https://docs.google.com/document/d/1peDiNwaWE-M8CH4IaDCbxCiscqYrYLhl/edit#){:target="_blank"}**  
➡ **[Scala, and some category theory](https://docs.google.com/document/d/1d3oi2t1Yz7XX9zVpuFeLSeXb_N09_tCJ/edit){:target="_blank"}**


## Advice on interviewing

I worked with a couple of mid-to-senior level engineers who felt uncomfortable leading interviews with candidates, especially the "tell me about a project you've worked on and we'll dig into the details together" panel. I enjoy interviewing, so I wrote some notes on ➡ **[how I interview](https://docs.google.com/document/d/1qNeXN_E_na_KXsZMaXRfYQcoT-0w59yjdmN1B7Tst68/edit#){:target="_blank"}** and the approach I take.

## Understanding options markets

In early 2021 I got interested in options trading (yes, around the GME bubble 🚀), and stumbled across the [Net Options Pricing Effect model](https://www.scribd.com/document/487296659/Investigating-Delta-Gamma-Hedging-Impact-on-SPY-Returns-2007-2020){:target="_blank"} created by [Lily Francus](https://twitter.com/nope_its_lily){:target="_blank"}. Having had no formal finance training it was a lot to wrap my head around, and I spent a few days diving into the mechanics of options trading to understand it. There are _many_ articles online on the  basics of options trading, but past the shallow water there is very little instruction. So I decided to write some.

➡ **Blog post [here](https://helgridly.github.io/finstuff/understanding-NOPE/){:target="_blank"}**. Pitched as an introduction to NOPE, but quickly dives into the inner workings of option trading as a whole. Assumes some prior knowledge of options trading.