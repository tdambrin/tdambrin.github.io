---
title: '[Research] Studying heuristics to solve Bayesian Games through Linear Programs'
date: 2021-12-30
permalink: /posts/2021/12/bayesian-games/
tags:
  - research
  - opensource
relevant: true
---

## Studying heuristics to solve Bayesian Games through Linear Programs

Bayesian Games are instances of a relatively simple class of games. They are decision-making model used to derive optimal strategies for incomplete information, they therefore represent a step in a partially observable markov decision processes (POMDP). 

Optimal strategies in this games represent a Nash Equilibrium that can be found through solving a Linear Program. The resolution of such systems runs in polynomial time which is a limit to systems integrating this approach. Building a sequential decision making solver where each step is polynomial might indeed be challenging. Therefore, we propose to study the use of search heuristics to consider most probable states first. 

Two heuristics were tested. Results show that, even though solving time was improved, solving complexity remains polynomial. Testing more complex heuristics could result in complexity decrease but nothing shows evidence of that here.

**Read full [report](/files/bayesian-hs-report.pdf).**

**View Library [homepage](https://sdmstudio.github.io) or [code base](https://github.com/SDMStudio/sdms)**