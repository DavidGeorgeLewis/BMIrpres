BMI Presentation
========================================================
author: David Lewis
date: Sat Oct 11 16:58:16 2014

=====================

## Obesity is a cause of health problems


<img alt="Are Fit People Happier?" src="http://media.carbonated.tv/81550_story__fit-people-happier-635x370.jpg" style="width: 100%; height: auto;" class="span9 zerolr imgLiquid imgLiquid_error">

***

- Hypertension  
- Dyslipidemia   
- Type 2 diabetes   
- Coronary heart disease   
- Stroke   
- Gallbladder disease    
- Osteoarthritis     
- Sleep apnea and respiratory problems     
- At least 10 cancers

=========

## Obesity is increasing 

<img class="irc_mi" style="margin-top: 0px;" src="http://fashion-times.com/wp-content/uploads/2013/11/obesity-statistics.jpg" width="582" height="293">

***

- Obesity is increasing globally    
- Obesity is now a bigger cause of bad health than malnutrition   
- In the USA 36% of the population are obese (2010)

====

## The BMI app enables people to monitor their weight

The BMI Index is calculated by weight (kgs) divided by height squared in (meters) 

So if somebody has a height of 1.8 and a weight of 89 the BMI is 27.5



```r
diabetesRisk <- function(height,weight)  round(weight/height^2,1)
diabetesRisk(1.80,89)
```

```
[1] 27.5
```


[Click for BMI app](https://davidglewis.shinyapps.io/BMI-app/)

=====

## The BMI Index 

<img style="-webkit-user-select: none; cursor: zoom-in;" src="http://www.metric.org.uk/sites/default/files/images/BMI_chart.GIF" width="573" height="500">

***

- Underweight < 18.5
- Normal 18.5 to 25
- Overweight 25 to 30
- Obese 30 to 35
- Clinically obese > 35
