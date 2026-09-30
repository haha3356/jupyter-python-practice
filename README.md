# Linear Algebra Practice with Python

This repository contains worked linear algebra exercises presented as Jupyter notebooks. Each exercise is organized with a consistent question-and-solution structure and uses Python where computation, verification, or visualization is helpful.

## Contents

| Notebook | Topics |
| --- | --- |
| [`chapter1.ipynb`](chapter1.ipynb) | Linear systems, row reduction, vector equations, matrix equations, linear independence, linear transformations, and linear models |
| [`chapter2.ipynb`](chapter2.ipynb) | Matrix operations, matrix inverses, the Invertible Matrix Theorem, partitioned matrices, matrix factorizations, conditioning, and applications |
| [`chapter3.ipynb`](chapter3.ipynb) | Determinants, determinant properties, Cramer's rule, volume, and linear transformations |

The notebooks cover selected exercises from the following sections:

- Chapter 1: Sections 1.2, 1.3, 1.4, 1.7, 1.8, 1.9, and 1.10
- Chapter 2: Sections 2.1, 2.2, 2.3, 2.4, 2.5, and 2.7
- Chapter 3: Sections 3.1, 3.2, and 3.3

## Tools Used

- [Jupyter](https://jupyter.org/) for interactive notebooks
- [NumPy](https://numpy.org/) for numerical matrix calculations
- [SymPy](https://www.sympy.org/) for symbolic and exact calculations
- [Matplotlib](https://matplotlib.org/) for visualizations

## Getting Started

Clone the repository:

```bash
git clone https://github.com/haha3356/jupyter-python-practice.git
cd jupyter-python-practice
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
python -m pip install jupyter numpy sympy matplotlib
```

Start Jupyter Lab:

```bash
jupyter lab
```

Then open any of the chapter notebooks and run the cells from top to bottom.

## Notebook Format

Exercises use a consistent heading structure:

```text
Section 3.1 - Exercise 21
Solution
```

Code cells support the written solutions by performing calculations, checking results, and producing visualizations where appropriate.
