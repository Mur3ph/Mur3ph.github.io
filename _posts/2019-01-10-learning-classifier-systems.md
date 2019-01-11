---

title: "Learning Classifier System"
date: 10-01-2019
---

What are Evolutionary Algorithms?

Evolutionary algorithms (EAs) are inspired by the biological model of evolution and natural selection first proposed by Charles Darwin in 1859. In the natural world, evolution helps species adapt to their environments. Environmental factors that influence the survival prospects of an organism include climate, availability of food and the dangers of predators.

Species change over the course of many generations. Mutations occur randomly. Some mutations will be advantageous, but many will be useless or detrimental. Progress comes from the feedback provided by non-random natural selection. For example, organisms that can survive for long periods without water will be more likely to thrive in dry conditions than those that can’t. Likewise, animals that can run fast will be more successful at evading predators than their slower rivals. If a random genetic modification helps an organism to survive and to reproduce, that modification will itself survive and spread throughout the population, via the organism’s offspring.

Evolutionary algorithms are based on a simplified model of this biological evolution. To solve a particular problem we create an environment in which potential solutions can evolve. The environment is shaped by the parameters of the problem and encourages the evolution of good solutions.

The field of Evolutionary Computation encompasses several types of evolutionary algorithm. These include Genetic Algorithms (GAs), Evolution Strategies, Genetic Programming (GP), Evolutionary Programming and Learning Classifier Systems.

The most common type of evolutionary algorithm is the generational genetic algorithm.  The basic outline of a generational GA is as follows (most other EA variants are broadly similar).  A population of candidate solutions is iteratively evolved over many generations. Mimicking the concept of natural selection in biology, the survival of candidates (or their offspring) from generation to generation in an EA is governed by a fitness function that evaluates each candidate according to how close it is to the desired outcome, and a selection strategy that favours the better solutions. Over time, the quality of the solutions in the population should improve. If the program is successful, we can terminate the evolution once it has found a solution that is good enough.