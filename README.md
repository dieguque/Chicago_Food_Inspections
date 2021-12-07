# Chicago Food Inspections

Diego Duque

## Abstract

According to the **City of Chicago** there are over 15,000 food establishments across the City of Chicago that are subject to sanitation inspections by the Department of Public Health. Three dozen inspectors are responsible for checking these establishments, which means one inspector is responsible for nearly 470 food establishments. The Department of Public Health has systematically collected the results of nearly 100,000 sanitation inspections. That is enough data to make a classification project to interpret and even create some models to understand and predict these inspections.
This data is public and avilable at the [Chicago Department of Public Health’s Food Protection Program](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5).

## Design

This project originates from the idea to understand more about the huge restaurant industry in Chicago. As a Chicago resident and as a consumer, I came up with the idea to collect more information for other residents; especially for parents and families in general. Fortunately, the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5) has some related information to all food establishments in the city. This huge data set was used to create some classification and interpreation models.

## Data

The data is public. It is available on [Kaggle](https://www.kaggle.com/tjkyner/chicago-food-inspections) and the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5). This dataset has 17 features and 223K inspections. Most of its features are categorical.

## Algorithms 

Data Collection and Manipulation

Gathered data from the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5) and performed feature engineering to cut down the features from 17 to 9.

Modeling


Random Forest
XGBoost

## Tools

1. Sklearn 
  - LogisticRegression
  - RandomForestClassifier
  - GridSearchCV
  - Fbeta_score
  - Confusion_matrix
  - Classification_report
2. Xgboost - XGBClassifier
3. Numpy
4. Pandas

## Communication

In addition to these charts, this is the direct link to the [presentation](https://github.com/dieguque/Chicago_Food_Inspections/blob/f32d80afd4a4638aba4a8ea6e2a83f8a3acd6325/Chicago%20Food%20Establishments.pdf).

2010 - 2021 Chicago Food Inspections

<img src="https://github.com/dieguque/Chicago_Food_Inspections/blob/f32d80afd4a4638aba4a8ea6e2a83f8a3acd6325/charts/Inspections%20Results.png">


Random Forest Confusion Matrix

<img src="https://github.com/dieguque/Classification-Project/blob/348e02e704f2aa69de3aad5a06bf43d0960f987a/charts/confusion_matrix_rf_food.pngx">


XGBoost Feature Importance (frequency)

<img src="https://github.com/dieguque/Classification-Project/blob/348e02e704f2aa69de3aad5a06bf43d0960f987a/charts/feature_importance_frequency.png">

XGBoost Feature Importance (gain)

<img src="https://github.com/dieguque/Classification-Project/blob/348e02e704f2aa69de3aad5a06bf43d0960f987a/charts/feature_importance_gain.png">
