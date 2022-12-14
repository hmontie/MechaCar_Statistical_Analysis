# MechaCar_Statistical_Analysis








## Deliverable 1: Linear Regression to Predict MPG

![line regression ](https://user-images.githubusercontent.com/107443962/194187359-fc5e31dd-44f1-4957-b081-dfeaa6e2d10a.png)

In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results, ground clearance and mpg (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. When an intercept is statistically significant, it means there are other variables and factors that contribute to the variation in quarter-mile time that have not been included in our model. These variables may or may not be within our dataset and may still need to be collected or observed.
From our linear regression model, the r-squared value is 0.68, which means that roughly 68% of all predictions will be correct when using this linear model.

In addition, the p-value of our linear regression analysis is p-value: 6.712e-11, which is much smaller than our assumed significance level of 0.05%. Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.


## Deliverable 2: Create Visualizations for the Trip Analysis

![Total Summary](https://user-images.githubusercontent.com/107443962/194191214-316dede1-2fab-4bfe-9a90-40f5d4cf102a.png)

![Lot](https://user-images.githubusercontent.com/107443962/194191223-b5ccf00a-757b-46e9-84ed-423c258d97d2.png)

Using our visualization in combination with our calculated p-value and r-squared value, we have determined that there is a significant relationship between ground_clearance and mpg.

R-squared: 0.7119, Adjusted R-squared: 0.6791 suggest a strong correlation and the P-value significantly lower than 0.05, suggest strong correlation and prediction as expalined in more detail in Deliverable 1.

## Deliverable 3: T-Tests on Suspension Coils

![T-Test](https://user-images.githubusercontent.com/107443962/194191243-53ed1aa8-1d1c-481b-993a-6faf53cbca9d.png)

PSi distribution is normal since P-value is way less than 0.05

Our significance level was the common 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.

## Deliverable 4: Design a Study Comparing the MechaCar to the Competition

What metric or metrics are you going to test?

I would test vehicle weight with the safety rating. I belive that safety would be a competitive advantage.

What is the null hypothesis or alternative hypothesis?

Null hypothesis represents the scenario that our results can be explained by random chance without any outside influence. In contrast, our alternate hypothesis represents any other scenario that our results could yield.

H0 : PH = 0.1 (High) Ha : PH ??? 0.1 (High)

Where PH represents the probability of safety rating to vehicle weight.

What statistical test would you use to test the hypothesis? And why?

I would use two-tailed hypotheses to describe both sides of the distribution and use descriptions such as "equal to" or "not equal to."

If my hypotheses and statistical test are both two-tailed, use the statistical test p-value as is. If my hypotheses are one-tailed, but our statistical test is two-tailed, I would divide the statistical test p-value by 2.

Than If calculated p-value is smaller than significance level, I would state that there is sufficient statistical evidence that null hypothesis is not true, and therefore reject null hypothesis. Alternatively, if calculated p-value is larger than significance level, I would state that I do not have sufficient evidence to reject null hypothesis, and therefore fail to reject null hypothesis.

What data is needed to run the statistical test?

I need data that will be correct and represent the true real-world results. A direct relationship between weight and accidents would be a first step. To limit type I error (reject the null hypothesis when it is actually true) I would decrease the P to 0.1 as mentioned above and in order to limit type 2 error (fail to reject the null hypothesis when it is actually false) I would add additional measurments such as terrain, weather or maintenance.


