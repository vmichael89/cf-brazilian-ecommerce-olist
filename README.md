brazilian-ecommerce-olist
==============================

Data analysis on Brazilian E-commerce Public Dataset provided by Olist.

The analysis entails the following steps:
1. Thorough data understanding
2. Spatial analysis
3. Implementation of unsupervised and supervised machine leaning techniques
4. Time series analysis
5. Forecasting utilizing ARIMA
6. Design of an informative data dashboard

This project also serves as a source of inspiration for automation and supportive tasks in data analysis, which will be further developed as part of my current side project; the [`databridger` library on GitHub](https://github.com/vmichael89/databridger), which I am developing alongside my journey in data analytics. Some notable ideas for `databridger` being persued include:
- **Automatic Column Classification**
- **Generic Analysis of Inter-Table Key Relationships**: Identify primary and foreign keys.
- **Issue Tracker Implementation**: A robust system to log, track, manage and document issues found during the analysis phase.

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks
    │   ├── 1.0-initial-data-exploration
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
