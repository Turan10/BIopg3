Group members: Turan, Sitthichai, Vivek and Metin. 
BI 3 miniproject - linear regression and predicting house pricing. 

What type/s of regression have you applied?:
Linear regression, with one variable, was the first model we used, where we looked at the sqft_living attribute, which was the one with the highest gain, to predict house prices. 
Multiple Linear Regression with PCA: Next, we tried a more advanced method where we used several features (like size, number of bathrooms, etc.). Before using these features, we applied PCA, a technique that helped us focus only on the most important aspects of our data. It's like narrowing down to the most influential factors that determine a house's price.
Polynomial Regression: Finally, we experimented with a method that considers not just the size of the house but also its square (size and size²) to predict prices. This approach is useful for capturing more complex relationships between size and price.

Which were the challenges?:
One of our biggest challenges was figuring out which features (size, age, location) are crucial for accurately predicting house prices.
We needed to strike a balance between making our model sophisticated enough to capture the nuances of the data and keeping it simple enough to be practical and efficient.
We noticed some houses with unusually high or low prices (outliers) and realised that there could be more information in the data which we would have to ignore when only using the features we chose. 

How accurate is your solution?:
Our models had moderate success. The PCA model with multiple features explained about 64.8% of house price variations, with an average prediction error (RMSE) of around 231. The polynomial regression model, however, was less precise in its predictions.

What could be done for further improvement of the accuracy?:
We think examining additional or different features might improve our predictions.
We could also use more sophisticated models and techniques which would handle or fit our data better.
More effectively managing outliers and adjusting for non-linear relationships could enhance model performance and results.
Adjusting some parameters could give better results and enhance performance.
test our models on different segments of the data, to check if our models are reliable and don't just work with the specific data we trained them on.
