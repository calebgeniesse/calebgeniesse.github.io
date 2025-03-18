---
layout: default
title: 
---


# Caleb Geniesse

I am a senior ML scientist at [Diadia Health](https://diadiahealth.com).

Before this, I was a postdoc in the [Machine Learning & Analytics Group](http://dav.lbl.gov/) at [Lawrence Berkeley National Laboratory](https://www.lbl.gov/), doing scientific ML (e.g., physics-informed neural networks) and interpretability (e.g., developing new ways to visualize loss landscapes and characterize learning).

I did my PhD in [Biophysics](http://med.stanford.edu/biophysics.html) at [Stanford](https://www.stanford.edu/), 
where I developed new computational methods (using ML and topological data analysis) to study the brain's dynamical organization during ongoing cognition.

<div class="more">
	<a href="about-me/">more about me</a>
</div>



### Selected Publications

- M. Sakarvadia, A. Ajith, A.M. Khan, N.C. Hudson, **C. Geniesse**, K. Chard, Y. Yang, I. Foster, M. Mahoney. **[Mitigating Memorization in Language Models](https://arxiv.org/abs/2410.02159).** *Spotlight at the International Conference on Learning Representations (ICLR)*, 2025. [[pdf](https://arxiv.org/pdf/2410.02159)] [[blog](https://mansisak.com/memorization/)]

- T. Baldi, J. Campos, O. Weng, **C. Geniesse**, N. Tran, R. Kastner, A. Biondi. **[Loss Landscape Analysis for Reliable Quantized ML Models for Scientific Sensing](https://arxiv.org/abs/2502.08355).** *arXiv*, 2025. [[pdf](https://arxiv.org/pdf/2502.08355)]

- O. Weng, M. Andronic, D. Zuberi, J. Chen, **C. Geniesse**, G.A. Constantinides, N. Tran, N. Fraser, J. Duarte, R. Kastner. **[Greater than the Sum of its LUTs: Scaling Up LUT-based Neural Networks with AmigoLUT](https://doi.org/10.1145/3706628.3708874).** *International Symposium on Field Programmable Gate Arrays (FPGA)*, 2025. [[pdf](https://kastner.ucsd.edu/wp-content/uploads/2025/01/admin/fpga25-amigoLUT.pdf)]

- **C. Geniesse**\*, J. Chen\*, T. Xie\*, G. Shi, Y. Yang, D. Morozov, T. Perciano, M. Mahoney, R. Maciejewski, G.H. Weber. **[Visualizing Loss Functions as Topological Landscape Profiles](https://arxiv.org/abs/2411.12136).** *NeurIPS Workshop on Symmetry and Geometry in Neural Representations (NeurReps) Proceedings Track*, 2024. [[pdf]((https://arxiv.org/pdf/2411.12136))] (*equal contribution)

- T. Xie\*, **C. Geniesse**\*, J. Chen\*, Y. Yang, D. Morozov, M. Mahoney, R. Maciejewski, G.H. Weber. **[Evaluating Loss Landscapes from a Topology Perspective](https://arxiv.org/abs/2411.09807).** *NeurIPS Workshop on Scientific Methods for Understanding Deep Learning (SciForDL)*, 2024. [[pdf](https://arxiv.org/pdf/2411.09807)] (*equal contribution)

- T. Xie\*, J. Chen\*, Y. Yang\*, **C. Geniesse**\*, G. Shi, A. Chaudhari, J.K. Cava, M.W. Mahoney, T. Perciano, G.H. Weber, R. Maciejewski. **[LossLens: Diagnostics for Machine Learning Through Loss Landscape Visual Analytics](https://ieeexplore.ieee.org/abstract/document/10804049/).** *IEEE Computer Graphics and Applications*, 2024. [[pdf](https://arxiv.org/pdf/2412.13321)] (*\*equal contribution*) 

- S.K.L. Quah, B. Jo, **C. Geniesse**, L.Q. Uddin, J.A. Mumford, D.M. Barch, D.A. Fair, I.H. Gotlib, R.A. Poldrack, M. Saggar. **[A Data-Driven Latent Variable Approach to Validating the Research Domain Criteria Framework](https://doi.org/10.1038/s41467-025-55831-z).** *Nature Communications*, 2024.

- **C. Geniesse**\*, S. Chowdhury\*, M. Saggar. **[NeuMapper: A Scalable Computational Framework for Multiscale Exploration of the Brain's Dynamical Organization](https://doi.org/10.1162/netn_a_00229).** *Network Neuroscience*, 2022. [[code](https://braindynamicslab.github.io/neumapper)] (*\*equal contribution*) 

- **C. Geniesse**, O. Sporns, G. Petri, M. Saggar. **[Generating Dynamical Neuroimaging Spatiotemporal Representations (DyNeuSR) Using Topological Data Analysis](https://doi.org/10.1162/netn_a_00093).** *Network Neuroscience*, 2019. [[code](https://braindynamicslab.github.io/dyneusr)] [[demos](https://braindynamicslab.github.io/dyneusr/demo/)]

- Z. Wu, B. Ramsundar, E. Feinberg, J. Gomes, **C. Geniesse**, A. Pappu, K. Leswing, V. Pande. **[MoleculeNet: A Benchmark for Molecular Machine Learning](https://doi.org/10.1039/C7SC02664A).** *Chemical Science*, 2018.

<div class="more">
	<a href="publications/">more publications</a>
</div>



### Selected Projects

- **[NeuMapper.](https://braindynamicslab.github.io/neumapper/)**&nbsp;A scalable Mapper algorithm for neuroimaging data analysis. The Matlab implementation was designed specifically for working with complex, high-dimensional neuroimaging data and produces a shape graph representation that can be annotated with meta-information and further examined using network science tools.

- **[Reciprocal Isomap.](https://calebgeniesse.github.io/reciprocal_isomap)**&nbsp;A reciprocal variant of Isomap for robust non-linear dimensionality reduction in Python. The `ReciprocalIsomap` transformer was inspired by scikit-learn's implementation of Isomap, but the reciprocal variant enforces shared connectivity in the underlying *k*-nearest neighbors graph (i.e., two points are only considered neighbors if each is a neighbor of the other).

- **[Landmark Cover.](https://calebgeniesse.github.io/landmark_cover)**&nbsp;A Python implementation of [NeuMapper](https://braindynamicslab.github.io/neumapper/)'s landmark-based cover. The `LandmarkCover` transformer was designed for use with [KeplerMapper](https://kepler-mapper.scikit-tda.org/en/latest/), but rather than dividing an *extrinsic* space (e.g., low-dimensional projection) into overlapping hypercubes, the landmark-based approach directly partitions data points into overlapping subsets based on their *intrinsic* distances from pre-selected landmark points.

- **[DyNeuSR.](https://braindynamicslab.github.io/dyneusr/)**&nbsp;A Python visualization library for topological representations of neuroimaging data. The package combines visual web components with a high-level Python interface for interacting with, manipulating, and visualizing topological graph representations of functional brain activity.

<div class="more">
	<a href="projects/">more projects</a>
</div>
