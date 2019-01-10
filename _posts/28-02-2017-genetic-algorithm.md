---
layout: post
title: "Paul Murphy, Optimzing Genetic Algorithm"
date: 02-04-2017
---

Optimization algorithms, which try to find the minimum values of mathematical functions, are everywhere in engineering. Among other things, they’re used to 
evaluate design tradeoffs, to assess control systems, and to find patterns in data.

One way to solve a difficult optimization problem is to first reduce it to a related but much simpler problem, then gradually add complexity back in, solving 
each new problem in turn and using its solution as a guide to solving the next one. This approach seems to work well in practice, but it’s never been characterized
theoretically.