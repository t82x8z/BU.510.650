java c
BU.510.650
Assignment #3
Data Analytics
Assignment #3Attention: Please prepare two files for each homework assignment: the .docx or .pdf file for your answers including figures to each question; the other .R file for your R script.  File names should be “LastName FirstName studentID.docx” and  “LastName FirstName studentID.R” for assignment 3. All assignments should submitted via Canvas.
1. In this exercise, we will generate simulated data, and will then use this data to perform. best subset selection.
(a) Use the rnorm() function to generate a predictor X of length n = 100, as well as a noise vector ϵ of length n = 100.  (Both X and ϵ follow the standard normal distribution.  Use set.seed(100) and set.seed(200) in generating X and ϵ, respectively)
(b)  Generate a response vector Y of length n = 100 according to the model Y = β0 + β1X + β2X2 + β3X3 + ϵ,
where β0 = 3,β1  = 2,β2  = 1,β3  = 0.5 are constants.
(c) Use the regsubsets() function to perform. best subset selection in order to choose the best model containing the predictors X, X2 ,..., X 10 . What is the best model obtained according代 写BU.510.650 Assignment #3 Data Analytics
代做程序编程语言 to Cp, BIC, and adjusted R2?  Show some plots to provide evidence for your answer,  and report the coefficients of the best models obtained.   Hint:   you  can use regsubsets(Y~poly(X,10,raw=TRUE),data=data.frame(X,Y)) to perform. best subset with predictor x,x2 , ..., x10 .
(d)  Repeat (c), using forward stepwise selection and also using backwards stepwise selection. How does your answer compare to the results in (c)?
2. In this exercise, we will perform. subset selection using data set Boston. Note that the response variable is medv.  
(a)  Perform. best subset selection with three predictor. What are the best three predictors?
(b)  Perform. linear regression with the three best predictors.  Is your model significant?  How much variability can be explained by this linear model.(c)  Perform. forward and backward stepwise subset selection.  Find the models with seven predictors. Are they the same as the best subset selection?  If different, does the stepwise subset selection lose much in terms of proportion of variability explained by the model?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
