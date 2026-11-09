---
layout: page
title: My Research
description: Formal methods for safe cyber-physical systems, from reachability analysis and set containment to differential dynamic logic.
permalink: /myResearch/
nav: true
nav_order: 2
---

A lot of algorithms for cyber-physical systems are typically unsafe. For instance, on a higher level, trajectory planners often use machine learning or optimization solvers to calculate the next optimal trajectory; this works *most of the time*, but for safety-critical systems such as autonomous vehicles, smart power grids, or medical devices, incorrect predictions can result in catastrophic outcomes.

This is where formal methods enter the picture: Using a variety of techniques, system behavior can be predicted in a safe manner, for instance using approximations of reachable sets of dynamical systems (i.e., an approximation of the trajectories a model can physically reach), or the formal verification of the software that is running on the platform (i.e., is the code that is running actually performing what it was meant to do?).

My methods aim to advance this field, by combining methods from a variety of mathematical areas, such as functional analysis, convex geometry, complexity theory, or deductive logic, to guarantee that tomorrow's autonomous systems can be trusted.

Specifically, at the moment I am working a lot with matrix norms and containment problems for convex sets, which were the main topics during my PhD. However, my recent interests also include differential dynamic logic and the amazing world of mathematical logic, which I use to strengthen some of my results.
