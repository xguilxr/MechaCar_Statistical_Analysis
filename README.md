# MechaCar_Statistical_Analysis

## Linear Regression to predict MPG

From a dataset that contained the MPG test results for 50 MechaCar design prototypes, a linear regression model was made to predict MPG defined by several factors such as vehicle length, weight, etc. 

<img width="444" alt="LR" src="https://user-images.githubusercontent.com/85911181/135763650-7e607e9a-60fa-48e3-b8ba-6b4d60145e63.PNG">
<img width="444" alt="SMRY" src="https://user-images.githubusercontent.com/85911181/135763941-8945d1a0-e661-4282-b6c2-53e5fd370269.PNG">

From the linear regression results presented in the previous images, we get results of 71% accuracy in models with a p-value of 5.35*10^-11 which satisfies the significance value of 0.05. The low p-value in this case helps prove that the slope of the line is not 0. 

## Summary Statistics on Suspension Coils

It is important to analyze if the suspension coil PSI reading is ocnsistent accross all productions lots. Two summary tables have been created from the data: the first one details production accross all lots. The second one analyzes the three lots individually. 

<img width="164" alt="TOTAL_SUMMARY" src="https://user-images.githubusercontent.com/85911181/135764839-1c0ab4e7-c3fe-4e29-8a30-79c8f8ea366c.PNG">
<img width="235" alt="LOT_SUMMARY" src="https://user-images.githubusercontent.com/85911181/135764842-740ee174-e16d-47b3-a420-bc697ab05f26.PNG">

## T-Test on Suspension Coils

T-test analyses were performed to determine if PSI readings from suspension coils globally or indifivually are different from the population of 1,500 PSI.

<img width="232" alt="T-test-1" src="https://user-images.githubusercontent.com/85911181/135765235-6bc23676-557b-4ec2-aed5-fb871c503f90.PNG">
<img width="304" alt="T-test-lots" src="https://user-images.githubusercontent.com/85911181/135765236-7b8ed460-de20-4d35-a8ec-1e0c1438fdad.PNG">


## Study Design: MechaCar vs Competition

After analyzing internally the production process, it is important to externalize the analysis with MechaCar's competition.

### Metrics to be tested

It is important to decide which factors will be analized and why. For this study the metrics that wlil be tested would be cost, location (city), and MPG (highway and inside the city).

### Hypotheses

Null Hypothesis (Ho): MechaCars have no difference in pricing compared to its competitors, and have no differences in fuel efficiency in comparison to the competition.

Alternative Hypothesis (Ha): MechaCars have different pricing in comparison to competitors and have differences in fuel efficiency in comparison to the competition.

### Statistical Tests to be Performed

In this study we will use a two sample t-test to compare the averages from the two populations. From there individual one-tailed t-tests will be performed to analyze which populations have greater means. 

### Data Requirements

In order to carry out these tests,it will be necessary to collect data from MechaCar and its competitors. In case this is not completely possible, it is necessary to have the following: 
  - Mean of the samples
  - Standar deviation of samples
  - Number of instances recorded





