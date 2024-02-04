# Data science project template with cookiecutter 

With the aim of creating a reproducible structure, this repository contains a structural template of a data science project.

## Tools used in this project
- [Cookiecutter](https://www.cookiecutter.io): Open Source Library for building coding project templates
- [Poetry](https://python-poetry.org): Dependency management

## Project structure

```
├── README.md                       <- Describe your project
│
├── configs                  
│   ├── main.yaml                   <- Main configuration file
│   ├── model.yaml                  <- Configurations for training model
│   └── preprocess.yaml             <- Configurations for processing data
│
├── data
│   ├── final                       <- Data after training the model 
│   ├── processed                   <- Data that has been transformed or after processing
│   └── raw                         <- The original raw data
│
├── docs                            <- Documentation for your project
│
├── models                          <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks                       <- Jupyter notebooks
│
├── src                 
│   ├── __init__.py                 <- Make src a Python module 
│   ├── evaluate_model.py           <- Model evaluation
│   ├── process.py                  <- Process data before training model   
│   └── train_model.py              <- Train model
│── tests                 
│    ├── __init__.py                <- Make tests a Python module 
│    ├── test_process.py            <- Test functions for process.py
│    └── test_train_model.py        <- Test functions for train_model.py
│
├── pyproject.toml                  <- Dependencies for poetry
│
└── requirements.txt                <- The requirements file for reproducing the analysis environment, e.g.
                                       generated with `pip freeze > requirements.txt`
```

# How to use this project

Install cookiecutter 
```
pip install cookiecutter
```
Create a project based on the template
```
python -m cookiecutter https://github.com/LilianVital/project-template-ds
```
