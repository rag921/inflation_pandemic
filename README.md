# inflation_pandemic

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

# Inflation Analysis Due to the Pandemic

## Project Description

This project analyzes the impact of the COVID-19 pandemic on inflation across different regions and sectors. The aim is to identify patterns and determine the factors contributing to inflation during and after the pandemic. The project includes data processing, exploratory data analysis (EDA), statistical modeling, and evaluation of the findings.

### Key Objectives:
- Analyze inflation trends across various countries/regions.
- Investigate the role of government policies (e.g., stimulus checks, monetary policies).
- Evaluate how different sectors (e.g., food, healthcare, housing) were affected.
- Build models to forecast inflation trends based on the pandemic data.

## Dependencies

The following dependencies are required to run the project:

- Python 3.x
- [List of Python packages used, e.g.,]
  - `numpy` >=1.20.0
  - `pandas` >=1.2.0
  - `matplotlib` >=3.3.0
  - `seaborn` >=0.11.0
  - `scikit-learn` >=0.24.0
  - `statsmodels` >=0.12.0
  - `plotly` >=4.14.0
  - `requests` >=2.25.1

To install the dependencies, use the following:

```bash
pip install -r requirements.txt


## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         inflation_pandemic and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── inflation_pandemic   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes inflation_pandemic a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

