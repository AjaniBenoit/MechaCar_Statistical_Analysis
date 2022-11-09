# MechaCar_Statistical_Analysis

Statistical Analysis with R  

## Project Overview

Using R and R studio mechacar_mpg.csv and suspension_coil.csv were analyzed. 

## Linear Regression to Predict MPG 

The mechcar_mpg.csv dataset contains mpg test results for 50 prototype Mecha Cars. A linear regression model was created using the R language in R Studio. 

### Results 

R was used to calculate the coefficients for MPG,  vehicle_length, vehicle_weight, spoiler_angle, ground_clearance, and AWD. 

![fig1.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig1.png)

MPG is statistically significant with the coefficient of .00 being less than .05. 
Vehicle_length is statistically significant with the coefficient of .00 being less than .05. 
Vehicle_weight is not statistically significant with a coefficient of .08 being greater than .05. 
Spolier_angle is not statistically significant with a coefficient of .31 being greater than .05. 
Ground_clearance is statistically significant with a coefficient of .00 being less than .05 
AWD is not statistically significant with a coefficient of .19 being greater than .05. 

![fig2.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig2.png)

Vehicle_length and ground_clearance variables are statistically significant and has correlation with MPG. 

The R-squared of value of 0.7149 represents a strong correlation for the dataset. The linear model predicts the MPG of MechCar Prototype. 

## Summary Statistics on Suspension Coil 

### Manufacturing Lot Summary 
![fig3.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig3.png)

### Manufacturing Lot Number Summary 
![fig4.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig4.png)

The design specifications for the MechaCar suspension coil states that variance of the suspension coil mut not exceed 100 pounds per square inches. Lot 1 and Lot 2 meet the requirements with variances of .98 and 7.5 pounds per square inches. Lot 3 does not meet the required specfications with a variance of 170.3 pounds per square inches. 

## T-Test on Suspension Coils

### T-Test all Manufacturing lots against the Population Mean

![fig5.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig5.png)

The p-value of 1 is greater than the 0.05 and is not statistically significant. The null hypothesis cannot be rejected. 


### T-Test Lot 1

![fig6.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig6.png)

The p-value is lower than 0.05 and is statistically significant. The null hypothesis can be rejected. 

### T-Test Lot 2 

![fig7.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig7.png)

The p-value is lower than 0.05 and statistically significant. The null hypothesis can be rejected. 

#### T-Test Lot 3 

![fig8.png](https://github.com/AjaniBenoit/MechaCar_Statistical_Analysis/blob/main/images/fig8.png)

The p-value is higher than 0.05 and is not statistically significant. The null hypothesis cannot be rejected.

## Study Design: MechaCar vs Competition 

When comparing MechaCar to competitors, we can identify other metrics that could interest consumers, such as horsepower, acceleration time, highway and city fuel efficiency. 

Our null hypothesis: Performance measures of MechaCar prototype are similar to the performance measures of competition. 
 
Our Alternative hypothesis: Performance measures of MechaCar prototype are significantly different from the performance measure of competition 

Using multiple linear regressions would show how the variables of horsepower, acceleration time. Highway and city fuel efficiency compare to their competitors. 

A random sample of Mechacar’s competitors would be collected. The sample would need to include performance measures related to horsepower, acceleration and fuel efficiency. 
