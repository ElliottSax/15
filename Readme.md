## Background ##

A few weeks after starting his new role, Jeremy is approached by upper management about a special project. 
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing
team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production
data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG ##

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle weight, spoiler angle and all wheel drive provided a non-random amount of variance. 

Is the slope of the linear model considered to be zero? Why or why not?

The slope is not considered to be zero. The p-value is less than 0.05 and the null hypothesis can be rejected.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

No. It's somewhat reliable, it's wrong a third of the time. The R-squared value is 71%.

## Summary Statistics on Suspension Coils ##

The suspension coils were tested to determine if the manufacturing process is consistent across production lots.

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Yes. Lots 1 and 2 are within specifications and have the same mean and median. 
Lot 3 has the most variance and exceeds specifications.

## T-Tests on Suspension Coils ##
For lot 1, the p value is 1.568e-11 which is greater than 0.05 and is therfore not significant and the null hypothesis can be accepted. 
The p value is 1 which is greater than 0.05 and is not significant and the null hypothesis can be accepted.

For lot 2, The p value is 0.0005911 which is less than 0.05 and is therfore significant so the null hypothesis can be rejected.

For lot 3, The p value is 0.1589 which is greater than 0.05 and is therfore not significant so the null hypothesis can be accepted.

## Study Design: MechaCar vs Competition ##

Perhaps the most important metrics would be of interest to a consumer are cost, fuel efficiency and maintenance costs.
Right now, fuel efficiency is especially important, so we would test fuel efficiency.

The null hypothesis would be certain changes in the design make no improvement in fuel efficiency.
The alternative hypothesis would be that changes do make an improvement in fuel efficiency.

The data needed for the statistical test would be a large dataset of the fuel efficiency of cars with the changes
to improve efficiency and another without.


