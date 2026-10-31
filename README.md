# SpaceX Falcon 9 First Stage Landing Prediction

## Project Overview

This project investigates the landing success of SpaceX Falcon 9 first-stage boosters using data science and machine learning techniques.

SpaceX's ability to reuse its Falcon 9 first-stage boosters significantly reduces launch costs. Predicting whether a booster will successfully land is therefore an important part of understanding the economics and reliability of reusable rocket technology.

The objective of this project is to analyse historical Falcon 9 launch data, identify factors associated with landing success, and develop machine learning classification models to predict the outcome of future first-stage landings.

This project was completed as part of the **IBM Data Science Professional Certificate – Applied Data Science Capstone**.

##Repository Update

This repository contains an updated version of my original capstone submission.

The notebooks and code have been reviewed and revised to address implementation issues encountered during the initial version. The updated upload aims to provide a more complete, functional and consistent representation of the project workflow.

## Project Objectives

- Collect and explore historical SpaceX launch data.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) to identify patterns and relationships.
- Investigate the influence of launch sites, payload mass, orbit types and booster characteristics on landing success.
- Develop and evaluate machine learning classification models.
- Compare model performance to identify effective approaches for predicting landing outcomes.

## Technologies and Libraries

The project uses Python and several data science and machine learning libraries.

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Development and analysis environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical data visualisation |
| Scikit-learn | Machine learning and model evaluation |
| BeautifulSoup | Web scraping and HTML parsing |
| Requests | HTTP requests and data retrieval |

## Project Methodology

The project follows a structured data science workflow.

### 1. Data Collection

Historical SpaceX launch information is obtained using publicly available data sources and datasets provided through the IBM Skills Network course.

The data includes information such as:
- Flight number and launch date.
- Booster version.
- Payload mass.
- Orbit type.
- Launch site.
- Landing outcome.
- Booster flight and reuse information.

### 2. Data Wrangling

The collected data is prepared for analysis through:
- Filtering the dataset to include Falcon 9 launches.
- Handling missing values.
- Converting variables into appropriate data types.
- Preparing features for exploratory analysis and machine learning.

### 3. Exploratory Data Analysis

Exploratory data analysis is used to investigate relationships between launch characteristics and first-stage landing success.

The analysis considers factors such as:
- Launch site.
- Flight number.
- Payload mass.
- Orbit type.
- Booster version and reuse history.

Visualisations are used to identify trends, distributions and potential relationships within the dataset.

### 4. Data Visualisation and Analysis

Python visualisation libraries are used to communicate findings and investigate patterns in the historical launch data.

### 5. Predictive Analysis

Several supervised machine learning classification algorithms are implemented and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbours (KNN)

Hyperparameter tuning is performed using `GridSearchCV` and cross-validation to identify suitable model configurations.

### 6. Model Evaluation

Model performance is assessed using classification accuracy and confusion matrices.

These evaluation techniques help determine how effectively each model predicts successful and unsuccessful first-stage landings.

## Dataset

The primary analytical dataset contains **90 Falcon 9 launch records** and 17 columns.

The dataset includes variables describing launch characteristics, payload information, booster configuration, landing outcomes and launch-site coordinates.

**Dataset source:** IBM Skills Network – Applied Data Science Capstone.

[IBM Falcon 9 Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/dataset_part_1.csv)

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Working with real-world datasets.
- Retrieving and preparing data for analysis.
- Web scraping and working with APIs.
- Performing exploratory data analysis.
- Identifying relationships between variables.
- Preparing datasets for machine learning.
- Implementing classification algorithms.
- Performing hyperparameter optimisation.
- Evaluating predictive models using appropriate metrics.

## Repository

This repository contains the notebooks, analysis and supporting materials associated with the SpaceX Falcon 9 First Stage Landing Prediction capstone.

The project demonstrates the application of data science concepts throughout the process, from data preparation and exploratory analysis to predictive modelling and evaluation.

## Acknowledgements

This project was completed as part of the **IBM Data Science Professional Certificate**, with learning materials and datasets provided through IBM Skills Network.

Data and background information are based on publicly available SpaceX launch information.

---

**Author:** Stefan Bezuidenhout  
**Project:** IBM Applied Data Science Capstone  
**Focus:** Data Science | Machine Learning | Predictive Analytics
