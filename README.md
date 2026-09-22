# Machine Learning Study Notes

This repository contains practical Python, NumPy, Pandas, data analysis, and
introductory machine-learning study material collected as notebooks, datasets,
assignments, and reference PDFs.

## Repository layout

```text
.
├── notebooks/
│   ├── python/                         # Python class notebooks
│   ├── numpy/                          # NumPy practice notebooks
│   ├── pandas/                         # Pandas/data-analysis notebooks
│   ├── machine-learning.ipynb          # Machine-learning exercises
│   └── machine-learning-lab.ipynb      # ML lab exercises
└── classes/
    └── Introduction_To_Machine_Learning/
        ├── Notes/                      # Lecture notes and note PDFs
        ├── Lab Class/                  # Guided lab notebooks and datasets
        ├── Assignment/                # Assignment notebooks, solutions, and PDFs
        ├── Data/                       # CSV datasets used by the notebooks
        └── Self Study/                 # Additional study material
```

## Topics covered

- Python fundamentals, strings, dictionaries, and data processing
- NumPy arrays, indexing, slicing, broadcasting, and vectorized operations
- Pandas DataFrames, filtering, grouping, cleaning, and visualization
- Matplotlib and Seaborn plotting
- Data preprocessing and exploratory data analysis
- K-nearest neighbors, linear regression, and logistic regression
- Practice assignments using Titanic, penguins, MPG, placement, and other datasets

## Getting started

Create an environment with Python 3.10 or newer, then install the notebook
dependencies:

```bash
python -m venv .venv
source .venv/bin/activate       # Windows: .venv\Scripts\activate
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn
jupyter notebook
```

For notebooks under `classes/Introduction_To_Machine_Learning`, open or run
them with that directory as the working directory when they load files from
`Data/`:

```bash
cd classes/Introduction_To_Machine_Learning
jupyter notebook
```

The local environments, notebook checkpoints, OS metadata, and nested Git
metadata are intentionally excluded from version control.
