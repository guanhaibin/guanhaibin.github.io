---
title: "Straggler-free Coding for Concurrent Matrix Multiplications"
categories:
  - conference publication
tags:
  - matrix multiplication
  - erasure coding
  - coding theory
  - distributed computing
  - information theory
---

Matrix multiplication is a fundamental building block in various distributed computing algorithms. In order to compute the multiplication of large matrices, it is common practice to distribute the computation into multiple tasks running on different nodes. In order to tolerate potential stragglers among such nodes, various coding schemes have been proposed which add additional coded tasks. However, most existing coding schemes for the matrix multiplication are constructed for only one matrix multiplication, while it is common to compute multiple matrix multiplications concurrently in large-scale distributed computing workloads. In this paper, we propose a novel coding framework where the results of multiple multiplications can be obtained within one job concurrently. Compared with running the multiplications separately with multiple jobs, our work demonstrates that the same number of stragglers can be tolerated with much fewer tasks.

<cite><a href="https://ieeexplore.ieee.org/abstract/document/9174239">Link to the Publication</a></cite>
