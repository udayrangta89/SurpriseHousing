# Surprise Housing
> A US based company buys houses at a cheaper rate and sells them a higher price.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house. 
 
Business Goal 
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We want to prodict the price of a house and sell it at a higher price
- A US based company wants to predict SalePrice of a house using different variables for its profit
- We want to create a model for price of houses with the available in independent variables
- We have different varaibles that one sees before buying a house and thus they contribute to the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
We have 3 float type, 35 int and 43 object type.and we see that there are some columns with null values.
- Conclusion 2 from the analysis
Note the correlation between LotFrontage and SalePrice is 0.351799. We will use this obseravation in deciding if the missing value needs to be deleted for LotFrontag
- Conclusion 3 from the analysis
Number of columns with some value as null : 19
- Conclusion 4 from the analysis
For LotFrontage, there are 257 missing values which account to 17% of the data. There is a correlation between LotFrontage and SalePrice so its important to get the right values.
- Conclusion 5 from the analysis
    After decidign to go with Lasso model.
   Top 5 significant variables in predicting the price of the house-
        1. Neighborhood_StoneBr
        2. SaleType_New
        3. Neighborhood_NoRidge
        4. Neighborhood_NridgHt
        5. BsmtQual_Gd

- Conclusion 5 from the analysis
Company can use this model to predict the actual values and buy them at a lower price than what the model has predicted.
They can either go with variables with stong + coefficients, like Stonebrook, Northridge, Northridge heights neighbourhood, Newly constructed homes. 
And with Strong -ve coefficients - like Height of basement between 80 to 99 inches, Kitchens above grade, Roof material Grave and Tar.
Business can make decision according to the coefficients, like if Roof material is Grave and Tar, they can buy it a very low cost highlighting the material, probably if they find in a good neightbourhood,and sell it at higher price by highlighting the good neighbour feature.
There are 105/240 variables that according to lasso will impact the SalePrice of the house.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- The project is an outcome of the learning from upGrad Python, Essential Statistic and Machine learning modules.


## Contact
Created by [@udayrangta89] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->