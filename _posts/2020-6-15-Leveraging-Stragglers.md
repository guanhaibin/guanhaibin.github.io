---
title: "Leveraging Stragglers in Coded Computing with Heterogeneous Servers"
categories:
  - conference publication
tags:
  - matrix multiplication
  - erasure coding
  - coding theory
  - distributed computing
  - information theory
---

With the increasing sizes of models and datasets, it has become a common practice to split machine learning jobs as multiple tasks. However, stragglers are inevitable when running a job on multiple servers. Compared to replicating each task on multiple servers, running coded tasks can tolerate the same number of stragglers with much fewer servers. However, additional results of tasks running on stragglers are typically disregarded in existing schemes of coded computing, incurring a waste of the resources on such servers. In this paper, we leverage the results of partially finished tasks. In existing designs that utilize partially finished tasks, they have only considered servers with homogeneous performance. However, in a typical distributed infrastructure, e.g., a cloud, servers with heterogeneous configurations are common. Therefore, we propose Spinner which can efficiently utilize the results of partially finished tasks even on heterogeneous servers. Spinner works with existing coding schemes for matrix multiplication, a fundamental operation in various machine learning algorithms, and can efficiently assign the workload based on the performance of the corresponding server. Furthermore, Spinner can equivalently adapt the coding scheme for heterogeneous servers, aligned with the expected workload assigned to each server, and thus save the complexity of decoding. Combining the two strategies together, we demonstrate in our experiments that Spinner can improve the time of matrix multiplication by up to 84.0% and thus improve the time of linear regression by 40.7%.

<cite><a href="https://ieeexplore.ieee.org/abstract/document/9213028">Link to the Publication</a></cite>
