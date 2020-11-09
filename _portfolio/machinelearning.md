---
layout: single
title: " "
excerpt: " "
header:
  overlay_image: /assets/images/unsplash6.jpg
  #teaser: /assets/images/dataviz.jpg
author_profile: true  
classes: wide 

--- 
<style>
.myDiv {  
  text-align: justify;
  font-size: 15px;
  font-family: Arial, Helvetica, sans-serif; 
  overflow: hidden;
}

p.clear {
  clear: both;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  font-size: 15px;
  font-family: Arial, Helvetica, sans-serif;  
} 

li{
  font-size: 20px;
  font-family: Arial, Helvetica, sans-serif; 
 }
</style>  

**Home prices in Ames,Iowa**
<p>
<img src="/assets/images/Housepricesimage.png" style="float:left;width:200px;height:200px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"><div class="myDiv">For this project, I analyzed a dataset from kaggle, which consists of 79 explanatory variables that describe various features of residential homes in Ames,Iowa. The challenge is to identify which features affect sale prices and predict home prices of each of these homes. I used Gradient Boost and XGBM algorithms for this.</div></p>

<div class="myDiv"><strong>Packages</strong>: tidyverse, ggplot2, caret, gbm, xgboost</div>

[Report](/portfolio/Housingprices.html){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/Housingprices/blob/master/Housingprices.Rmd){: .btn .btn--info .btn--small}
