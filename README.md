# EKC-Expert-Knowledge-Constraint-based-algorithm
This study discusses the definition of model interpretability in traffic crash analytics, including trust, causality, heterogeneity, transferability, and stability. A semi-data-driven Bayesian Network (BN) structure learning algorithm, the **Expert Knowledge Constraint-based (EKC)** algorithm, is proposed. By integrating expert knowledge with conditional independence tests, the EKC algorithm constructs a causal relationship network with a high level of interpretability. The algorithm was applied to a highway safety scenario using crash data collected in 2022 from the HuNing highway in China.

The EKC algorithm synergizes data-driven learning with domain expertise through a priori causal constraints. 

There are two steps to build the Bayesian network structure using EKC.
- Constructing a skeleton, which represents the undirected structure of the graph.
- Determining the directions of edges between nodes based on the skeleton.

Due to the data limitation, authors do not have the right to share the raw data. The Jupyter notebooks with original results were shared.

The main Python library for BN construction is 'pgmpy'.
