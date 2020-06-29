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
  
 .myDiv{  
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

<div class="myDiv">
  Each week, I participate in a social project called <strong>#TidyTuesday</strong> hosted by <ahref="https://www.rfordatasci.com/">R4DS</a> community. They provide a raw dataset with the goal of creating meaningful data visualizations. The project allows the pariticipants to practice data wrangling and data visualization skills and connect with the greater #rstats community. Below are some featured visualizations that I generated as part of this project.</div>
&nbsp;

**College Tuition**      
<p>
<img src="/assets/images/Collegetuition.png" style="float:left;width:320px;height:160px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"> <div class="myDiv">For this visualization project, I analyzed college tuition and pay data for 2018 across the US. I used <strong>R shiny flexdashboard</strong> to create an interactive dashboard that allows the users to explore the correlation between college tuition and early career incomes by state.</div></p>  
<p class="clear"> </p>
[View visualization](https://smakeneni.shinyapps.io/Tuition_Salary/){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/TidyTuesday/blob/master/College_tuition_03_011/Tuition_Salary.Rmd){: .btn .btn--info.btn--small}

**Broadway Incomes**          
<p>
<img src="/assets/images/Broadway_teaser.gif" style="float:left;width:320px;height:160px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"> <div class="myDiv"> For this project, I analyzed broadway incomes data and aggregated weekly gross incomes per year by show to visualize top 10 shows every year from 2010-2019. I created an animated plot using the <strong>gganimate</strong> package in R.</div></p>
<p class="clear"></p>
[View visualization](/portfolio/Dataviz_broadway.html){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/TidyTuesday/blob/master/Broadway/Animatedplot.R){: .btn .btn--info.btn--small}

**Brain Injury Statistics**            
<p>
<img src="/assets/images/BrainInjury_teaser.png" style="float:left;width:320px;height:160px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"> <div class="myDiv"> I analyzed brain injury data from 2006-2014 and created an interactive plot using <strong>plotly</strong> that summarizes the statistics for traumatic brain injuries in the United States.</div></p>  
<p class="clear"></p>  
[View visualization](/portfolio/braininjury_dashboard.html){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/TidyTuesday/blob/master/BrainInjury_03_24/barplots_braininjury.R){: .btn .btn--info.btn--small}

**Tracking Caribou**
<p>
<img src="/assets/images/Caribou_migration.gif" style="float:left;width:320px;height:160px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"> <div class="myDiv"> I analyzed data that tracks woodland caribou in northern British Columbia and created an animated plot using <strong>gganimate</strong> that shows the movements of caribou between 2001-2016 </div></p>
<p class="clear"></p>
[View visualization](/portfolio/Caribou.html){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/TidyTuesday/blob/master/Caribou_06_23/Caribou_animated.R){: .btn .btn--info.btn--small}
