# Research on car sales ads
The project from the Exploratory Data Analysis sprint of the Practicum DA/DS course.

## Description

Here we have a dataset of free vehicle advertisements, and our goal is to determine which factors influence the price of a vehicle. 

First, we should do some data preprocessing: fill in the missing values, clean spelling errors, and change data types. Also, we need to add some new columns to help our analysis. After doing so, we could explore our data and see if we could make any predictions.

## Conclusion
After preprocessing, I removed entries with price, age, and mileage outliers. It gave me a smaller (about 70% volume) dense subset.
From this cleaner subset, I took two types of vehicles (sedans and SUVs) and explored how different aspects affect the price. There is some negative correlation between the car's age and its price but not very strong. And there is almost no influence from the mileage, condition, transmission or colour. I suppose the main reason is that we took too broad categories (very different cars are called sedans or SUVs). Splitting them into smaller subcategories or taking other types could give better results.
