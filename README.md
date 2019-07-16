# Random-Forest:
Random forest is an ensemble learning method for classification and regression mostly. It works in two parts. The first step involves Bootstrapping technique for training and testing and second part involves decision tree for the prediction purpose. Now like every other predictive modelling technique we have the goal to minimize the generalization of error. To decrease that we make the balance between the bias and variance called as Bias-variance tradeoff.

# What exactly is Bias-variance tradeoff?

1.      Bias is the error for the wrongful assumptions we make building the learning algorithm. It is the primary reason for the under fitting the model. When the bias becomes higher then there is huge gap in the relationship between the regressors and the response variable hence under fit model. 

2.      Variance is the error due to fluctuations in the training set. When we have high variance then our model is going to over fit.



To have the lowest generalization of error we need to find the best tradeoff of bias and variance.
# Gradient-Boosting:
# What is boosting?

1.Boosting itself nullifies the overfitting issue and it takes care of the minimizing the bias.

It helps to find a predictor which is a weighted average of all the model used. It manipulates the training set to work on the area where we find high errors. It adds new trees to the original trees and helps to achieve the maximum accuracy.
# There are following steps we can follow:

1.Assign a response variable which is the weighted average of all the models.

2.Training of first model on the train set and use the response variable for just this model.

3.For Gradient Boosting, redefine the supervised response variable with the alignment of some kind of residual between the ground truth and   the overall response variable.

4.Train the new modified data as training set and use the updated response variable as the predictor.

5.Repeat the above 3rd and 4th steps.

Basically boosting used the simple technique of weighted majority vote for classification from all model classifications.
