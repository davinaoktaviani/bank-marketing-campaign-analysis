# Bank Marketing Campaign Analysis

An exploratory data analysis project using **R** to investigate customer characteristics, campaign interactions, and their relationship with subscription outcomes in a bank marketing campaign.

The project focuses on transforming raw campaign data into meaningful insights through **data quality assessment, preprocessing, statistical analysis, feature engineering, interactive visualization, and business recommendations**.

## Project Overview

Bank marketing campaigns involve contacting customers to promote financial products. Understanding which customer characteristics and campaign factors are associated with positive responses can help improve campaign analysis and targeting strategies.

This project analyzes customer and campaign-related variables to identify patterns associated with the campaign outcome (`y`), where:

* `yes` → Customer subscribed
* `no` → Customer did not subscribe

## Objectives

This project aims to:

1. Identify and handle data quality issues.
2. Perform data cleaning and preprocessing.
3. Explore descriptive statistics and variable distributions.
4. Analyze relationships between customer/campaign variables and campaign outcomes.
5. Create meaningful features for further analysis.
6. Build interactive visualizations using Plotly.
7. Translate analytical findings into actionable business insights.

## Key Findings

Several patterns were identified during the analysis:

* The average customer age was approximately **39 years**, with a median of **37**.
* Customers in the **30–50 age group** showed a relatively high proportion of positive campaign responses.
* The `admin` job category showed a high proportion of positive responses within the analyzed dataset.
* Customers with a previous successful campaign outcome (`poutcome = success`) showed stronger positive responses in the current campaign.
* Customers responding positively generally had longer contact durations.
* Contact duration varied across education levels and months.
* Married customers had a higher average number of campaign contacts than some other marital-status groups.

## Business Insights

Based on the exploratory analysis, several potential strategies can be considered:

1. **Customer segmentation**
   Analyze customer segments such as age groups and job categories to identify groups with stronger campaign responses.

2. **Previous campaign performance**
   Consider previous campaign outcomes when prioritizing customers for future marketing analysis.

3. **Campaign interaction analysis**
   Monitor contact duration and frequency as campaign indicators while considering that longer conversations may reflect existing customer interest rather than directly causing subscription.
