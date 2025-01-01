## Overview

This is the project assignment for the course Pattern Recognition and Machine Learning of ECE AUTH the year
2024-25, built with `Python` and `Jupyter Notebook`

## Requirements

Before running the project, make sure you have the following installed:

- `Python 3.9.12` 
- `Anaconda` (Recommended for Python environments)

## Installation

### 1. Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone git@github.com:georrous6/Pattern-Recognition.git
```

### 2. Set Up Anaconda Environment

Navigate to the directory of the repository
```bash
cd Pattern-Recognition
```

Create a new Anaconda environment with all the installed requirements along with the appropriate Python version
```bash
conda env create -f environment.yml
```

Activate the environment
```bash
conda activate PRenv
```

When you're done working in the environment, you can deactivate it by running
```bash
conda deactivate
```

### 3. Version Control with Jupyter Notebook

To clear Jupyter Notebook's output and metadata when using git commit, 
add this to your local `.git/config`
```bash
[filter "strip-notebook-output"]
clean = "nbstripout"
```
