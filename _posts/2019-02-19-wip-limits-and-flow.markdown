---
layout: post
title: The importance of WIP limits
date: '2019-02-19 21:25:56'
---

I once came across a team of 9 (yeah, I know it is too many) with five deliverables in flight. Looking at their work allocations, it seems 0.5 to 2.5 people were working on each deliverable. This immediately raised alarm bells because you can safely conclude that people are shared across tasks and that some work in isolation.

This approach is sub-optimal as it causes invisible\* side-effects, which slow down the overall delivery of the team;

- People shared across tasks causes situations they wait for others, which slows delivery down. This causes a traffic jam because people start waiting for people who are waiting for others.
- Quality is typically lower because people work in isolation, so their mistakes are only detected when bugs are discovered during testing or in production. Quality is everyone’s responsibility, and our goal is to prevent bugs from happening in the first place.
- Some teams never form because people work as individuals, which means they never get to the point where they build the deep trust required for high performance and innovation.

There may be valid scenarios where teams share subject-matter experts (problem space or module) or specialists (like quality assistance) across the work. Even here, there are problems because ;

- the shared persons’ own ability to contribute is reduced because they are spending a lot of time switching work,
- their ability to mentor the team is reduced because they are only working with a small subset and also not for the whole time, and
- It drives "hero culture”, which causes people to pool knowledge and negatively affects others' growth.

A natural consequence is that these teams tend to be VERY busy while not producing much.

_Solutions to consider:_

- Reduce work in flight to one per team
- With a _team_ think of a group of people who work on one piece of business value together.
- Try to structure teams working as pods of 3-4 people.
- Focus everyones' effort on finishing work as opposed to starting. Finishing the goal should be achieving business objectives instead of simply deploying production software.

Other observations:

- The team is also assigning work to people at the beginning of the week, which means that people don’t get the opportunity to choose the best person for the task when the task is picked up.

_\*The idea of a Kanban board is to make these things visible so people can manage the flow and prevent flow impediments early._ The team has numerous kanban boards, which means they cannot identify these flow problems effectively. Each cohesive team should ideally have one Kanban board and one only.

_Further reading:_

- [Nice summary of Lean Thinking](https://less.works/less/principles/lean-thinking.html) (I’m not the biggest fan of LeSS)
- [HBR: Six Myths of Product Development](https://hbr.org/2012/05/six-myths-of-product-development)
- Cool video on [the resource utilization trap](https://www.youtube.com/watch?v=CostXs2p6r0)
- [The Logic of Flow: Some Indispensable Concepts](https://www.youtube.com/watch?v=rc1MqHsiiKo)
- [Principles of Product Development Flow](https://www.amazon.com/Principles-Product-Development-Flow-Generation-ebook/dp/B007TKU0O0)
<!--kg-card-end: markdown-->