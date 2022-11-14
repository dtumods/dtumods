---
title: George Em Karniadakis
author: 
layout: post
icon: fa-chalkboard-teacher
---

# Physics-informed machine learning: Blending data and physics for fast predictions

Despite great progress in simulating multiphysics problems using the numerical
discretization of partial differential equations (PDEs), one still cannot seamlessly incorporate noisy
data into existing algorithms, mesh generation remains complex, and high- dimensional problems
governed by parameterized PDEs cannot be tackled. Moreover, solving inverse problems with
hidden physics is often prohibitively expensive and requires different formulations and elaborate
computer codes. Machine learning has emerged as a promising alternative, but training deep neural
networks requires big data, not always available for scientific problems. Instead, such networks can
be trained from additional information obtained by enforcing the physical laws (for example, at
random points in the continuous space- time domain). Such physics- informed learning integrates
(noisy) data and mathematical models, and implements them through neural networks or other
kernel- based regression networks. Moreover, it may be possible to design specialized network
architectures that automatically satisfy some of the physical invariants for better accuracy, faster
training and improved generalization. Here, we review some of the prevailing trends in embedding
physics into machine learning, present some of the current capabilities and limitations and discuss
diverse applications of physics- informed learning both for forward and inverse problems, including
discovering hidden physics and tackling high-dimensional problems.