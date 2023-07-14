

## Data Science Template

A code starter for creating Python (Data Science) projects.


## Project Organization

    │
    ├── Makefile           <- Makefile with commands: create_environment, initialize_git, install, clean
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── .github/workflows  <- Github actions workflows
    │  
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── config
    │   └── config.yaml    <- Configuration file for the project
    │
    ├── logs
    │   └── logger.log     <- Log file for the project
    │
    ├── docs               <- A default pdoc project
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),the creator's initials,
    │                        and a short `-` delimited description, e.g.`1.0-jqp-initial-data-exploration`.
    │
    ├── requirements
    │   ├── requirements.txt        <- The requirements file for reproducing the analysis environment, e.g.
    │   │                               generated with `pip freeze > requirements.txt`
    │   └──test_requirements.txt    <- Test requirements file for github actions and tox
    │
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   └── predict.py     <- Script to run predictions
    │
    │── main.py        <- Main script to run the project
    │
    ├── tests                       <- Test scripts
    │   ├── __init__.py             <- Makes tests a Python module
    │   └── test_prediction.py      <- Test script for predict.py
    │
    ├── Dockerfile         <- Dockerfile for the project
    │
    ├── .gitignore         <- .gitignore file
    │
    ├── .pre-commit-config.yaml <- pre-commit configuration file
    │
    └── tox.ini            <- tox file with settings for running tox


--------
