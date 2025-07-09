---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a thrid-year Ph.D. student in Data Science at the [School of Data Science](https://sds.cuhk.edu.cn/), [the Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en). Prior to this, I obtained a B.Sc. in Applied Mathematics from Shandong University, and a M.S. in Data Science from the University of Wisconsin-Madison. 

My research interests lie in distributed learning and large-scale optimization, particularly in designing communication-efficient algorithms for networked systems and developing applications in machine learning, deep learning, and large language models. I also focus on federated learning and its real-world applications.



Publications and Preprints
=====
\* indicates equal contributions

- **Runze You** and Shi Pu, Stochastic Push-Pull for Decentralized Nonconvex Optimization, submitted. [arXiv](https://arxiv.org/pdf/2506.07021).
  - In this paper, we present a comprehensive analysis to understand the convergence behavior of the Push–Pull method for decentralized optimization with stochastic gradients (Stochastic Push–Pull) by clarifying the algorithm’s underlying assumptions, particularly those regarding the network structure and weight matrices and establishing the convergence rate under smooth nonconvex objectives.

- **Runze You\***, Kun Huang\* and Shi Pu, Decentralized Min-Max Optimization with Gradient Tracking. [arXiv](https://arxiv.org/pdf/2505.10631).
  - This paper presents a novel distributed formulation of the min-max optimization problem. Such a formulation enables enhanced flexibility among agents when optimizing their maximization variables.

- **Runze You** and Shi Pu, Distributed Learning over Arbitrary Topology: Linear Speed-Up with Polynomial Transient Time, submitted. [arXiv](https://arxiv.org/pdf/2503.16123), [code](https://github.com/ryou98/SpanningTreePushPull).

  - In this paper, We propose a novel algorithm, ``Spanning Tree Push-Pull'' (STPP), which employs two spanning trees extracted from a general communication graph to distribute both model parameters and stochastic gradients. Unlike prior approaches that rely heavily on spectral gap properties, STPP leverages a more flexible topological characterization, enabling robust information flow and efficient updates.

- **Runze You** and Shi Pu, B-ary Tree Push-Pull Method is Provably Efficient for Distributed Learning on Heterogeneous Data, Advances in Neural Information Processing Systems (**NeurIPS**), 2024. [OpenReview](https://openreview.net/forum?id=3MnXAcTBD3), [arXiv](https://arxiv.org/pdf/2404.05454), [code](https://github.com/ryou98/BTPP).
  
  - In this paper, we consider the distributed learning problem where a group of agents cooperatively minimizes the summation of their local cost functions based on peer-to-peer communication. Particularly, we propose a highly efficient algorithm, termed ``B-ary Tree Push-Pull'' (BTPP), that employs two B-ary spanning trees for distributing the information related to the parameters and stochastic gradients across the network.






