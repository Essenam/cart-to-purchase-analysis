Marketing analytics project to investigate a decline in cart-to-purchase conversion.
# Customer Cart-to-Purchase Conversion Analysis

**Tools Used:** R, tidyverse, ggplot2, dplyr

## 🔍 Overview
This project analyzes six months of e-commerce activity from a multi-category retailer to identify the cause of a 10% drop in cart-to-purchase ratio observed in one month.

The goal:  
- Understand product and customer features influencing purchases  
- Simulate revenue impact of behavioral changes  
- Provide data-backed solutions for marketing and product recovery strategies

## 📈 Methods

### 🧹 Data Preparation
- Cleaned and deduplicated event-level retail data
- Created categorical variables for user and product segmentation
- Simulated March data with a 10% drop in purchases from February baseline

### 📊 Exploratory Data Analysis
- Cart-to-purchase ratio dropped from 0.59 to 0.53  
- $213,921 in estimated revenue lost in March  
- Top categories impacted: **Videocards** and price buckets of **$200–$300**

### 🤖 Predictive Modeling
- Built classification models to predict purchase likelihood
- Key variables: user session duration, interaction frequency, and product category diversity

### ✅ Recommended Solutions
- Marketing focus on high-conversion categories with price sensitivity  
- Promotional offers targeted at mid-range products  
- Engagement-based segmentation for re-targeting customers

## 📎 Files
- `Decline in cart-to-purchase conversion.Rmd`: full source code and narrative  
- `Decline in cart-to-purchase conversion.html`: rendered report 
