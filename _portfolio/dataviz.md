---
layout: single
title: " "
excerpt: " "
header:
  overlay_image: /assets/images/unsplash6.jpg
  #teaser: /assets/images/dataviz.jpg
author_profile: true  
classes: wide 

#sidebar:
 # - title: "Role"
 #   text: "Designer, Front-End Developer"
 # - title: "Responsibilities"
 #   text: "Reuters try PR stupid commenters should isn't a business model"
--- 

Each week, I take part in a social project called #TidyTuesday challenge hosted by the R for data science community. They post a raw data set and allow the participants to explore the data and summarize it into meaningful data visualizations. This challenge provides an opportunity to practice data wrangling and visualizations skills as well as to connect with the #rstats community. Most of the visualiations you will see below were done as a part of this challenge.
{: .text-justify}

**Tools and Packages used:**  R, tidyverse, ggplot2, plotly, R shiny, gganimate, flexdashboard
{: .notice--info}

**College tuition vs. Salary Potential**

![image-left](/assets/images/Collegetuition.png){: .align-left}For this project, I analyzed tuition and salary data to explore correlation between tuition costs and career pay. I used R shiny flexdashboard to create an interactive dashboard that allows the users to explore tuition fees and salary potential by state in the US

[Dashboard](https://smakeneni.shinyapps.io/Tuition_Salary/){: .btn .btn--info .btn--small}  [Code](https://github.com/smakeneni/TidyTuesday/blob/master/College_tuition_03_011/Tuition_Salary.Rmd){: .btn .btn--info .btn--small}

**Broadway Incomes**

![image-left](/assets/images/broadway.gif){: .align-left}For this project, I analyzed broadway incomes data and aggregated weekly gross incomes per year by show to visualize top 10 shows every year from 2010-2019. I created an animated plot using the gganimate package in R.

[View visualization](/portfolio/Dataviz_broadway.html){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/TidyTuesday/blob/master/Broadway/Animatedplot.R){: .btn .btn--info.btn--small}

**Brain Injury Statistics**

![image-left](/assets/images/College_tuition_maps.png){: .align-left}For this project, I analyzed traumatic brain injuries data in the US between 2007-2014 to explore the leading cause for injuries and deaths. I used plotly in R to generate this plot.

[View visualization](https://github.com/smakeneni/TidyTuesday/blob/master/BrainInjury_03_24/Braininjury_plotly.R){: .btn .btn--info .btn--small}  [Code](https://github.com/smakeneni/TidyTuesday/blob/master/BrainInjury_03_24/Braininjury_plotly.R){: .btn .btn--info .btn--small} 
