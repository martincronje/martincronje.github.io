---
layout: post
title: The Technical Debt metaphor is broken
date: '2015-11-07 11:43:28'
---

I was first introduced to the Technical Debt metaphor in 2008 in this [video](https://www.youtube.com/watch?v=pqeJFYwnkjE). The key takeaway for me is the Technical Debt metaphor to help us explain how the disorder within a system affects future development work.

Martin Fowler went further to classify the different causes of Technical Debt into a very helpful [quadrant](http://martinfowler.com/bliki/TechnicalDebtQuadrant.html). For me, this quadrant is a very complete classification of the things that cause disorder within a software system.

> "A particular benefit of the debt metaphor is that it's very handy for communicating to non-technical people." - Martin Fowler

The important keyword for me here is "metaphor". Metaphors only serve as symbolic description of what something is and shouldn't be used as a literal interpretation. Metaphors (like most models) are abstractions and aim to highlight certain characteristics or behaviours through analogy.

In the instance of Technical Debt the metaphor is intended to **highlight the compounding effect** of that disorder (entropy) has within a system. This effect applies equally to all states of disorder whether it is [just a mess](https://sites.google.com/site/unclebobconsultingllc/a-mess-is-not-a-technical-debt) or deliberate prudent technical debt.

There are two problems with the wide use of this metaphor:

- People continually try to draw a direct correlation between Technical Debt and Financial Debt and that causes confusion. We are using the metaphor only to explain the compounding effect on future maintenance costs. Unlike financial debt, the classification of technical debt is quite subjective and hard to measure, causing a wide variety of alternative uses and disagreement on meaning. The prime example being: _"Is a mess technical debt?"_
- The term Technical Debt is benign enough for people to continue doing it. _(Credit to Ron Jeffries for saying this in an open space during Agile2015)_. We should give it a more severe name like "disrepair" or "disorder" as caused by entropy.

_(It is worth mentioning that synonyms to entropy are deterioration, degeneration, crumbling, decline, degradation, decomposition, breaking down, collapse.)_

**Solution: See software as an depreciating asset**

I propose another approach where we rely less on an incomplete metaphor. By addressing the problem directly.

Software is an asset and in the US custom software is even classified as a fixed asset ([here](http://businessecon.org/2013/01/the-definition-of-fixed-assets/) and [here](http://www.accountingtools.com/definition-fixed-asset)). An asset's value is determined by the condition in which that asset exists and its value depreciates as it falls into disrepair.

> In Mythical Man Month, Fred Brooks said of entropy _"All repairs tend to destroy the structure, to increase the entropy and disorder of the system. Less and less effort is spent on fixing the original design flaws; more and more is spent on fixing flaws introduced by earlier fixes."_

From an asset perspective refactoring synonymous to upkeep (maintenance). As with upkeep, through refactoring we avoid having the system fall into disorder. Our system's usefulness and value depreciates as it falls into disrepair. This state of disorder behaves similarly to financial debt in that it compounds. This lack of upkeep causes a compounded increase in the cost of further development and fixes within the codebase.

A further merit is that software **IS** an asset as we can use established reasoning about asset freely. We don't have to rely on flaky financial markets analogies anymore.

We shouldn't forget about the merit of the Technical Debt metaphor as well. When you talk to non-technical people just say that the lack of upkeep has a compounding effect and only when they really struggle to understand should you use the "Debt" metaphor.

Aside, I see immense value in the Technical Debt quadrant and simply propose that we call it something more appropriate such as the "Entropy Quadrant" or even more evocative the "Deterioration Quadrant".

<!--kg-card-end: markdown-->