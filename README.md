# FGSSL

>Federated Graph Semantic and Structural Learning
> 
>Wenke Huang, Guancheng Wan, Mang Ye, Bo Du

## Abstract

Federated graph learning collaboratively learns a global graph neural network with distributed graphs, where the non-independent and identically distributed property is one of the major challenge. Most relative arts focus on traditional distributed tasks like images and voices, incapable of the graph structures. This paper firstly reveals that local client distortion is brought by both node-level semantics and graph-level structure. First, for node-level semantic, we find that contrasting nodes from distinct classes is beneficial to provide a well-performing discrimination. We pull the local node towards the global node of the same class and push them away from the global node of different classes. Second, we postulate that a well-structural graph neural network possesses similarity for neighbors due to the inherent adjacency relationships. However, aligning each node with adjacent nodes hinders discrimination due to the potential class inconsistency. We transform the adjacency relationships into the similarity distribution and leverage the global model to distill the relation knowledge into the local model, which preserves the structural information and discriminability of the local model. Empirical results on three graph datasets manifest the superiority of the proposed method over counterparts.

## Citation

``` latex
@article{huangfederated,
  title={Federated Graph Semantic and Structural Learning},
  author={Huang, Wenke and Wan, Guancheng and Ye, Mang and Du, Bo},
  booktitle={IJCAI},
  year={2023}
}
```

