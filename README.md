# food_sales_predictions
Predicting the sales of various food items, based on visibility, outlet size, fat content, item type, and MRP. 

This data was gathered from the Analytics Vidhya Hackathon: Big Mart Problem. The goal was to develop a machine learning model that can predict food item sales. Correlations between variables after encoding was analyzed to view patterns in the dataset.

![FoodSalesHM](https://user-images.githubusercontent.com/91214731/142919128-fb466ce3-7423-4e4a-aea5-54f5836ad1fa.png)

Item MRP and Item Sales displayed a moderately strong correlation that was examined further.

![FoodSalesvMRP](https://user-images.githubusercontent.com/91214731/142919715-0692f607-6f8f-43be-9519-06b82adc6b39.png)

A decision tree model was developed and tested against a linear regression model using R2, MAE, MSE, and RMSE as metrics. The decision tree model outperformed the linear regression model on all metrics.

Recommendations for this project include maximizing the visibility and promoting items that are high MRP in starchy foods, breakfast foods, and seafoods categories, especially in Supermarket Tier 3 store types. Please see the attached video presentation for a more complete overview of the data, model, and recommendations.
