# MechaCar_Statistical_Analysis
R Statistics

## Linear Regression to Predict MPG
### Deliverable 1: Statistical Summary using Multiple Linear Regression

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/e0ef053b98612dabf33f75cb71a3ba00926a43a3/resources/deliverable1.png)

#### **Multiple Linear Regression** is a statiscal tool that uses multiple variables to describe observed variations in the dependent variable. Using this tool, the *R-squared* value shows 71.5% of variations can be explained by the model or formula used. The *p-value* is *5.35e-11*. This means that **vehicle lenght** and **ground clearance** are statistically significant. In other words, these coefficients provide non-random amount of variance to the mpg values in the data set.

#### The slope of the linear model cannot be considered to be *0* because there is statiscallly significant relationship between the predictor/model and the variables. The slope is equal to *-1.040e+02* While this value is close to *0*, looking at the *t-value* of *-6.559* and a *p-value* of *5.35e-11*, these values supports the idea that there is strong association between the model and the variables.

#### In conclusion, this linear model effectively predicts mpg of MechaCar prototypes. Understanding the statistical analysis used, *R-squared* value is 71.5% , there is a higher *t-value* and a lower *p-value*, therefore the predictor linear model is significant.

# Summary Statistics on Suspension Coils
### Deliverable 2: Create Visualizations for the Trip Analysis

<p align="center">
   Total Summary
</p>

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/56348a2736f74201e70b438dcd0d6a7f3cecc5d9/resources/total_summary.png)

<p align="center">
  Lot Summary
</p>

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/56348a2736f74201e70b438dcd0d6a7f3cecc5d9/resources/lot_summary.png)

### Analysis: 
#### For the total summary, the variance is at *62.3 psi*, which is under *100 psi*. This means that generally, the MechaCar prototypes meets the criteria design specifications for suspension coils. However, looking at each individually, Lot 3 has exceeded the *100 psi* design specification. In other words, some vehicles manufactured have not met the standard for suspension coils.

## T-Tests on Suspension Coils

<p align="center">
  T-test for Total Summary 
</p>

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/ad224f220b514a72c0ede624330cf970eb0b2daa/resources/overall_t_test.png)

<p align="center">
  T-test for Lot 1
</p>

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/ad224f220b514a72c0ede624330cf970eb0b2daa/resources/lot1_ttest.png)

<p align="center">
  T-test for Lot 2
</p>

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/ad224f220b514a72c0ede624330cf970eb0b2daa/resources/lot2_ttest.png)

<p align="center">
  T-test for Lot 3
</p>

![This is an image](https://github.com/gmgarin/MechaCar_Statistical_Analysis/blob/ad224f220b514a72c0ede624330cf970eb0b2daa/resources/lot3_ttest.png)

### Analysis
#### The *T-test* accross all manufacturing lot indicates a score of *-1.89* and a *p-value* of *0.06*. Assuming the 0.05 as the level of significance, the calculated *p-value* is higher. Therefore, we fail to reject the null hypothesis, and the two means are statistically similar. In addition, all lots but lot 3, have higher *p-value* than the level of significance. Lot 3 has a *p-value* of *0.4*, therefore, the null hypothesis is rejected, and the two means are statiscally different. This findings supports the fact that Lot 3 average have exceeded design criteria for suspension coils.


## Study Design: MechaCar vs Competition.
### Deliverable 4: Design a Study Comparing the MechaCar to the Competition 

#### Car manufacturing industry is constantly changing because of many reasons. Car manufacturers have to adapt to these changes to stay in the market. On the other hand, consumers have a wide range of options when it comes to car buying. With these great many options, it all boils down to consumer prerences and budget. MecharCar will have the chance in the car manufacturing industry if it will pride itself in producing reliable and safe cars.

### Reliability and Safety
#### Car's reliability is defined how vehicles have held up and the odds that an owner could be incovenienced by problems and repairs, according to [Consumer Reports](https://www.consumerreports.org/cars-car-reliability-guide/). The [National Highway Traffic Safety Administration’s](https://www.nhtsa.gov/ratings) New Car Assessment Program (NCAP) created the 5-Star Safety Ratings Program to provide consumers with information about the crash protection and rollover safety of new vehicles beyond what is required by Federal law. One star is the lowest rating; five stars is the highest. More stars equal safer cars.

### Null and Alternative Hypotheses
#### *Null Hypothesis*: MechaCar prototypes' average reliabilty and safety ratings are similar competitor's vehicles.
#### *Alternative Hypothesis*: MechaCar prototypes' average reliabilty and safety ratings are nnot similar competitor's vehicles.

### Statistical Analysis Tool to be Used
#### For this statiscal study, I would like to use **Two-Way ANOVA* since I would be testing multiple variables.

### Data Needed
#### The data that will be collected will be coming from [Consumer Reports](https://www.consumerreports.org/cars-car-reliability-guide/) reliability ratings data and [National Highway Traffic Safety Administration](https://www.nhtsa.gov/ratings) safety ratings data.


