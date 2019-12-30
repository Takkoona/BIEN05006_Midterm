# BIEN05006_Midterm
Source code for BIEN05006 midterm. Codes are run in [jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html).

## Dependency
1. `python >= 3.5`: `jupyter`, `biopython`
2. `R >= 3.6`: [`IRkernel`](https://irkernel.github.io/installation/), `ape`, `jsonlite`
3. [`PyMOL`](https://pymolwiki.org/index.php/Category:Installation)

## How to run
First `cd` into the project directory and start jupyter notebook by running `jupyter notebook`. This will open up the browser and send you to the jupyter file explorer.

### Translate mRNA
Open `mRNA_translation.ipynb` from jupyter file explorer and use `Ctrl` + `Shift` to run the cells.

### Visualize phylogeny
Open `phylogeny_plot.ipynb` from jupyter file explorer and use `Ctrl` + `Shift` to run the cells. The plots will be saved in `Figures` folder. **Make sure the kernel is R**.

### Visualize 3D structure
Open PyMOL and `cd` into the project directory. Run `@HSP90AA1_structure.pml` inside the PyMOL console to view the 3D structure. The plot will be saved in `Figures` folder.
