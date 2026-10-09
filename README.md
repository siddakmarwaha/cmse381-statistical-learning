# CMSE 381 — Statistical Learning Coursework

![Python](https://img.shields.io/badge/python-3.9%2B-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Homework and projects following *An Introduction to Statistical Learning*: linear and logistic regression, cross-validation and the bootstrap, subset selection, ridge/lasso, polynomial and spline models, tree ensembles and support vector machines.

**Course:** CMSE 381 — Fundamentals of Data Science Methods  
**Term:** Fall 2024  
**Institution:** Michigan State University

## Highlights

- **Project:** regression on the Real Estate Valuation dataset (linear, K-fold CV, ridge) and multi-class classification of Poker Hands (random forest).
- **Honors project:** star-type classification and temperature regression on a Kaggle stellar dataset, with feature encoding and model interpretation.
- Eight homework sets covering the ISLR exercises in Python (statsmodels, scikit-learn).

## Contents

- [`projects/real_estate_and_poker_hand.ipynb`](projects/real_estate_and_poker_hand.ipynb) — course project
- [`projects/honors_star_classification.ipynb`](projects/honors_star_classification.ipynb) — honors project

## Notebook Index

### Homework

- [`hw01.ipynb`](homework/hw01.ipynb) — Siddak Marwaha
- [`hw02.ipynb`](homework/hw02.ipynb) — Siddak Marwaha
- [`hw03.ipynb`](homework/hw03.ipynb) — Siddak Marwaha
- [`hw04.ipynb`](homework/hw04.ipynb) — Siddak Marwaha
- [`hw05.ipynb`](homework/hw05.ipynb) — Siddak Marwaha
- [`hw06.ipynb`](homework/hw06.ipynb) — Siddak Marwaha
- [`hw07.ipynb`](homework/hw07.ipynb) — Siddak Marwaha
- [`hw08.ipynb`](homework/hw08.ipynb) — Siddak Marwaha

## Repository Structure

```text
cmse381-statistical-learning/
├── homework/
│   ├── hw01.ipynb
│   ├── hw02.ipynb
│   ├── hw03.ipynb
│   ├── hw04.ipynb
│   ├── hw05.ipynb
│   ├── hw06.ipynb
│   ├── hw07.ipynb
│   └── hw08.ipynb
├── projects/
│   ├── honors_star_classification.ipynb
│   └── real_estate_and_poker_hand.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

## Tech Stack

Python, scikit-learn, statsmodels, pandas, NumPy, seaborn

## Getting Started

```bash
git clone https://github.com/siddakmarwaha/cmse381-statistical-learning.git
cd cmse381-statistical-learning
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## Data

Datasets are the standard ISLR files (`Auto.csv`, `College.csv`, `Default.csv`, `OJ.csv`) and public UCI/Kaggle datasets referenced in each notebook; they are not committed.

> **Academic integrity:** This repository contains my own submitted work for a university course and is shared as a portfolio sample. Assignment prompts and starter code belong to the course instructors. Current students should not copy this work.

## Author

**Siddak Marwaha**

## License

Code in this repository is released under the [MIT License](LICENSE). Course-provided prompts and materials remain the property of their authors.
