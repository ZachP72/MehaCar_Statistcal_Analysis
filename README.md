# MehaCar_Statistcal_Analysis

## Linear Regression to Predict MPG
1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    Ground clearance and vehicle length are the two variables that provided the most amount of random variance. On the otherside, you have vehicle weight, spoiler angle, and AWD which had a non-random amount of variance. 
2. Is the slope of the linear model considered to be zero? Why or why not?
    Because our p-value is less than 0.05 we know thatt the slope is not zero. 
3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
    While there are a few other factors that are not in our dataset that contribute to the MPG variability, we know t hat our R-squared value is 71% which means the model will correctly predict MPG values 71% of the time.

## Summary Statics on Suspension Coils
1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
   Of the three lots, Lot 1 and 2 both are within design specifications while having a similar mean and median. Lot 3 on the other hand go over the manufacture specs and has a lot of variance. 

## T-Tests on Suspension Coils
The information below shows us that in Lot 3 there must have been a production cycle error. I would recommend checking for system failures and the suspension coils to be inspected or removed fro not meeting the quality criteria.
### Lot Numbers
![image](https://user-images.githubusercontent.com/95777297/162599680-79cbf070-0a5e-45f6-94f5-b637d4ee58fa.png)

![image](https://user-images.githubusercontent.com/95777297/162599675-af631e9f-e82e-44e4-91c3-3600b950ed5f.png)

![image](https://user-images.githubusercontent.com/95777297/162599686-80db2e85-e537-4937-8368-d2bfe853e1db.png)

![image](https://user-images.githubusercontent.com/95777297/162599688-2f176b23-8ccf-4cd8-a06d-8d84254a0d3d.png)


## Study Design: MechaCar vs Competition
Three of the most important factors consumers make while looking for a car is, price, MPG, horsepower. With all this data we could compare our MechaCar to other various vehicles to see where it would stand amongst them. I could make a null hypothesis stating that it is exactly the same as some of our competition or an alternative hypothesis would be the exact opposite. We would need to collect data from all the other competitor vehicles we want to compare against and use our t-test to compare the population of all types of competitor vehicles. 

