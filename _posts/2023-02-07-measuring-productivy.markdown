---
layout: post
title: Measuring productivity
date: '2023-02-07 21:39:48'
---


*Disclaimer: Each company has different tech stack and delivery challenges, but the methodology for measuring and improving productivity applies equally.*

In a previous role, I was hired to “Improve Delivery Flow” ([ref Team Topologies](https://teamtopologies.com/?ref=cron.je)) across an org of about ~400, with an emphasis on process improvements, platform capabilities and debt-recovery work.

# Problem
Delivery in the company slowed down over the years and they needed to find a way to unblock and speed it up to the "good old days". Anecdotal observations showed that:
* Engineers hated the toolchain and were waiting for ages for local and remote builds.
* There was very low confidence that releases would go without failure which resulted in expensive regression test cycles.
* Deployments required manual intervention due to legacy interpretation of PCI compliance.
* The slow speed to meant that merges became bigger and large merge conflicts were common.
* Product managers had to wait until late in the process to see features work end-to-end.

# Measurement
To improve something, one must first measure it, and we found that [DORA](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance?ref=cron.je) is incomplete as it focuses too much on CD and not enough on teams getting shit done. [SPACE](https://queue.acm.org/detail.cfm?id=3454124&ref=cron.je) as a framework proved valuable but needed to be interpreted for our needs. We landed on:
* Satisfaction: Internal Developer NPS and CSAT
* Performance: Change Failure rate (and Product Management satisfaction implied)
* Activity: Merge & Deploy Frequency and Cycle time (looking at the merge and deploy size was interesting too)
* Collaboration: Only measure in the platform by looking at incoming Service Requests and adoption of services
* Efficiency: Qualitative measurement of Toil from Developer Interviews (mainly Staff and Principal engineers)

# North Star
We encouraged product, platform, and sub-speciality (aka practice) teams to calibrate their improvement projects to the above measurements working towards the following north star metrics:
**Year 1:**
* Code integrated within 10 min to Test
* Non-prod provisioned within hours
* Refactored team ownership scope to enable deploying independently where relevant

**Year 2**
* Code integrated within 10 min to Prod
* Prod can be provisioned within hours
* Refactored team ownership scope to enable deploying independently where relevant

**This led to projects such as:**
* Build automation improvement to provide developer feedback on merge within 10 minutes
* Provide self-service build for teams refactoring (fracturing) their ownership scope
* Create base images for non-prod environment to facilitate automated provisioning
* Reduce manual regression test cycle to hours by removing unneeded tests

## Key learnings
* Using a framework like SPACE forced us to think about what productivity means for us.
* Setting a North Star for our tech strategy enabled teams to rally around the goal
* Defining what productivity meant enabled us to have effective conversations about improving delivery with stakeholders such as the CEO and Product Management
