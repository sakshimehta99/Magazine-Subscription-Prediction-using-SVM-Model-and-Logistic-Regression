# Magazine-Subscription-Prediction-using-SVM-Model-and-Logistic-Regression

Introduction

In this project, the goal is to work on a dataset that has details of magazine subscriptions from its various customers, predict if the customer accepts the offer in the first campaign, and find out what factors might affect the end goal. The features from the dataset will be explored and analyzed to find out the trends and patterns of customers and then Machine Learning models will be created to share the results with the company that can strategize their subscription plans to gain maximum profit.

Analysis

Modeling

The dataset after all the cleaning of the variables and after performing one hot encoding has a total of 14 features and 1 target variable. Now, we will be performing both Logistic regression and SVM model and find out which works better and what features are significant to understand the population of subscribers.
Logistic Regression and SVM

We build a Logistic Regression model to predict if the customer will accept the offer in first campaign. The model was trained on train set and then the test set is used to evaluate the
accuracy of the model. Our outputs of the summary tell us that Income, number of times the

customer visits the website in a month, total sales bu the customer, if they have children or not, the time passed since the customer subscribed are some of the important features that affect our target variable. We get an accuracy of 92% and the most significant factors were income, the number of times they visited the website, and their total sales. All of these have a positive
 
relationship with the target variable. We observe the confusion matrix and find out that the precision is 46% that we could predict 46% of correct positive predictions relative to total positive predictions and recall obtained is 18% that means we could predict 18% of correct positives wrt total actual positive.
After building SVM model we get an accuracy of 92%. However, the precision rate in this case was 67% and recall is 6% .

Comparison of the models

Both the models have provided results with si,ilar accuracy. However, there is difference in recall and precision. The true positive values for SVM are higher than Logistic Regression but before choosing the model, the size of the dataset matters as well. In our case the features are less and records are more therefore it is better to go with Logistic regression.

Conclusion

It can be inferred from the output summary of logistic regression that if the income is more, there is a possibility of subscription from the end user. Therefore, different marketing strategies should be used such that well off family be more attracted towards this. Moreover, having a good, interactive website can help get more customers. The more the visits, the more likely to convert to a subscriber. Total sales tell us that more the sale means people have preferred shopping from here and therefore different discount plans or benefits should be provided to loyal customers. If these things are taken care of, the better predicted results are guaranteed.
 
In terms of Model selection it is better to choose Logistic Regression for this type of dataset as the numer of rows is more and features are not a lot.

Reference:

●	Bassey, P. (2019, September 19). Logistic Regression Vs Support Vector Machines (SVM). Medium.
https://medium.com/axum-labs/logistic-regression-vs-support-vector-machines-sv m-c335610a3d16

●	Zach. (2022, May 9). How to Interpret the Classification Report in sklearn (With Example). Statology. https://www.statology.org/sklearn-classification-report/
●	Ray, S. (2015, November 26). Simple Methods to deal with Categorical Variables in Predictive Modeling. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2015/11/easy-methods-deal-categorical-va riables-predictive-modeling/


