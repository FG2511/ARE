#BIG DATA

Dataset:

The dataset contains minute-by-minute data about temperature, humidity, air pressure and different kind of gases, collected by the uHoo air quality sensor (https://uhooair.com/). The raw dataset has been manipulated to add:
  - an attribute 'Activity' that can assume the values 'Meal' (class 1) or 'Other' (class 0).
  - other attributes that give informations about meals: food, domestic appliances, windows. 
    Also these attributes are binary (values: 0,1).

Problem 1:

Given the dataset described above, train a NN for a binary-class classification probelm. The NN has to classify if a minute belongs to the class 'Meal' (1) or to the class 'Other' (0).


Problem 2:

Given the results of "Problem 1", train a NN for a multi-class classification problem. The NN has to determine what kind of food has been cooked during the meal.
