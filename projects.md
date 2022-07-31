---
layout: page
title: Projects
---

Below are some of the projects I have developed throughout my research. Most of these (and more) can also be found on my [GitHub](https://github.com/calebgeniesse).

- **[NeuMapper](https://braindynamicslab.github.io/neumapper/).**&nbsp;A scalable Mapper algorithm for neuroimaging data analysis. The Matlab implementation was designed specifically for working with complex, high-dimensional neuroimaging data and produces a shape graph representation that can be annotated with meta-information and further examined using network science tools.

- **[`ReciprocalIsomap`](https://github.com/calebgeniesse/reciprocal_isomap).**&nbsp;A reciprocal variant of Isomap for robust non-linear dimensionality reduction in Python. `ReciprocalIsomap` was inspired by scikit-learn's implementation of `Isomap`, but the reciprocal variant requires shared connectivity in the underlying *k*-nearest neighbors graph (i.e., two points are only considered neighbors if each is a neighbor of the other).

- **[`LandmarkCover`](https://github.com/calebgeniesse/landmark_cover).**&nbsp;A landmark-based cover for Mapper. `LandmarkCover` was designed to be used with [KeplerMapper](https://kepler-mapper.scikit-tda.org/en/latest/), but it departs from the existing `CubicalCover` by introducing an additional landmark selection during the initial fit, and then partitioning data points into cover elements based on their distances from the selected landmarks during the transform step.
 
- **[`PartialCluster`](https://github.com/calebgeniesse/pcluster).**&nbsp;A partial clustering wrapper for Mapper. `PartialCluster` wraps around a user-specified clustering algorithm to enable "globally-aware" partial clustering. By pre-fitting the wrapper to an entire dataset, "global" clustering assignments can then be used to guide the partial clustering of "local" subsets of the data. 

<!-- 
- **[`reciprocal_isomap`.](https://github.com/calebgeniesse/reciprocal_isomap)**&nbsp;A reciprocal variant of Isomap for robust non-linear dimensionality reduction in Python. `ReciprocalIsomap` was inspired by scikit-learn's implementation of `Isomap`, but the reicprocal variant improves the original algorithm (e.g., robustness to outliers) by requiring that neighbors in the underlying *k* nearest neighbors graph must be reciprocal (i.e., two points are only considered neighbors if each is a neighbor of the other).

- **[`landmark_cover`.](https://github.com/calebgeniesse/landmark_cover)**&nbsp;A landmark-based cover for Mapper. `LandmarkCover` derives from [KeplerMapper's](https://kepler-mapper.scikit-tda.org/en/latest/) `Cover` class, but departs from the existing `CubicalCover` by adding an additional landmark selection step during the fitting process. Using these landmarks, the `LandmarkCover` partitions the input data points based on distances to each of the landmark points.

- **[`pcluster`.](https://github.com/calebgeniesse/pcluster)**&nbsp;A partial clustering wrapper for Mapper. The package introduces a `PartialCluster` transformer that wraps around a user-specified clustering algorithm to enable "globally-aware" partial clustering. By pre-fitting the wrapper to an entire dataset, "global" clustering assignments can be used to guide the partial clustering of "local" subsets of the data. To predict the cluster labels of a subset of data points, the pre-fit cluster labels can be indexed based on user-defined distance metric.  -->

- **[DyNeuSR](https://braindynamicslab.github.io/dyneusr/).**&nbsp;A Python visualization library for topological representations of neuroimaging data. The package combines visual web components with a high-level Python interface for interacting with, manipulating, and visualizing topological graph representations of functional brain activity.

- **[DyNeuSR Fire](https://braindynamicslab.github.io/dyneusr-fire/).**&nbsp;A command line interface for [DyNeuSR](https://braindynamicslab.github.io/dyneusr/) based on the [Python Fire](https://github.com/google/python-fire) library. The package wraps [KeplerMapper](https://kepler-mapper.scikit-tda.org/en/latest/) and [DyNeuSR](https://braindynamicslab.github.io/dyneusr/) into a single pipeline and automatically generates a simple command line interface that allows users to customize this pipeline. 
