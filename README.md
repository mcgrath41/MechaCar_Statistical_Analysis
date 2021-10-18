# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
As seen in the screen shot below, the ground_clearance and vehicle_length provided non-random variance to mpg. The vehicle_weight provided a variance that is not significant. The slope of the linear model is not considered to be zero because the p-value of the hypothesis test was 5.35e-11. The r-squared value is 0.7149, meaning that the multiple linear regression model does an adequate job of predicting the mpg correctly (71% of the time). There are likely other more impactul variables and factors not captured in the dataset that contribute to the mpg variability.  

![](/Resources/Deliverable1.png)

## Summary Statistics on Suspension Coils
As evidenced in the screen shots below, Lot 1 & Lot 2 are both within design specifications and have the same mean & median values. Lot 3, however, has far more variance with a calculated value of ~170 that exceeds manufacturing specs. If all three lots are combined and summarized on a total basis, the overall calculated variance is within specifications (~62).  

![](/Resources/Deliverable2a.png)

![](/Resources/Deliverable2b.png)

## T-Tests on Suspension Coils
As seen in the screen shot of the one-sample t-tests below, Lot 1 & Lot 2 PSI values are statistically different from the mean of the population. The p-value of Lot 3, however, is 0.04168, which is below the signficance level. This suggests that the Lot 3 mean suspension coil PSI is statistically different from the population mean. 

![](/Resources/Deliverable3.png)
