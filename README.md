Uber-Demand-Prediction [[Link of the deployed website](http://16.16.121.209:8501)]
==============================

The project is a regression problem that has input features about the rider, the vehicle he owns, the weather condition, traffic and location of restaurant and delivery. The goal of the project is to predict the time in min to deliver the order from origin to destination.

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


![uber](https://github.com/user-attachments/assets/f906fb83-0c17-4e45-9d59-62d9e690b252)  


# Exploratory Data Analysis

![Screenshot 2025-05-12 104728](https://github.com/user-attachments/assets/8113947e-392c-4766-8f3c-c47b84632abd)

Observations:
1. Creative Mobile Technologies holds a slightly larger share of the vendor market in NYC, accounting for 53.26% of the total.
2. VeriFone Inc. represents 46.74%, indicating a competitive distribution between the two vendors.



![Screenshot 2025-05-12 104728](https://github.com/user-attachments/assets/262ed791-44c9-41e7-a82e-c1ff5dd81930)

Observations: 
1. The highest frequency of passengers is for 1 passenger, with approximately 2.5 million instances, indicating a strong preference for single-passenger rides.
2. The second-highest frequency is for 2 passengers, with approximately 0.5 million instances, suggesting a notable but smaller demand for two-passenger rides.



![Screenshot 2025-05-12 104728](https://github.com/user-attachments/assets/f1150620-b96f-467b-9197-85be707fadde)

Observation:
1. The fare amount increases steadily from 5.0 at the 10th percentile to 18.0 at the 80th percentile, indicating a gradual rise in fare amounts as the percentiles increase.
2. A sharp spike occurs at the 100th percentile, with a fare amount of 429,496.72, suggesting the presence of outliers or exceptionally high fares in the data.



![Screenshot 2025-05-12 104728](https://github.com/user-attachments/assets/26bd5adc-bd54-4a01-80d2-b19e7a04c13c)

Observation:
1. The majority of trips are associated with RatecodeID 1.0, with a count of 33,627,000, indicating it is the most common rate code.
2. RatecodeID 6.0 and 99.0 have significantly lower counts, with 320 and 835 respectively, suggesting they are rare or less frequently used rate codes.



![Screenshot 2025-05-12 104728](https://github.com/user-attachments/assets/a9f287a8-889f-40bd-ac9b-324b3adf853a)

Observation:
1. The data shows fluctuations in the pickup counts over the span of three months, with the highest pickup count recorded on 2016-02-12 at 1,285,409.
2. 2016-03-31 has the lowest pickup count at 394,055, indicating a significant drop in pickups compared to the rest of the period, potentially due to external factors or anomalies.



![Screenshot 2025-05-12 104728](https://github.com/user-attachments/assets/db632532-3d3c-4557-a6c9-63ee5d394c90)

Observation:
1. The highest demand occurs between 18:00 and 20:00 hours, with a noticeable dip in demand on Sundays, where the numbers are consistently lower throughout the day compared to other weekdays.



We successfully launched the website/app ->  [[Link of the deployed website](http://16.16.121.209:8501/)]


















