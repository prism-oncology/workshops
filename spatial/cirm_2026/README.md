# Spatial omics practical workshop

This workshops introduces several spatial omics tools: (i) [Sopa](https://github.com/prism-oncology/sopa) for data preprocessing, (ii) [scConcept](https://github.com/theislab/scConcept) for cell-type annotation, (iii) [Novae](https://github.com/prism-oncology/novae) for spatial domains annotation and (iv) Graph Neural Networks.

## Notebooks

1. [`1_preprocessing.ipynb`](https://github.com/prism-oncology/workshops/blob/main/spatial/cirm_2026/1_preprocessing.ipynb) introduces Sopa and SpatialData on a light synthetic dataset. It's a quick tutorial that is fully guided: no code has to be written.
2. [`2_postprocessing.ipynb`](https://github.com/prism-oncology/workshops/blob/main/spatial/cirm_2026/2_postprocessing.ipynb) acts as you already pre-processed your data and now work only on the `AnnData` object. It uses scConcept and Novae for postprocessing of real data (embeddings were pre-computed for conveniency). Writing code is required to walk through this notebook.
3. [`3_GNN.ipynb`](https://github.com/prism-oncology/workshops/blob/main/spatial/cirm_2026/2_GNN.ipynb) also works on the AnnData object, and introduces Graph Neural Networks on the same real colon cancer slide (the Novae spatial domains were pre-computed and used as labels). It goes from building a spatial graph to predicting the spatial domains, and to finding niches without any labels. Writing code is required to walk through this notebook.

## Requirements

Both tutorials are independant, and their dependencies are listed at the beginning of the notebook.

All dependencies can be installed on all OS, for any **Python version `>=3.11`**.

> [!TIP]
> We recommend having one environment per notebook.

## Event details

This workshop was given by Hakim Benkirane and Quentin Blampey at the *'Mathematical Foundations for Spatial Omics in oncology'* summer school (20-24 July, 2026).
