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



**Distribution of Sales based on item visibility in stores**

![download2](https://user-images.githubusercontent.com/97268064/171047926-ea141bc9-ed80-454d-8570-e6a3cc22810d.png)

> I dont see a direct correlation between how visible an item and how much that item sells however, the important takeaway here is there does not seem to be a strong correlation with the size of the outlet either.
The majority of the higher selling items are coming from Medium size outlets, not what I would have expected.


## Model

My model contains an Imputer for missing values that were leftover in some of the numberical columns as well as a OneHotEncoder for my categorical columns




