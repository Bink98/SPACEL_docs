# SPACEL: characterizing spatial transcriptome architectures by deep-learning

% ![Overview](docs/figures/figure1.png "Overview")
SPACEL (**SP**atial **A**rchitecture **C**haracterization by d**E**ep **L**earning) is a Python package of deep-learning-based methods for ST data analysis. SPACEL consists of three modules: 

- Spoint embedded a multiple-layer perceptron with a probabilistic model to deconvolute cell type composition for each spot on single ST slice.
- Splane employs a graph convolutional network approach and an adversarial learning algorithm to identify uniform spatial domains that are transcriptomically and spatially coherent across multiple ST slices.
- Scube automatically transforms the spatial coordinate systems of consecutive slices and stacks them together to construct a three-dimensional (3D) alignment of the tissue.

## Content
* {doc}`Installation <installation>`
* {doc}`Tutorials <tutorials>`
%    * [Spoint tutorial: Deconvolution of cell types distribution of spatial transcriptomics](tutorial/deconvolution_of_cell_types_distribution.ipynb)
%    * [Splane tutorial: Identify uniform spatial domain in multiple slices](tutorial/identification_of_uniform_spatial_domain.ipynb)
%    * [Scube tutorial: Alignment of multiple spatial transcriptomic slices](tutorial/alignment_of_multiple_slices.ipynb)
%    * [Scube tutorial: 3D expression modeling with gaussian process regression](tutorial/3D_expression_modeling.ipynb)
* {doc}`API <api>`

```{toctree}
:hidden: true
:maxdepth: 1

installation
tutorials
api
```
