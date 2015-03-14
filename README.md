FuseNet
=======

Markov networks are undirected graphical models that are widely used to infer relations between genes from experimental data. Their state-of-the-art inference procedures assume the data arise from a Gaussian distribution. High-throughput omics data, such as that from next generation sequencing, often violates this assumption. Furthermore, when collected data arise from multiple related but otherwise nonidentical distributions, their underlying networks are likely to have common features. New principled statistical approaches are needed that can deal with different data distributions and jointly consider collections of data sets. 

FuseNet is a Markov network formulation that infers networks from a collection of nonidentically distributed data sets. FuseNet is computationally efficient and general: given any number of distributions from an exponential family, FuseNet represents model parameters through shared latent factors that define neighborhoods of network nodes. Network inference methods for non-Gaussian data, such as FuseNet, can help in accurate modeling of the data generated by emergent high-throughput technologies. 

This repository contains supplementary material for *Gene network inference by fusing data from diverse distributions* by Marinka Zitnik and Blaz Zupan. 

Citing
------

    @article{Zitnik2015,
      title     = {Gene network inference by fusing data from diverse distributions},
      author    = {{\v{Z}}itnik, Marinka and Zupan, Bla{\v{z}}},
      journal   = {},
      volume    = {},
      number    = {},
      pages     = {},
      year      = {2015},
      publisher = {}
    }
