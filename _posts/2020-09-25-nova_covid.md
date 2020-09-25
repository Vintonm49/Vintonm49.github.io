---
layout: post
title: "COVID-19 in Nothern Virginia"
date: "2020-09-25"
output: 
  html_document:
    keep_md: true
---



### COVID-19 Cases in Northern Virginia





Northern Virginia is populous region of Virginia just outside of D.C. and includes the counties of Fairfax, Alexandria, Arlington, Loudoun, and Prince William.  The population is about 2.36 million people, which accounts for almost 28% of the population of the state.  This analysis focuses on the data related to the COVID-19 pandemic, specifically in Northern Virginia.  The goal is to highlight trends in the region and discover insights.

$~$

We use data from the [Virginia Department of Health](https://www.vdh.virginia.gov/coronavirus/covid-19-in-virginia/) .  The source data was downloaded from the Virginia Department of Health website on September 20, 2020. 

$~$




### Cases and Hospitalizations

These charts show the 5-day moving average for both reported cases and hospitalizations.  Both show a significant drop from the early months of the pandemic and a leveling off since July. 

![](../assets/images/unnamed-chunk-3-1.png)<!-- -->![](../assets/images/unnamed-chunk-3-2.png)<!-- -->

### Active Cases and Hospitalizations



How many people in Northern Virginia *currently have* COVID-19?  We use the term "Active" to refer to cases from the past 14 days.  The duration of illness or infection from COVID-19 is up to 14 days, for most people.  For a given day, the "Active Cases" metric is the total number of reported cases for the past 14 days.  This allows us to focus on the current spread of the disease in Nothern Virginia, vice cases that have long since resolved. It can also give you a sense of the likelihood of interacting with an individual with COVID-19.

For example, there were 3106 active cases on September 20, 2020.  This means in an area with a population of over 2.3 million, a total of 3106 people were positive for COVID-19 on that day.  Of course, this does not account for people who have COVID-19 but have not been tested, including a potentially substantial number of asymptomatic individuals.

![](../assets/images/unnamed-chunk-5-1.png)<!-- -->

$~$

The active hospitalizations metric is similar in that it captures the total number of hospitalizations in the past 14 days for each day. 

![](../assets/images/unnamed-chunk-6-1.png)<!-- -->

$~$

### Data By County 

Not all counties in Northern Virginia are the same.  This chart shows the 5-day moving average of cases by county in Northern Virginia.  







![](../assets/images/unnamed-chunk-8-1.png)<!-- -->

$~$

However, not all of the counties in Northern Virginia are the same size in population.  This chart shows the number of cases in each county, per million in population.  When compared to the previous chart, you see that while Fairfax County generally has the most new cases, other counties generally have higher case rates relative to population size.  

![](../assets/images/unnamed-chunk-9-1.png)<!-- -->

