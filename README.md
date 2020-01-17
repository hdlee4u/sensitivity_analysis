# sensitivity_analysis
sensitivity analysis on linear regression and logistic regression

< simple procedure >
- (1) after fitting linear regression or logistic regression model
- (2) select all X variables from an observation (1 row)
- (3) then, predict y value by using only 1 variable's existing value and setting '0' for other variables
      : ie. for loop iteration of all variables one by one
- (4) compare predicted y value by variables

* used abalone.txt open dataset as an example
