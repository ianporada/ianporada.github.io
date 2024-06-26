---
title: META-Learning State-based Eligibility Traces for More Sample-Efficient Policy
  Evaluation
authors:
- Mingde Zhao
- Sitao Luan
- Ian Porada
- Xiao-Wen Chang
- Doina Precup
date: '2020-05-01'
publishDate: '2024-06-26T20:12:47.830194Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 19th International Conference on Autonomous Agents
  and MultiAgent Systems*'
abstract: Temporal-Difference (TD) learning is a standard and very successful reinforcement
  learning approach, at the core of both algorithms that learn the value of a given
  policy, as well as algorithms which learn how to improve policies. TD-learning with
  eligibility traces provides a way to boost sample efficiency by temporal credit
  assignment, i.e. deciding which portion of a reward should be assigned to predecessor
  states that occurred at different previous times, controlled by a parameter λ. However,
  tuning this parameter can be time-consuming, and not tuning it can lead to inefficient
  learning. For better sample efficiency of TD-learning, we propose a meta-learning
  method for adjusting the eligibility trace parameter, in a state-dependent manner.
  The adaptation is achieved with the help of auxiliary learners that learn distributional
  information about the update targets online, incurring roughly the same computational
  complexity per step as the usual value learner. Our approach can be used both in
  on-policy and off-policy learning. We prove that, under some assumptions, the proposed
  method improves the overall quality of the update targets, by minimizing the overall
  target error. This method can be viewed as a plugin to assist prediction with function
  approximation by meta-learning feature (observation)-based λ online, or even in
  the control case to assist policy improvement. Our empirical evaluation demonstrates
  significant performance improvements, as well as improved robustness of the proposed
  algorithm to learning rate variation.
---
