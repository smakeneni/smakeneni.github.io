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
</style>   

**Survival Analysis**
<p>
<img src="/assets/images/survplot_test.png" style="float:left;width:200px;height:200px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"> <div class="myDiv">Lung cancer is the second most common form of cancer in both men and women, accounting for 2.3 million cases of the 17 million total estimated cases. In this project, I analyzed clinical trial data of ~800 patients obtained from the cancer genome atlas program <a href="https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga">(TCGA)</a>and estimated survival rates of two kinds of non-small cell lung cancers using Kaplan-Meir curves and Cox proportional hazard model. I also explored demographic, pathological, and smoking history of patients and identified statistically-significant covariates that influence survival rates.</div>
</p>

<div class="myDiv"><strong>Packages</strong> : survminer, survival, RTCGA, RTCGA.clinical</div>
<br>
[Report](/portfolio/Lungcanceranalysis.html){: .btn .btn--info .btn--small}    [Code](https://github.com/smakeneni/SurvivalAnlaysis/blob/master/Lungcanceranalysis.Rmd){: .btn .btn--info.btn--small}
<br>
<br>
<br>
<br>
**Population Estimates - Code for Philly Datathon 2020**
<p>
<img src="/assets/images/Linear_regression.png" style="float:left;width:200px;height:200px;margin-right:10px;border:1px solid #021a40;padding:3px;background-color:sand;"> <div class="myDiv">This project was done as part of a datathon organized by code for philly and R-ladies philly to assist [Prevention Point](https://ppponline.org/), a non-profit organization, which works with communities affected by drug use. The goal of our team was to estimate the number of intravenous drug users in the city of Philadelphia. In order to aid our calculations, we integrated data provided by prevention point with data from city of Philadelphia including fatal and non-fatal drug overdoses, medically assisted treament, and drug arrests. Additionally, we also explored treatment addiction datasets from [SAMHSA](https://www.samhsa.gov/). Since the data precluded any granaular data due to HIPAA, we used indirect estimation methods addition, multiplier and truncated Poisson estimation methods to estimate the number of intravenous drug users in the city.</div>
</p>

<div class="myDiv"><strong>Packages</strong> : tidyverse, ggplot2</div>
<br>
[Report](/portfolio/team_04_report.pdf){: .btn .btn--info .btn--small}    
