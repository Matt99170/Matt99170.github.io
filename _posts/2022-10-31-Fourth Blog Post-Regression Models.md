# Fourth Blog Post-Regression Models

Variable selection is intended to select the “best” variables to use as predictors. We what to select the best since our aim is to explain the data in the simpliest and easiest way to reduce time and computational cost.

Some popular variable selection algorithms, that I would use to determine variables to use in a regression model are as follows, 

## Backward elimination (BE)

This is the simplest of all variable selection procedures and can be easily implemented without special
software. It usually involves, 
* Examining all the predictors in the model
* Removing the predictor that is the most insignificant
* Reestimating the model
* Stop if no more predictors are insignificant.

## Forward Selection (FS)

This just reverses the backward method. It usually involves, 
* Starting with no variables in the model
* Include the predictor that is the most significant 
* Reestimate the model
* Stop if no more significant predictors can be included.

## Stepwise forward

This uses (FS) and (BE). It usually involves,
* Performing the steps of (FS) but after each inclusion of the predictor that is the most significant and perform the steps of (BE)
* In subsequent (FS) steps, reconsider the predictors that were removed in former steps
* Stop if no more predictors can be removed or added.

## Best subset selection

This involves estimating all possible models and choose the best model according to the required criteria.

## LASSO

This involves imposing a penalty on the sum of squares or log likelihood that is equal to the absolute sum of regression coefficients.

While I am still a novice, the LASSO selection appears to have some advantages. Variable selection methods often reduce the RMSE of regression coefficients, in particular for weak or noise predictors. This shrinkage effect is quite extreme for LASSO at small sample sizes, which can result in considerably reduced RMSEs of true regression coefficients. Additionally LASSO selection tends to select more predictors than (BE). 

It should be noted that the list of variable selection algorithms listed above are not exhaustive. Further reading can be found in the following articles.

1. [Biometrical Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969114/)
2. [Biostat Teaching resource](https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf)
3. [Springer publication](https://link.springer.com/content/pdf/10.1057/jt.2009.26.pdf).




