# ProteinsPlus Examples

ProteinsPlus provides a wide-range of tools for structure-based drug discovery and structural bioinformatics. This repository provides examples on how use the [proteins.plus](https://proteins.plus) API programmatically.

This project is developed at the Universitaet Hamburg, ZBH - Center for Bioinformatics
by the group of Matthias Rarey.

## Colab notebooks

Interactive examples can be found for:

* [Protoss: Hydrogen prediction](notebooks/Protoss_example.ipynb)
* [DoGSite: Binding site prediction](notebooks/DoGSite_example.ipynb)
* [PoseView: 2D images of protein-ligand interactions](notebooks/PoseView_example.ipynb)
* [SIENA: Binding site similarity search](notebooks/SIENA_example.ipynb)
* [EDIAscorer: Assessing electron density fit of individual atoms](notebooks/EDIAscorer_example.ipynb)
* [Molecule handler: Working with proteins and ligands](notebooks/MoleculeHandler_example.ipynb)
* [StructureProfiler: Structure quality analysis](notebooks/StructureProfiler_example.ipynb)

## Jupyter notebooks

All notebooks can alternatively be run locally using jupyter notebook. We suggest using [conda](https://docs.conda.io/en/latest/miniconda.html) to manage the dependencies. You can generate a conda environment with all necessary dependencies using the following command:

```bash
conda create -n examples -c conda-forge -c anaconda python=3.7 nglview biopython jupyter requests rdkit
conda activate examples
```

Some notebook cells are colab specific. These may fail in jupyter notebook, but will not influence the rest of the notebook.

