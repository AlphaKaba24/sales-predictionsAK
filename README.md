# Sales volume does not always correlate to the size of the outlet

## Sales predictions for large Supermarket chains

**Author: Alpha Kaba**

#### Business Problem: I was tasked with finding correlation between these many sales metrics to ultimately utilize a model to predict sales volume.

DATA: Sales data from multiple different stores of different sizes; included data on not only the stores themselves but also the products sold within the store

## Methods

> Data preparation was the first step: Cleaning(missing values, duplicates, etc.), fixing inconsistent categories, etc

> Data visualition was the most integral part here(correlation heatmap, barplot, scatterplot) it tells the story of the data in a universally understood way

> Lastly, the most **important** aspect of this whole process was getting the data prepped for our ML models and finding the right model for our data

**RESULTS**

**Sales per food item type**

![download (1)](https://user-images.githubusercontent.com/97268064/171047410-5044b0ac-d245-4ad9-95e6-ca2778f217d5.png)

>**Fruits and Veggies and Snack Foods dominate Average sales across all outlet sizes**



**Outlet Sizes per Outlet Type**

![download](https://user-images.githubusercontent.com/97268064/172299511-d7a9c00f-6236-4a84-a6b0-c365bf1ba676.png)


> Supermarket Type 1 seems to have the most stores overall and contains both Medium(actually the only outlet type that contains medium sized stores) as well as Small outlets; Medium outlets account for the majority of Sales so Supermarket Type 1, in turn, brings in the most revenue.


## Model

Linear Regression model with a low MSE, MAE and RMSE.

I think with such limited avg. error, this model is dependable when predicting sales volume for the future.

## For Further information

Please feel free to reach out to me:

kabaalpha@yahoo.com






