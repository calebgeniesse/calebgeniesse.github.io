---
layout: default
title: 
---


# Caleb Geniesse
I'm a PhD student in the [Biophysics Program](http://med.stanford.edu/biophysics.html) at [Stanford University](https://www.stanford.edu/). My current research revolves around developing and applying machine learning and topological data analysis to study the brain's dynamical organization during ongoing cognition. More broadly, I'm interested in research at the interface of neuroscience and artificial intelligence, especially neuroscience-inspired AI.

<div class="more">
	<a href="about-me/">more about me</a>
</div>



### Selected Projects

- **[NeuMapper.](https://braindynamicslab.github.io/neumapper/)**&nbsp;A scalable Mapper algorithm for neuroimaging data analysis. The Matlab implementation was designed specifically for working with complex, high-dimensional neuroimaging data and produces a shape graph representation that can be annotated with meta-information and further examined using network science tools.

- **[Reciprocal Isomap.](https://calebgeniesse.github.io/reciprocal_isomap)**&nbsp;A reciprocal variant of Isomap for robust non-linear dimensionality reduction in Python. The `ReciprocalIsomap` transformer was inspired by scikit-learn's implementation of Isomap, but the reciprocal variant enforces shared connectivity in the underlying *k*-nearest neighbors graph (i.e., two points are only considered neighbors if each is a neighbor of the other).

- **[Landmark Cover.](https://calebgeniesse.github.io/landmark_cover)**&nbsp;A Python implementation of [NeuMapper](https://braindynamicslab.github.io/neumapper/)'s landmark-based cover. The `LandmarkCover` transformer was designed for use with [KeplerMapper](https://kepler-mapper.scikit-tda.org/en/latest/), but rather than dividing an *extrinsic* space (e.g., low-dimensional projection) into overlapping hypercubes, the landmark-based approach directly partitions data points into overlapping subsets based on their *intrinsic* distances from pre-selected landmark points.

- **[DyNeuSR.](https://braindynamicslab.github.io/dyneusr/)**&nbsp;A Python visualization library for topological representations of neuroimaging data. The package combines visual web components with a high-level Python interface for interacting with, manipulating, and visualizing topological graph representations of functional brain activity.



<div class="more">
	<a href="projects/">more projects</a>
</div>



### Selected Publications

- **C. Geniesse**\*, S. Chowdhury\*, M. Saggar. **[NeuMapper: A Scalable Computational Framework for Multiscale Exploration of the Brain's Dynamical Organization](https://doi.org/10.1162/netn_a_00229).** *Network Neuroscience*, 2022. [[code](https://braindynamicslab.github.io/neumapper)] (*\*equal contribution*) 

- H. Xie, R. Beaty, S. Jahanikia, **C. Geniesse**, N. Sonalkar, M. Saggar. **[Spontaneous and Deliberate Modes of Creativity: Multitask Eigen-Connectivity Analysis Captures Latent Cognitive Modes During Creative Thinking](https://doi.org/10.1016/j.neuroimage.2021.118531).** *NeuroImage*, 2021.

- N. Sonalkar, S. Jahanikia, H. Xie, **C. Geniesse**, R. Ayub, R. Beaty, M. Saggar. **[Mining the Role of Design Reflection and Associated Brain Dynamics in Creativity](https://doi.org/10.1007/978-3-030-28960-7_10).** *Design Thinking Research. Understanding Innovation. Springer, Cham*, 2020.

- **C. Geniesse**, O. Sporns, G. Petri, M. Saggar. **[Generating Dynamical Neuroimaging Spatiotemporal Representations (DyNeuSR) Using Topological Data Analysis](https://doi.org/10.1162/netn_a_00093).** *Network Neuroscience*, 2019. [[code](https://braindynamicslab.github.io/dyneusr)] [[demos](https://braindynamicslab.github.io/dyneusr/demo/)]



<div class="more">
	<a href="publications/">more publications</a>
</div>
