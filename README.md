# Housing_Assignment

### Problem Statement : A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. The company wants to know

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
 
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.


### General Information

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusion :
The optimal lambda value in case of Ridge and Lasso is as below:

- Ridge - 5
- Lasso - 0.0001

The Mean Squared error in case of Ridge and Lasso are:

- Ridge - 0.016
- Lasso - 0.014

The Mean Squared Error of Lasso is slightly lower than that of Ridge

Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house, GrLivArea type of the house, LotFrontage, Total basement area in square feet and the Basement finished square feet area

Therefore, the variables predicted by Lasso in the above table as significant variables for predicting the price of a house.

