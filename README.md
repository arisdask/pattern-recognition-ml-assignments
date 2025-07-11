# Pattern Recognition & Machine Learning Assignment (ECE AUTH 2024-25)

> **Authors:** Aristeidis Daskalopoulos, Georgios Rousomanis.

This repository contains the assignments for the Pattern Recognition and Machine Learning course at ECE AUTH (2024-25). 
The project is implemented in Python and Jupyter Notebook, and includes code, datasets, and presentation material. 
Assignment's details are in `PR_Assignment_2024.pdf`.


## Repository Structure

- `Team63-AC.ipynb`, `Team63-D.ipynb`: Main Jupyter Notebooks for assignments (Parts A–C and D).
- `datasetTest.csv`, `datasetTV.csv`: Datasets for training and testing (Part D).
- `labels63.npy`: Numpy array of resulting labels from Part D code.
- `environment.yml`: Conda environment specification for reproducibility.
- `presentation/`: LaTeX source (`main.tex`) and compiled PDF (`presentation.pdf`) for the project presentation.
- `PR_Assignment_2024.pdf`: Assignment description.


## Setup Instructions

### 1. Prerequisites

- Python >= 3.9.12
- Anaconda

### 2. Create and Activate the Environment

Create the environment using the provided `environment.yml`:

```bash
conda env create -f environment.yml
conda activate PRenv
```

To deactivate the environment:

```bash
conda deactivate
```

### 3. Run the Notebooks

Open `Team63-AC.ipynb` or `Team63-D.ipynb` in Jupyter Notebook or VS Code and run the cells to reproduce the analysis and results.

### 4. Presentation

The `presentation/` folder contains the LaTeX source and PDF for the project presentation.


## Version Control Tips

To keep Jupyter Notebooks clean in git commits, you can use `nbstripout`:

```bash
[filter "strip-notebook-output"]
clean = "nbstripout"
```

Add this to your local `.git/config` to automatically strip output and metadata from notebooks on commit.
