# MVP - Food Inspection Prediction
#### Diego Duque

Predict when a restaurant and other food establishment in Chicago will pass a food inspection.

I have over 222K data points and 17 features. I was able to maintain the most of the 222K data point but I reduced the number of features in order to make progress in the project.

Some interesting findings during the EDA is the variaton on food inspections over the eyars. Especially since 2018.

<img src="https://github.com/dieguque/Chicago_Food_Inspections/blob/87518b5fd792cffbf96bc863353491b623e91045/charts/Inspections%20Results.png">
 
Most of my features were categorical features so I used the **LabelEncoder** which is in my opinion more efficient than **dummies**. 
 
Using that I was able to get a **pairplot** where it's clear the complexity of the data.

<img src="https://github.com/dieguque/Chicago_Food_Inspections/blob/0b3a10e576b8831864cfe1ace196fb3ab18dc26c/charts/pairplot.png">

This data is easier to read and visually understad with a heatmap.

<img src="https://github.com/dieguque/Chicago_Food_Inspections/blob/0b3a10e576b8831864cfe1ace196fb3ab18dc26c/charts/heat_map.png">

## Baseline Model
After defining my *y* which is **Results** and get defining my *X* I was able to create my first model: **Simple Logistic Regression**

<img src="https://github.com/dieguque/Chicago_Food_Inspections/blob/0b3a10e576b8831864cfe1ace196fb3ab18dc26c/charts/Scaled%20Logisitc%20Rgression.png">

## Next Steps
Keep using and analyzing other classification models.
