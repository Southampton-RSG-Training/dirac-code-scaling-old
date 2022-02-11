---
title: "Understanding Code Scalability"
slug: dirac-code-scaling-understanding-code-scalability
teaching: 0
exercises: 0
questions:
- "What is code scalability?"
- "Why is code scalability important?"
- "How can I measure how long code takes to run?"
objectives:
- "Describe why code scalability is important when using HPC resources"
- "Explain the difference between walltime and computational time"
- "Summarise the dangers of premature optimisation"
- "Describe the differences between strong and weak scaling"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## Using HPC Resources Efficiently

FIXME: introduce wall time and computational time. Importance of efficiency w.r.t. HPC resources, and risk of non-scalable (potentially badly optimised) code consuming more resources than it can effectively use. Importance of measurement - when we know how a particular code scales, it gives us a clearer idea of how many resources we should request

## Premature Optimistion

FIXME: regarded as bad practice, *may* lead to more complicated and unreadable code, need to profile code first. Without understanding can waste development time. Often difficult to do anticipate and improve on sophistication of common language interpreters and compilers and their "under the hood" optimisations. Summary of https://wiki.c2.com/?PrematureOptimization, and essentially "We should forget about small efficiencies, say about 97% of the time: premature optimization is the root of all evil. Yet we should not pass up our opportunities in that critical 3%." Anything non-trivial, don't optimise, but don't avoid obvious optimisations.

## How can we Characterise Scalability for Code?

FIXME: need to understand scalability firsty. Strong vs weak scaling, e.g. https://hpc-wiki.info/hpc/Scaling_tests

{% include links.md %}
