---
layout: single
title: "Data Visualization"
excerpt: " "
header:
  overlay_image: /assets/images/unsplash6.jpg
  #teaser: /assets/images/dataviz.jpg
author_profile: true  

feature_row1-1:
  - image_path: assets/images/Collegetuition.png
    alt: "Clusterisation results based on Conversion Rates"
    title: "Target Audience for Starbucks Rewards App"
    text: "In this project, I analyzed the customer behavior in the Starbucks Rewards Mobile App. After signing up for the app, customers receive promotions every few days. The task was to identify which customers are influenced by promotional offers the most and what types of offers to send them in order to maximize the revenue. I used PCA and K-Means clustering to arrive at 3 customer segments (Disinterested, BOGO, Discount) based on Average Conversion Rates and explored their demographic profiles and shopping habits."
    url: "https://github.com/smakeneni/TidyTuesday/blob/master/College_tuition_03_011/Tuition_Salary.Rmd"
    btn_label: "Code"
    btn_class: "btn--primary"
    url2: "https://smakeneni.shinyapps.io/Tuition_Salary/"
    btn_label2: "Dashboard"
    btn_class: "btn--primary"
    tags: 
        - Marketing
        - Segmentation
        - k-means clustering
        
feature_row2:
  - image_path: /assets/images/anim.gif
    title: "Broadway Incomes"
    text: " For this project, I analyzed the data from broadway incomes to created animated plots"
    url: "https://github.com/smakeneni/TidyTuesday/blob/master/Broadway/Animatedplot.R"
    btn_label: "Code"
    btn_class: "btn--primary"
    url2: "https://github.com/smakeneni/TidyTuesday/blob/master/Broadway/Animatedplot.R"
    btn_label2: "Visual"
    btn_class: "btn--primary" 
    tags:
      - gganimate, ggplot, tidyverse
    
feature_row3:
  - image_path: /assets/images/College_tuition_maps.png
    title: "BrainInjury Statistics"
    text: " For this project, I analyzed the data from broadway incomes to created animated plots"
    url: "https://github.com/smakeneni/TidyTuesday/blob/master/BrainInjury_03_24/Braininjury_plotly.R"
    btn_label: "Code"
    btn_class: "btn--primary"
    url2: "https://github.com/smakeneni/TidyTuesday/blob/master/Broadway/Animatedplot.R"
    btn_label2: "Visual"
    btn_class: "btn--primary" 
    tags:
      - plotly, tidyverse

#sidebar:
 # - title: "Role"
 #   text: "Designer, Front-End Developer"
 # - title: "Responsibilities"
 #   text: "Reuters try PR stupid commenters should isn't a business model"
--- 

Each week, I take part in a social project called #TidyTuesday challenge hosted by the R for data science community. They post a raw data set and allow the participants to explore the data and summarize it into meaningful data visualizations. This challenge provides an opportunity to practice data wrangling and visualizations skills as well as to connect with the #rstats community. Most of the visualiations you will see below were done as a part of this challenge.
{: .text-justify}

**Skills used for these visualizations:  R shiny, ggplot2, plotly, tidyverse, flexdashboard**
{: .notice--info}

{% include feature_row id="feature_row1-1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
