# Macf-491---Statistical-Learning
Some of the machine learning projects that I worked on during that course
More information on the assignments can be found here.
Q1: This question attempts to predict the weekely electricity consumption of Scandanavian countries using Fourier expansions and regressions.
Most machine learning methods are created from their defintions without using built in functions, such as for Ordinary Least Squares.
K fold cross-validation is then performed using the above function
The optimal parameters are obtained, and there is a graph showing the true values vs the predicted values.
Q2: In this part, I attempt to predict whether a borrower will be able to pay back his balance using linear regression models and 5 fold cross validation.
First I calculate the 5 fold cross validation RMSE and MSE where the "Balance" is regressed on all other parameters.
Next I find out which parameters are significant on the 5% confidence level and repeat the above step just for the significant parameters.
Then, I perform a forward variable selection using "regsubsets" and find which parameters minimize the Bayesian Information Criterion (BIC)
Then, I perform the selection with an exhausitve approach as opposed to a forward approach.
Next I use glmnet package to find the 5 fold RMSE of a ridge regression, then of a lasso regression.
