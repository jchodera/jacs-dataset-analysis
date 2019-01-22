# Re-analysis of the Schrödinger JACS dataset

This notebook is an analysis of the errors in relative free energy calculations from the Schrödinger JACS dataset:
> Wang, L., Wu, Y., Deng, Y., Kim, B., Pierce, L., Krilov, G., ... & Romero, D. L. (2015). Accurate and reliable prediction of relative ligand binding potency in prospective drug discovery by way of a modern free-energy calculation protocol and force field. Journal of the American Chemical Society, 137(7), 2695-2703.

http://doi.org/10.1021/ja512751q

## Manifest
* `notebook.ipynb` - Jupyter notebook
* `environment.yml` - conda environment
* `ja512751q_si_003.xlsx` - SI retrieved from
* `LICENSE` - copy of the MIT License this work is licensed under
* `jacs-analysis.pdf` - figure produced by the analysis

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
