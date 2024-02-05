Kaggle's Titanic Challenge
==============================

This project addresses the Titanic challenge on the Kaggle platform, using the Cookiecutter Data Science Project template. The solution was developed and submitted on the plaform.

<i>Link: https://www.kaggle.com/competitions/titanic/</i>

### Key Steps:

* Problem Understanding:

The goal is to predict whether a passenger survived or not in the Titanic disaster.

* Project Setup:

Utilization of the Cookiecutter Data Science Project template to structure the project.

<i>Template: https://drivendata.github.io/cookiecutter-data-science/</i>

* Exploratory Data Analysis (EDA):

Data exploration to identify patterns, distributions, and correlations.
Visualization of data through graphs and plots.
Handling missing data and outliers.

<i>Notebook: [1.0-exploration-reports.ipynb](https://github.com/marciosimoes/titanic-kaggle/blob/master/notebooks/1.0-exploration-reports.ipynb)</i>
<br><i>Reports: [exploring-initial.html](https://projects.marciosimoes.com/titanic-kaggle/reports/exploring-initial) and [exploring-survives.html](https://projects.marciosimoes.com/titanic-kaggle/reports/exploring-survives)</i>

* Data Preprocessing:

Treatment of missing values and outliers.
Encoding of categorical variables.
Feature engineering, if necessary.

<i>Notebook: [2.0-cleaning-and-transformation.ipynb](https://github.com/marciosimoes/titanic-kaggle/blob/master/notebooks/2.0-cleaning-and-transformation.ipynb)</i>

* Modeling:

Selection of machine learning algorithms (e.g., Linear Regression, Logistic Regression, SVM).
Training and tuning models using the training set.

<i>Notebook: [3.0-model-tests.ipynb](https://github.com/marciosimoes/titanic-kaggle/blob/master/notebooks/3.0-model-tests.ipynb)</i>

* Evaluation and Submission:

Model evaluation with the test set.
Submission of the result on Kaggle, achieving a maximum score of <b>0.76794</b>.


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
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
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
