---
layout: post
title: Predict Property Valuations
---

### **General Assembly Data Science Final Project** - Client Sellable  <br />
<hr>

# My Capstone project
<hr>
![](/Img/capstone_image_1.PNG)  <br />

# Project Introduction
<hr>
## Company Overview:
Sellable takes the hassle out of selling your home, they’re property experts that buy homes, make them look spectacular,
and then sell it using the best agents in the business. Currently receiving valuation requests of over 200 properties a month.

## Objectives:
- To have an automated valuation model to accurately predict property valuations.

## Key Requirements:
- Data clean customer .cvs file
- Obtain satellite imagery and calculate square lot area  and built area
- Scrape valid information from Web Sites that would be used for the model

# Action Plan
<hr>
- Data Gathering and Resources

![](/Img/capstone_image_2.PNG) <br />

![](/Img/capstone_image_3.PNG) <br /> <br />

# High Level Overview of Process
<hr>

![](/Img/capstone_image_4.PNG) <br /> <br />


# Architecture Process Flow
<hr>

![](/Img/capstone_image_5.PNG) <br /> <br />

# Sellable Property Dashboard
<hr>

![](/Img/capstone_image_6.PNG) <br /> <br />

![](/Img/capstone_image_7.PNG) <br /> <br />

# Valuation Model
<hr>
<b>The property Prediction was based on various features listed previously</b>

# Regression Models Tested were
<hr>
- <b>Lasso(L1) –</b> Helps in reducing over fitting by been aggressive with feature selection, this is in order to enhance the prediction accuracy. It adds a penalty equivalent to the absolute value of coefficients

- <b>Rigde(L2) – </b>Where predictor features are highly correlated, it adds a penalty equivalent to the square of the coefficients

- <b>RandomForest – </b>An example of an ensemble method, meaning it relies on the aggregating the results of an ensemble of simpler estimators.


<br /> <br />
# Model Selection Choice
<hr>

![](/Img/capstone_image_8.PNG) <br /> <br />

# Model Result Output
<hr>

![](/Img/capstone_image_9.PNG) <br /> <br />

# Image Recognition
<hr>
<b>Start with the address longitude/Latitude and feed this to google maps using an API key obtained</b>

- Grab the Google Image data and save the image files 400x400
- Display the grayscale image
- Mask based grayscale colour of the built up area
- Label and show the connected components in the mask
- Label the regions and find which label contains the centroid.
- Calculate the Lot Size         meters_ppx=156543.03392*Math.cos(data.latitude[0]

![](/Img/capstone_image_10.PNG) <br /> <br />

# Application Data Entry Screen Demo
<hr>
![](/Img/capstone_image_11.PNG) <br /> <br />

# Predicted Valuation
<hr>
![](/Img/capstone_image_12.PNG)


```python

```
