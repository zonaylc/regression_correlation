# regression_correlation
An assignment from course "Statistical Principel of DataScience" for understanding the correlation effect on the linear regression models.

### Data:
prostate_data.txt

##### Data Description:
A dataset from the study by [Stamey et al., 1989], examining the correlation between the level of prostate-specific antigen and a number
of clinical measures in men who were about to receive a radical prostatectomy.

### Tasks
Using 'glmnet' package in Rstudio to:

1. Exploration of the Effect of Correlation
*Fit a linear regression model with lcavol as predictor.
*Fit a linear regression model with lcp as predictor.
*Fit a linear regression model with lcavol and lcp as predictors.
*Compare the standard error for predictors in each model and explain the reason
why the predictors in the third model has larger standard error than the simple
models.

2. Fit Ridge Regression Model
*Fit a full ordinary least square model.
*Fit a ridge regression model.
*Plot the trace of the estimated coefficients against λ and verify from plot when
the λ are approaching to zero the coefficients for each predictor are equal to the
one obtained from ordinary least square model.
*Choose the best λ and give an explanation why you choose that.
*Find the coefficients using the λ you picked. And make a prediction for test data
with these coefficients. Calculate the rMSE to assess the performance of your
model.

3. Fit LASSO Model
*Fit a LASSO model.
*Plot the trace of the estimated coefficients against λ. Compare this trace plot
with the one for ridge regression.
*Choose the best λ and motivate your choice.
*Find the coefficients using the λ you picked. And make prediction for test data
with these coefficients. Calculate the rMSE to access the performance of your
model.
*Compare the estimates from ridge regression and LASSO.

4. Fit Elastic Net Model
*Fit an elastic net for our training data.
*Choose the best set of λ1 and λ2.
*Evaluate your result with explanation (e.g. compare the CV-RMSE for these
three models).

#### References
Thomas A Stamey, John N Kabalin, John E McNeal, Iain M Johnstone, Fuad Freiha,
Elise A Redwine, and Norman Yang. Prostate specific antigen in the diagnosis
and treatment of adenocarcinoma of the prostate. ii. radical prostatectomy treated
patients. The Journal of urology, 141(5):1076–1083, 1989.
