## Data mining Boston AirBnB data set using CRISP-DM process model

The CRoss Industry Standard Process for Data Mining (CRISP-DM) is a process model with six phases that naturally describes the data science life cycle. It’s like a set of guardrails to help you plan, organize, and implement your data science (or machine learning) project.[1]

In this project I will follow the CRISP-DM process model to analyze the Boston AirBnB data set to answer the following questions:

1- How is price impacting the occupancy of Apartments during the year?
1- What other factors may impact the selection of an apartment beisdes de price?
1- Do the physical location of the property has an impact on the occupancy of the property?
1- Model a price predictor based on some features of the listings data set


## Libraries used

To run the associated Jupyter Notebook please ensure your python environment contains the following libraries:

- folium
- matplotlib
- numpy
- pandas==1.2.3
- seaborn

## Boston AirBnB Data 

The Boston Airbnb data set consist of three different comma separated value files:

listings.csv, including full descriptions and average review score
calendar.csv, including listing id and the price and availability for that day
reviews.csv, including unique id for each reviewer and detailed comments

This analysis will use only the first two files, listings and calendar.


[1] CRISP-DM. (2021, July 31). Data Science Process Alliance. https://www.datascience-pm.com/crisp-dm-2/






