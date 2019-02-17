# Evaluating performance on the Schrödinger JACS dataset

This notebook is an analysis of the errors in relative free energy calculations from the Schrödinger JACS dataset:
> Wang, L., Wu, Y., Deng, Y., Kim, B., Pierce, L., Krilov, G., ... & Romero, D. L. (2015). Accurate and reliable prediction of relative ligand binding potency in prospective drug discovery by way of a modern free-energy calculation protocol and force field. Journal of the American Chemical Society, 137(7), 2695-2703.

http://doi.org/10.1021/ja512751q

## Manifest
* `AMBER TI chemRxiv analysis - mapped edge DDGs.ipynb` - analysis of mapped edge DDG statistics
* `AMBER TI chemRxiv analysis - DG and allpairs DDG.ipynb` - analysis of DG and all-pairs DDG statistics
* `environment.yml` - conda environment
* `LICENSE` - copy of the MIT License this work is licensed under
* `jacs-analysis.pdf` - figure produced by the analysis
* `fep-plus` - SI retrieved from [Schrödinger publication](http://doi.org/10.1021/ja512751q)
* `amber-ti` - AMBER TI results reported on [chemRxiv](https://chemrxiv.org/articles/Validation_of_AMBER_GAFF_for_Relative_Free_Energy_Calculations/7653434)

## To use the notebook

Create a conda environment and activate it
```bash
conda env create -f environment.yml -n jacs
source activate jacs
```
Launch the notebook
```bash
jupyter notebook notebook.ipynb
```
