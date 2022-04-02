---
title: "Locally Random P-adic Alloy Codes with Channel Coding Theorems for Distributed Coded Tensors"
categories:
  - preprint
tags:
  - tensors
  - random codes
  - machine learning
  - symbolic-numeric computing
  - erasure coding
  - coding theory
  - distributed computing
  - information theory
---

Tensors, i.e., multi-linear functions, are a fundamental building block of machine learning algorithms. In order to train on large data-sets, it is common practice to distribute the computation amongst workers. However, stragglers and other faults can severely impact the performance and overall training time. A novel strategy to mitigate these failures is the use of coded computation. We introduce a new metric for analysis called the typical recovery threshold, which focuses on the most likely event and provide a novel construction of distributed coded tensor operations which are optimal with this measure. We show that our general framework encompasses many other computational schemes and metrics as a special case. In particular, we prove that the recovery threshold and the tensor rank can be recovered as a special case of the typical recovery threshold when the probability of noise, i.e., a fault, is equal to zero, thereby providing a noisy generalization of noiseless computation as a serendipitous result. Far from being a purely theoretical construction, these definitions lead us to practical random code constructions, i.e., locally random p-adic alloy codes, which are optimal with respect to the measures. We analyze experiments conducted on Amazon EC2 and establish that they are faster and more numerically stable than many other benchmark computation schemes in practice, as is predicted by theory.

<cite><a href="https://arxiv.org/abs/2202.03469v2">Link to the Publication</a></cite>
