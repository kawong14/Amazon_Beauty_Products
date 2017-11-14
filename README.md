# Amazon Beauty Products

## KeyProblems / Issues: 
As a beauty retailer on Amazon, you want to determine if there is an optimal way you can recommend products to customers

## Neural Network: 
* The purpose of this neural network is to make predictions to see if customers would like a product
* The three variables I am looking at are (User ID, Product ID, and Rating) 
* By creating a neural network on users’ history of the products and how they rated it the model would recommend products
  * Inputs: 
    * User ID (reviewerID)
    * Product ID (asin = amazon standard identification number)
  * Output: Rating (overall)
  
## How It Works:
  For Example: We want to predict products Customer-B would likely want to purchase
  * Customer-A purchases Product 1 and rates it 5/5 stars with 5 being the highest value
  *	Customer-A then purchases Product 2 and rates it 5/5 stars
  *	Customer-B purchases Product 1 and rates it 5/5 stars
Therefore the model would recommend that Customer-B would like Product 2  

## Analyses:
  	Option 1: Fully Connected Neural Network
  	Option 2: Gradient Boosted Decision Trees-XGBoost

## Summary: 
The results from Option1 had an RMSE of 1.32, and the Option2 has an RMSE of 0.33.  The XGBoost model can more accurately predict the rating of a product than the neural network.  
