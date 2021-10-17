# MechaCar_Statistical_Analysis

## Background
AutosRUs' newest prototype, MechaCar is suffering from production troubles that are blocking the manufacturing teams progress. The production data needs to be reviewed and constructive feedback should be given based on the analysis to help the team. 

The required actions are as follows:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Deliverable 1: Linear Regression to Predict MPG

the variables/coefficents' p-values (Pr(>|t|)) are:

![del 1, 1](https://user-images.githubusercontent.com/86750935/137639737-3f41192c-92d0-49d4-80a3-3ef1babd8277.png)

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model, they have a huge impact on MPG on the MechaCar prototype. However, the spiler angle and All Wheel Drive (AWD) have random variance based on the p-values.

* Is the slope of the linear model considered to be zero? Why or why not?

desired significance level is 0.05 - 1 = 0.95 or 95%). All three of the tested coefficients are outside the 95% min significance level based on the linear model. the p-Value: 5.35e-11, there is enough information to reject our null hypothesis.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

the r-square value is 0.7149, which means that approximately 71% of all mpg predictions will be determined when using this specific model.

## Deliverable 2: Summary Statistics on Suspension Coils

Creating a summary statistics table to show:

* The suspension coil’s PSI continuous variable across all manufacturing lots
* The following PSI metrics for each lot: mean, median, variance, and standard deviation.

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
