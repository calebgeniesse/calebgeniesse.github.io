---
layout: page
title: Projects
---

Below are some of the projects I have developed throughout my research. Most of these (and more) can also be found on my [GitHub](https://github.com/calebgeniesse).

- **[NeuMapper.](https://braindynamicslab.github.io/neumapper/)**&nbsp;A scalable Mapper algorithm for neuroimaging data analysis. The Matlab implementation was designed specifically for working with complex, high-dimensional neuroimaging data and produces a shape graph representation that can be annotated with meta-information and further examined using network science tools.

- **[Reciprocal Isomap.](https://github.com/calebgeniesse/reciprocal_isomap)**&nbsp;A reciprocal variant of Isomap for robust non-linear dimensionality reduction in Python. `ReciprocalIsomap` was inspired by scikit-learn's implementation of Isomap, but the reciprocal variant enforces shared connectivity in the underlying *k*-nearest neighbors graph (i.e., two points are only considered neighbors if each is a neighbor of the other).

- **[Landmark Cover.](https://github.com/calebgeniesse/landmark_cover)**&nbsp;A landmark-based cover for Mapper. `LandmarkCover` was designed for use with [KeplerMapper](https://kepler-mapper.scikit-tda.org/en/latest/), but rather than dividing an *extrinsic* space (e.g., a low-dimensional projection) into overlapping hypercubes, the landmark-based approach directly partitions data points into overlapping subsets based on their *intrinsic* distances from pre-selected landmark points.

- **[Partial Cluster.](https://github.com/calebgeniesse/pcluster)**&nbsp;A partial clustering wrapper for Mapper. `PartialCluster` wraps around a user-specified clustering algorithm to enable globally-aware partial clustering. By pre-clustering an entire dataset, *local* subsets of the data can be partially clustered based on their *global* cluster assignments.

- **[DyNeuSR.](https://braindynamicslab.github.io/dyneusr/)**&nbsp;A Python visualization library for topological representations of neuroimaging data. The package combines visual web components with a high-level Python interface for interacting with, manipulating, and visualizing topological graph representations of functional brain activity.

- **[DyNeuSR Fire.](https://braindynamicslab.github.io/dyneusr-fire/)**&nbsp;A command line interface for [DyNeuSR](https://braindynamicslab.github.io/dyneusr/) based on the [Python Fire](https://github.com/google/python-fire) library. The package wraps [KeplerMapper](https://kepler-mapper.scikit-tda.org/en/latest/) and [DyNeuSR](https://braindynamicslab.github.io/dyneusr/) into a single pipeline and automatically generates a simple command line interface that allows users to customize this pipeline. 
