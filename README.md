# CaliforniaHousingPrices

This project was part of my journey to understand machine learning from the ground up. Rather than relying solely on libraries like scikit-learn, I wanted to implement algorithms manually to grasp their mechanics and challenges.

##Context
This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine Learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning


##Content
The data describes houses in various California districts, along with summary statistics based on 1990 census data. Note that the data is not pre-cleaned, so preprocessing steps are required. The columns are as follows:

longitude: A measure of how far west a house is; a higher value is farther west
latitude: A measure of how far north a house is; a higher value is farther north
housingMedianAge: Median age of a house within a block; a lower number is a newer building
totalRooms: Total number of rooms within a block
totalBedrooms: Total number of bedrooms within a block
population: Total number of people residing within a block
households: Total number of households, a group of people residing within a home unit, for a block
medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
medianHouseValue: Median house value for households within a block (measured in US Dollars)
oceanProximity: Location of the house w.r.t ocean/sea

##Goal
The goal of this project is to create a Linear Regression model to predict median_house_value (the target variable). Linear Regression will be implemented using:

The normal equation

Batch Gradient Descent (BGD)

Stochastic Gradient Descent (SGD)

Mini-Batch Gradient Descent (MBGD)

Additionally, models with and without regularization will be explored, as well as polynomial regression models.


