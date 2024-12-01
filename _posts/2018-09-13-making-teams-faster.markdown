---
layout: post
title: Making teams faster
date: '2018-09-13 18:07:42'
---

I often get asked how to make teams faster, so I decided to jot down a few thoughts.

The key to success is working with the team over time through continuous feedback loops to identify and implement improvements.

## Team formation

Before even looking at mechanisms to make teams "faster", the starting point is proper team formation.

Russell Ackoff did an [excellent talk](https://www.youtube.com/watch?v=OqEeIG8aPPk) on system-thinking, which summarises how I approach teams formation and management.

A few notes:

- **Size:** Based on personal experience, I typically work on an ideal team size of 4-7 people with a preference on five as the most effective engineering team size. _(note: There are quite a few studies on the topic, but nothing I want to link because I want to publish this post and not spend hours finding data that I'm 100% comfortable with)_
- **Bootstrapping:** Psychological safety and team chartering is the most critical building block to team effectiveness. In any environment, this should be the starting point to ensure teams form well,
  - people are comfortable to give each other feedback and are comfortable to be themselves at work,
  - people know what they need expect from each other, and
  - the reason for the team's existence relative to the company is crystal clear.
- **Mutability:** Teams are immutable meaning with every team staffing change we reset the team’s formation. With that, I am reluctant to move people between teams without proper consideration.
- **Environment and tools:** Give people the tools and the environment in which they can do their best work and trust them to get the job done (drives tool efficacy, team engagement and creativity).

Have a look at [Google Project Aristotle](https://rework.withgoogle.com/blog/five-keys-to-a-successful-google-team/) and the [Liftoff book](https://pragprog.com/book/liftoff/liftoff-second-edition).

## Effectiveness (Maximising value)

The best software is the software that we don’t build while still bringing the value to our customers. To achieve this requires close collaboration between product, experience and engineering to find those magical solutions the customer problems. Techniques that have served me well are things like (in order of breath):

- Business Model- / Lean Canvas
- Impact mapping
- Auftragsklärung
- Story mapping
- Hamburger method / MOSCOW / Kano / etc.

Examples where my colleagues and I did this:

- Legal process automation (as coach): Only automated 2 out of 42 processes to get 98% usage coverage effectively reducing timeline from 10 months to 6 weeks. The team used manual data capture for the remaining flows.
- Tourism product (as an engineer): Reduced scope to 10% of initially thought to build a top grossing app (1 year reduced to 3 months).
- Accounting software (as manager): Reduced work from months to days with numerous projects. In another example, we built low-fidelity solutions in days instead of months.

## Efficiency (Hidden capacity)

The name of the game here is to eliminate waste. To eliminate waste teams need time to find and remove wasteful activities, which means that they need to reduce the active work-hours for the teams to create time for improvement.

The seven forms of waste in Lean Software Development is an excellent place to start (one of those "unnecessary features" fall into Effectiveness above).

> Tip: Detecting and fixing these different types of waste isn't as easy as reading the book and then magically doing it the next day. Experiment with various hypotheses, measures, and solutions. Allow yourself to try out things that feel wrong!

Some areas to look at with supporting data where I can still remember (not an exhaustive list):

- **Focus:** Maximise collaboration within the team by introducing team rooms. The result was between 50 and 300% improvement in velocity.
- **Defects (in development):** Find ways to prevent rejections (user, experience, testing, etc.) by creating cross-functional groups that do pair- and mob-programming. I repeatably saw the velocity increase 20-100% with some teams going down to zero-defects (in dev).
- **Defects (from production):** Run post-incident reviews, to understand what the team missed during the engineering process.
- **Work in progress:** Focussing on throughput (velocity) instead of utilisation (busyness) results in higher focus fewer defects, shorter cycle times, and also reduces partially done (often thrown away). I've seen teams reduce cycle times from:
  - 100 to 4 days with single piece flow (Freight software)
  - 90 to 5 days with mob- and pair-programming (Accounting software)
  - 3 months to 2 weeks with WIP-limits at one-per-person (Email marketing)
- **Decision making:** I’ve seen teams and even companies lose years. Observe decision making across functions as well as intra- and inter-team.
  - Inter: Ensure teams can make decisions without seeking external help.
  - Intra: Ensure there are leaders in the team (hopefully emergent) to help avoid groupthink and paralysis
- **Automation:** Identifying repetitive tasks and automating it where needed. I am currently experimenting with people focussed on developer productivity

## Adding more people

An option but often not feasible because of financial and productivity reasons.

On the productivity side, I would avoid having more than nine people on a shared codebase. Numerous studies show that teams of 9+ produce less with higher defects numbers on shared codebases.

<!--kg-card-end: markdown-->