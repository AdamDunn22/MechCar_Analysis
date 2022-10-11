# MechCar_Analysis

## Purpose
We are to analyze any manufaturing issues that are affecting the three production lots of the new prototype car. Currently we have the following variables Length, Weight, AWD, MPG, PSI, spoiler angle, and ground clearance.

## Linear Regression to Predict MPG
![Linear_Regression](https://user-images.githubusercontent.com/108701073/195098183-56ed4fb6-4201-4d81-86e8-b697c8db541b.png)

1) The car length and ground clearance are both variables that are highly likely to give data that will have a non random amount of variannce as their p-values were less than 0.05% while the other variables such as the MPG, PSI, spoiler angle andweight will have data with random amounts of variance.

2) We are able to reject the null hypothesis that the slope of the line is equal to 0 as we have a p value less than 0.05%. So we can say that since we reject the null hypothesis we can assume that the slope does not equal 0.

3) Reviewing the R-square we can see that we we would be able to predict 0.7149 of the data which is not relativley that high. Also, when we remove the less impactful variables the adjusted r-square drops to 0.674 meaning it less likely to predict the mpg of the prototype.

## Summary Statistics on Suspension Coils
### Total Summary
![total_summary](https://user-images.githubusercontent.com/108701073/195099210-de115b31-812b-4ea0-99d4-ec646824db85.png)

From the total sumamry we can see that the overall current manufacturing process is meeting the 100 pounds per square inch variance limitation.

### Lot Summary
![lot_summary](https://user-images.githubusercontent.com/108701073/195099232-3e008671-7f2c-40df-b989-bb513aa9a0fb.png)

When we break the data up into the three lots we see that lot three has a variance that exceeds the 100 pounds per square inch variance limitation.

## T-Tests on Suspension Coils

### All Lots t-test
![t_test](https://user-images.githubusercontent.com/108701073/195100537-0ccd807b-5dcb-4410-898e-c657da25cfc5.png)
We would fail to reject the null hypothesis that the sample mean may be equivalent to the population mean as the p-value is equal to 0.06028 and is greater than 0.05

### Individual Lot t-tests

1) Lot 1 has a p-value = 1 meaning that we fail to reject the null hypothesis that the sample mean may be equivalent to the population mean
![lot_one](https://user-images.githubusercontent.com/108701073/195101928-2b475483-c2f2-4034-8645-dcd12cc33930.png)

2) Lot 2 has a p-value = 0.6072 meaning that we fail to reject the null hypothesis that the sample mean may be equivalent to the population mean
![lot_two](https://user-images.githubusercontent.com/108701073/195102617-f02e53a8-2b66-47d9-9a80-2efceb2305d3.png)

3) Lot 3 has a p-value = 0.04168 meaning that we reject the null hypothesis that the sample mean may be equivalent to the population mean
![lot_three](https://user-images.githubusercontent.com/108701073/195102778-9cfd1c01-7728-48d7-8ab1-f5d2044d1510.png)


## Study Design: MechaCar vs Competition
