## A Curated list of papers related to efficient graph machine learning


### Model Level (Most papers come from ICML,NIPS,ICLR)
| **Title**                                                                                 | **Conference** | **Keywords**          |
|-------------------------------------------------------------------------------------------|----------------|-----------------------|
| Efficient Learning of Linear Graph Neural Networks via Node Subsampling                   | NIPS 2023      | Sampling              |
| Communication-Free Distributed GNN Training with Vertex Cut                               | Arxiv 2023     | Distributed           |
| DSpar: An Embarrassingly Simple Strategy for Efficient GNN training and inference via Degree-based Sparsification | TMLR 2023 | Data-driven, Graph Condensation|
| Learning Large Graph Property Prediction via Graph Segment Training                       | Arxiv 2023     | Graph Transformer     |
| LazyGNN: Large-Scale Graph Neural Networks via Lazy Propagation                           | ICML 2023      |                       |
| Graph Ladling: Shockingly Simple Parallel GNN Training without Intermediate Communication | ICML 2023      | Distributed           |
| GOAT: A Global Transformer on Large-scale Graphs                                          | ICML 2023      | Graph Transformer     |
| Do Not Train It: A Linear Neural Architecture Search of Graph Neural Networks             | ICML 2023      | NAS                   |
| MLPInit: Embarrassingly Simple GNN Training Acceleration with MLP Initialization          | ICLR 2023      | GNN as MLP            |
| GraphFM: Improving Large-Scale GNN Training via Feature Momentum                          | NIPS 2022      |                       |
| Graph Condensation for Graph Neural Networks                                              | ICLR 2022      | Data-driven, Graph Condensation |
|Graph-less Neural Networks: Teaching Old MLPs New Tricks via Distillation                  | ICLR 2022      | GNN as MLP            |
| GNNAutoScale: Scalable and Expressive Graph Neural Networks via Historical Embeddings      | ICML 2021      | Large Graph, Sampling |
| VQ-GNN: A Universal Framework to Scale up Graph Neural Networks using Vector Quantization | NIPS 2021      | Quantization          |
| Sketch-GNN: Scalable Graph Neural Networks with Sublinear Training Complexity             | NIPS 2021      |                       |





### ML/Sys-codesign level (Most papers come from SIGMOD, VLDB, OSDI, ICDE, ...)

| **Title**                                                                                 | **Conference** | **Keywords**          |
|-------------------------------------------------------------------------------------------|----------------|-----------------------|
| DSP: Efficient GNN Training with Multiple GPUs                                            | PPoPP 2023     |                       |
| PiPAD: Pipelined and Parallel Dynamic GNN Training on GPUs                                | PPoPP 2023     |                       |
| Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective| MLSYS 2022   | Kernel                |
| Sequential Aggregation and Rematerialization: Distributed Full-batch Training of Graph Neural Networks on Large Graphs | MLSYS 2022 | Distributed, full-batch | 
| Accelerating Training and Inference of Graph Neural Networks with Fast Sampling and Pipelining | MLSYS 2022 |                      | 
| Graphiler: Optimizing Graph Neural Networks with Message Passing Data Flow Graph          | MLSYS 2022     |                       | 
| BNS-GCN: Efficient Full-Graph Training of Graph Convolutional Networks with Partition-Parallelism and Random Boundary Node Sampling | MLSYS 2022 | |
| Algorithm and System Co-design for Efficient Subgraph-based Graph Representation Learning | VLDB 2022      |                       |
| Accurate and Scalable Graph Neural Networks for Billion-Scale Graphs                      | ICDE 2022      |                       |


### Non-graph but interesting & important work
| **Title**                                                                                 | **Conference** | **Keywords**          |
|-------------------------------------------------------------------------------------------|----------------|-----------------------|
| Shepherd: Serving DNNs in the Wild                                                        | NSDI 2023      |                       |
| FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness               | NIPS 2022      |                       |


### Other Awesome Resources

* [awesome-gnn-systems](https://github.com/chwan1016/awesome-gnn-systems)
