## A Curated list of papers related to efficient graph machine learning


### Model Level (Most papers come from ICML, NIPS and ICLR)
| **Title**                                                                                 | **Conference** | **Keywords**          | ** Paper ** | **Code** |
|-------------------------------------------------------------------------------------------|----------------|-----------------------|-------------|----------|
| Layer-Neighbor Sampling — Defusing Neighborhood Explosion in GNNs                         | NIPS 2023      | Sampling              | | |
| Efficient Learning of Linear Graph Neural Networks via Node Subsampling                   | NIPS 2023      | Sampling              | | |
| Communication-Free Distributed GNN Training with Vertex Cut                               | Arxiv 2023     | Distributed           | | |
| DSpar: An Embarrassingly Simple Strategy for Efficient GNN Training and Inference via Degree-based Sparsification | TMLR 2023 | Data-driven, Graph Condensation| | |
| Learning Large Graph Property Prediction via Graph Segment Training                       | Arxiv 2023     | Graph Transformer     | | |
| LazyGNN: Large-Scale Graph Neural Networks via Lazy Propagation                           | ICML 2023      |                       | | |
| Graph Ladling: Shockingly Simple Parallel GNN Training without Intermediate Communication | ICML 2023      | Distributed           | | |
| GOAT: A Global Transformer on Large-scale Graphs                                          | ICML 2023      | Graph Transformer     | | |
| Do Not Train It: A Linear Neural Architecture Search of Graph Neural Networks             | ICML 2023      | NAS                   | | |
| Fast Online Node Labeling for Very Large Graphs                                           | ICML 2023      |                       | | |
| Graph Neural Tangent Kernel: Convergence on Large Graphs                                  | ICML 2023      |                       | | |
| RSC: Accelerate Graph Neural Networks Training via Randomized Sparse Computations         | ICML 2022      |                       | 
| LMC: FAST TRAINING OF GNNS VIA SUBGRAPH-WISE SAMPLING WITH PROVABLE CONVERGENCE           | ICLR 2023      |                       | | |
| MLPInit: Embarrassingly Simple GNN Training Acceleration with MLP Initialization          | ICLR 2023      | GNN as MLP            | | |
| Influence-Based Mini-Batching for Graph Neural Networks                                   | LOG 2022       |                       | 
| GraphFM: Improving Large-Scale GNN Training via Feature Momentum                          | NIPS 2022      |                       | | |
| A Comprehensive Study on Large-Scale Graph Training: Benchmarking and Rethinking          | NIPS 2022      |                       | | |
| ReFactor GNNs: Revisiting Factorisation-based Models from a Message-Passing Perspective   | NIPS 2022      |                       | | |
| Sketch-GNN: Scalable Graph Neural Networks with Sublinear Training Complexity             | NIPS 2022      |                       | | |
| Graph Condensation for Graph Neural Networks                                              | ICLR 2022      | Data-driven, Graph Condensation | | |
|Graph-less Neural Networks: Teaching Old MLPs New Tricks via Distillation                  | ICLR 2022      | GNN as MLP            | | |
| EXACT: Scalable Graph Neural Networks Training via Extreme Activation Compression         | ICLR 2022      |                       | 
| SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs     | KDD 2022 | | 
| Graph Condensation via Receptive Field Distribution Matching                              | Arxiv 2022     |                        | | |
| GNNAutoScale: Scalable and Expressive Graph Neural Networks via Historical Embeddings      | ICML 2021     | Large Graph, Sampling | | |
| A Unified Lottery Ticket Hypothesis for Graph Neural Networks                             | ICML 2021      |                       | | |
| VQ-GNN: A Universal Framework to Scale up Graph Neural Networks using Vector Quantization | NIPS 2021      | Quantization          |






### ML/Sys-codesign level (Most papers come from SIGMOD, VLDB, OSDI, ICDE, ...)

| **Title**                                                                                 | **Conference** | **Keywords**          |**Paper**|**Code**|
|-------------------------------------------------------------------------------------------|----------------|-----------------------|---------|--------|
|FLASH: A Framework for Programming Distributed Graph Processing Algorithms                 | ICDE 2023      |                       |   
| ReFresh: Reducing Memory Access from Exploiting Stable Historical Embeddings for Graph Neural Network Training | Arxiv 2023 | | | |
| DSP: Efficient GNN Training with Multiple GPUs                                            | PPoPP 2023     |                       | | |
| PiPAD: Pipelined and Parallel Dynamic GNN Training on GPUs                                | PPoPP 2023     |                       | | |
| Sancus: staleness-aware communication-avoiding full-graph decentralized training in large-scale graph neural networks | VLDB 2023  | | | |
| Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective| MLSYS 2022   | Kernel                | | |
| Sequential Aggregation and Rematerialization: Distributed Full-batch Training of Graph Neural Networks on Large Graphs | MLSYS 2022 | Distributed, full-batch | 
| Accelerating Training and Inference of Graph Neural Networks with Fast Sampling and Pipelining | MLSYS 2022 |                      | 
| Graphiler: Optimizing Graph Neural Networks with Message Passing Data Flow Graph          | MLSYS 2022     |                       | 
| BNS-GCN: Efficient Full-Graph Training of Graph Convolutional Networks with Partition-Parallelism and Random Boundary Node Sampling | MLSYS 2022 | | | |
| Algorithm and System Co-design for Efficient Subgraph-based Graph Representation Learning | VLDB 2022      |                       | | |
| Accurate and Scalable Graph Neural Networks for Billion-Scale Graphs                      | ICDE 2022      |                       |


### Non-graph but interesting & important work
| **Title**                                                                                 | **Conference** | **Keywords**          |**Paper**|**Code**|
|-------------------------------------------------------------------------------------------|----------------|-----------------------|---------|--------|
| Shepherd: Serving DNNs in the Wild                                                        | NSDI 2023      |                       | | |
| FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness               | NIPS 2022      |                       | | |


### Other Awesome Resources

* [awesome-gnn-systems](https://github.com/chwan1016/awesome-gnn-systems)
