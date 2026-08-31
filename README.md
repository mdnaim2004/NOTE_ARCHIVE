# Mechine-Learning

A curated collection of introductory Python examples, Jupyter notebooks, and plotting exercises used while learning machine learning fundamentals.

This repository contains beginner-friendly code and notebooks that demonstrate core Python concepts, basic data visualization with Matplotlib and Seaborn, and small exploratory analyses.

**Contents**

- Basic Python/: beginner Python scripts and Day 1/Day 2 notebooks. See [Basic Python/hello.py](Basic%20Python/hello.py) and [Basic Python/basic_python_code_Day_1.ipynb](Basic%20Python/basic_python_code_Day_1.ipynb) for examples.
- matplotlib/: example notebooks showing plotting with Matplotlib such as [matplotlib/introduction_matplotlib.ipynb](matplotlib/intro_matplotlib.ipynb).
- seabron/: example notebook demonstrating Seaborn visualizations ([seabron/seaborn.ipynb](seabron/seaborn.ipynb)).

Note: Folder names preserve the original spelling used in this workspace.

**Prerequisites**

- Python 3.8 or newer
- pip
- Jupyter (for notebooks)

Recommended Python packages (installable with pip):

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyter numpy pandas matplotlib seaborn scikit-learn notebook
```

If you prefer to install only what's needed for a particular notebook or script, inspect that file for imports and install packages accordingly.

**Quick Start**

- Run Jupyter Notebook in the repository root and open any notebook from the browser UI:

```bash
jupyter notebook
```

- Run a Python script from the command line, for example:

```bash
python "Basic Python/hello.py"
```

**Repository structure (high level)**

- Basic Python/: basic scripts and teaching notebooks (strings, I/O, conditionals, small exercises).
- matplotlib/: Matplotlib-focused notebooks and examples.
- seabron/: Seaborn examples for statistical plotting.

Explore these folders to find hands-on examples you can run and modify.

**How to use this repo**

1. Create and activate a virtual environment.
2. Install the packages listed above.
3. Start `jupyter notebook` to open and run notebooks interactively, or run `.py` files directly with Python.

**Contributing**

- Small fixes, spelling corrections, improved examples, or additional notebooks are welcome.
- Open an issue to discuss significant changes before submitting large pulls.

**License**

This repository is provided for learning purposes. If you want a license added, tell me which one (for example, MIT) and I will add a `LICENSE` file.

**Contact**

If you want help expanding this repo (adding a requirements file, CI, or a tutorial), tell me what you'd like next.
