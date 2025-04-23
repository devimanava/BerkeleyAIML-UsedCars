# BerkeleyAIML-UsedCars


## Objective
Based on a Kaggle dataset that contains information on 426K cars, the objective here is to understand what factors make a car more or less expensive - the analysis done should have clear recommendations for a prospective client (a used car dealership), highlighting what consumers value in a used car. 

## Overview of the Approach Chosen
For this analysis, the CRISP-DM framework will be used that consists of the below phases:

a) Business Understanding: This involves coverting the business objective above into a data problem whiel outlining the project goals and success criteria

b) Data Understnding: This focuses on collecting and exploring the available data, with an objective to understand the schema and identify potential quality issues 

c) Data Preparation: This consists of activities that makes the data ready for modeling purposes

d) Modeling: Involves developing models based on shortlisted modeling technique and assessing them

e) Evaluation: Identify the most suited model and validate if it meets business needs

f) Deployment: Deploy the model in production and monitor it [not in scope of this exercise]

## Development Details
The Jupyter notebook prompt_II.ipynb has the code and execution results for each phase listed above. After preparing the data through various techniques (dropping unwanted columns, removing outliers, addressing missing data etc.), different regression models (linear and polynomial) were evaluated and additional regularization (Lasso regression) was also tried out. Based on the results, a polynomial regression of degree 3 was chosen as the model for making recommendations. 


## Findings from the Exercise
The pricing of a used vehicle is influenced significantly by the year, odometer reading, drive type and fuel type among the available features. To maximize the price at which a used vehicle is sold:

a) The vehicle should be as young as possible (Year)

b) The vehicle should have had as less miles covered as possible (Odometer Reading)

c) 4 wheel drives can be charged a premium (Drive Type)

d) Diesel vehicles are charged higher (Fuel Type) 




