# PHASE2_PROJECT #

### INTRODUCTION ###
We have been given a project for a Real Estate. In the project, we must use multiple linear regression modeling to analyze house sales in a northwestern county.

## BUSINESS UNDERSTANDING / PROBLEM ##
We need to advise homeowners about how home renovations might increase the estimated value of their homes, and how to price their property.

## OBJECTIVES ##
As a data scientist, you are to build multiple linear regression models that will predict the dependent variable which is the house sale price
against the various independent variable that we have been given in the dataset.

To see the relationship between them.

## SPECIFIC OBJECTIVES ##

To look for variables that are affecting housing prices.

Create models and evaluate how well the variables can/are predicting house prices.

To look at the correlation between the variables

### DATA UNDERSTANDING ###

We have been provided with King County House Dataset and column names. The column names contain certain data like:- date, price,	bedrooms, bathrooms,sqft_living, and floors, just to name a few . They contain categorical and numerical data.

### DATA ANALYSIS ###

This is where we explore the data, cleaned the missing values, remove the duplicates, and plot models. We got to see that the data had NaN values in the data and were replaced with 0. We got to also see that there were categorical and numeric data and they could not be plotted together using some plots instead you could either plot them separately or together by choosing to change the categorical columns to numeric values

Some columns are highly correlated to each other and others have a low correlation. Both high and low have an effect on the price to either higher or lower and in some cases where we would expect the price to be high it was low and where we expected it to be low it was high. From the data with some adjustments like making sure that the house/property condition was good, you can increase the price and make more sales at the same time. 

In the dataset, we had some outliers some of which were eligible to be dropped and some that were not eligible. the ones that were eligible for dropping were dropped. we also had simple linear and multilinear regression models that helped in identifying the R-squared, p-value, null, and alternative hypotheses.


### CONCLUSION ###

In the Kings County database I have made the following conclusions:-

1. The condition of the house greatly affects the pricing. 

2. The number of bathrooms in a property should be at least/ if not match the number of bedrooms

3. The property with sqft_basement had low pricing which may have been due to its size being small.

### RECOMMENDATION ###

1. Kings County should build more two to four bedrooms. This is because most people are going for those number of bedrooms which means it can increase the sales of the property and that of the county.

 They should also increase the size of the rooms instead of having many bedrooms which may be squeezed or small. You would rather have less room but with ample space if not spacious.

3. It is very important that the condition of the house is good because that will determine how much property you will sell. When the property is in good condition your can also increase the price by a certain percentage from what it was initially. 

4. Bathrooms are an important necessity in a property hence, most people want a good number of bathrooms depending on the number of rooms that are in the property. 

5. The bigger the sqft_living the more the property price. The properties with more sqft have been purchased more which means they are also in good condition and that is how most properties should be.

6. Make sure that the basement is in good condition and it is bigger it can have a good effect on the pricing which means it can be increased and you can also have more purchases of the property.
