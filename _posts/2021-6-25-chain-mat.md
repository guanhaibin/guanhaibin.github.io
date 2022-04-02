---
title: "Coded Matrix Chain Multiplication"
categories:
  - conference publication
tags:
  - matrix multiplication
  - erasure coding
  - coding theory
  - distributed computing
  - information theory
---

Matrix multiplication is a fundamental building block in many machine learning models. As the input matrices may be too large to be multiplied on a single server, it is common to split input matrices into multiple submatrices and execute the multiplications on different servers. However, in a distributed infrastructure it is common to observe stragglers whose performance is lower than other servers at some time. In order to mitigate the adversarial effects of potential stragglers, various coding schemes for the distributed matrix multiplication have been recently proposed. While most existing works have only considered the simplest case where only two matrices are multiplied, we investigate a more general case in this paper where multiple matrices are multiplied, and propose a coding scheme that the result can be directly decoded in one round, instead of in multiple rounds of computation. Compared to completing the matrix chain multiplication in multiple rounds, our coding scheme can achieve significant savings of completion time by up to 90.3%.

<cite><a href="https://ieeexplore.ieee.org/abstract/document/9521282">Link to the Publication</a></cite>
