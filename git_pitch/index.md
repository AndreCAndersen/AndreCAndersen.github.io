---
title       : BMI Calculator
subtitle    : BMI Calculation with grahical interface
author      : Andre Christoffer Andersen
job         : Coursera Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Presentation Content
The following presentation will go through the following parts:

1. Definition of BMI
2. Example Calculation
3. Graphical Representation

---

## Definition of BMI

BMI as defined by Wikipedia:

* "The body mass index (BMI) or Quetelet index is a value derived from the mass (weight) and height of an individual. The BMI is defined as the body mass divided by the square of the body height, and is universally expressed in units of kg/m2, resulting from mass in kilograms and height in metres."

BMI as defined by NHLBI:

* "Body mass index (BMI) is a measure of body fat based on height and weight that applies to adult men and women.""

---

## Example Calculation


```r
cm <- 180
kg <- 80
bmi <- kg / cm^2 * 10000
print(bmi)
```

```
## [1] 24.69136
```

A person of hight 180 cm and weight 80 kg would gets a BMI of 24.7. This is within 'normal' paramters; however, this person doesn't easely know the bounds of how high or low he can get before he should take remediating action. A graphical representation could help with this.

---

## Graphical Representation

<iframe src="https://andersen.shinyapps.io/bmi_calc/"></iframe>
If the above app doesn't work please visit it directly <a href="https://andersen.shinyapps.io/bmi_calc/">here</a>.

