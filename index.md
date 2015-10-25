---
title       : Why my shiny app is important
subtitle    : And why you need to view it
author      : Tim F.
job         : Coursera student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class #id 

## The Problem
1. Basketball is a sport played for fun
2. But if you are bad at basketball it can be embarrassing to play with friends
3. When will I be good enough to play basketball in public?


---

## The Solution
Predict when I will be good enough using a model fitted to historical data. 

<iframe width='100%' height='300' src='https://en.wikipedia.org/wiki/Predictive_modelling' frameborder='0'></iframe>

---

## The Data
Luckily I have built up a small record of my basketball accuracy over time. Each data point shows how many shots I sunk (out of ten), a fixed distance from the hoop. There are 79 recorded attempts.
<img src="assets/fig/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />
This data can be used to predict when I will be good at basketball!

---

## The Shiny App

Please go here to view my app:
https://tim-fan.shinyapps.io/basketball-accuracy

The app will allow you to
* View the data, plotted either by date or by number of attempts
* Fit a polynomial to the data to predict when I will sink 10/10 shots



Extras:
* Source for the shiny app:

  https://github.com/tim-fan/datasciencecoursera/tree/master/dataProducts/courseProject1/basketball-accuracy

* Source for this presentation: 

  https://github.com/tim-fan/slidifyPitch/tree/gh-pages



