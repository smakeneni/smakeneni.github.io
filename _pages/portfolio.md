---
layout: single
title: " "
permalink: /portfolio/
header:
    overlay_image: /assets/images/unsplash6.jpg
    caption: "Photo by Unsplash"
author_profile: true
classes: wide

feature_row1:
  - image_path: assets/images/posts/starbucks-cluster-conversion-rates.png
    alt: "Clusterisation results based on Conversion Rates"
    title: "Target Audience for Starbucks Rewards App"
    text: "In this project, I analyzed the customer behavior in the Starbucks Rewards Mobile App. After signing up for the app, customers receive promotions every few days. The task was to identify which customers are influenced by promotional offers the most and what types of offers to send them in order to maximize the revenue. I used PCA and K-Means clustering to arrive at 3 customer segments (Disinterested, BOGO, Discount) based on Average Conversion Rates and explored their demographic profiles and shopping habits."
    url: "https://github.com/k-bosko/Starbucks_rewards"
    btn_label: "Code + Presentation"
    btn_class: "btn--primary"
    url2: "/Starbucks-Rewards-Program/"
    btn_label2: "Technical Report"
    btn_class: "btn--primary"
    tags: 
        - Marketing
        - Segmentation
        - k-means clustering

#feature_row1:
 # - image_path: /assets/images/dataviz.jpg
 #   portfolio_caption: "Photo Credit"
 #   title: "Data Visualization"
 #   url: "portfolio/dataviz"
 #   btn_label: "Explore"
 #   btn_class: "btn--primary"
 #   url2: "https://smakeneni.github.io/portfolio/dataviz/"
 #   btn_label2: "Testing"
 #   btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/dataviz.jpg
    title: "Statistics"
    url: #"/portfolio/machinelearning"
    btn_label: "Read More"
    btn_class: "btn--primary"
    btn_size: "btn--small"

feature_row3:
  - image_path: /assets/images/dataviz.jpg
    title: "Machine Learning"
    url: #"/portfolio/Statistics/"
    btn_label: "Read More"
    btn_class: "btn--primary"   
    btn_size: "btn--small"

feature_row4:
  - image_path: /assets/images/dataviz.jpg
    title: "Other"
    url: #"/portfolio/Statistics/"
    btn_label: "Read More"
    btn_class: "btn--primary"   
   
---
## PORTFOLIO 
{: .text-center}
These are projects that I have done over the last year which are representative of my skills and interests. I have divided them into three categories as seen below. For each individual project, I have included a brief summary, detailed report, and  link to the code. If you have further questions, please feel leave a comment or contact me

{% include feature_row id="feature_row1" type="center" %}
{% include feature_row id="feature_row2" type="center" %}
{% include feature_row id="feature_row3" type="center" %}
{% include feature_row id="feature_row4" type="center" %}
