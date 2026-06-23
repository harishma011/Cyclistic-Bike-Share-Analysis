# Cyclistic Bike-Share Analysis Case Study

## Project Overview

This project is part of the Google Data Analytics Professional Certificate Capstone Case Study.

The objective of this analysis is to understand how annual members and casual riders use Cyclistic bikes differently and provide data-driven recommendations to help the company convert casual riders into annual members.

---

## Business Task

Analyze the differences between annual members and casual riders and identify opportunities to increase annual memberships through targeted marketing strategies.

---

## Dataset

The dataset used for this project is the Cyclistic Bike-Share dataset provided through the Google Data Analytics Capstone project.

The data contains ride information including:

* Ride ID
* Rideable Type
* Start and End Time
* Ride Duration
* Member Type (Member/Casual)
* Station Information
* Geographic Coordinates

---

## Tools Used

### Python

* Pandas
* NumPy
* Jupyter Notebook

### Data Visualization

* Tableau Public

---

## Data Cleaning and Preparation

The following data cleaning steps were performed:

* Combined multiple monthly datasets into a single dataset
* Checked for missing values
* Removed duplicate records
* Converted date and time columns to datetime format
* Created new features such as:

  * Ride Length
  * Day of Week
  * Month
  * Hour
* Removed invalid ride durations
* Detected and removed extreme outliers

---

## Exploratory Data Analysis (EDA)

The analysis focused on:

* Ride Count by Member Type
* Average Ride Length by Member Type
* Ride Count by Day of Week
* Average Ride Length by Day of Week
* Ride Count by Month
* Average Ride Length by Month
* Ride Count by Rideable Type
* Average Ride Length by Rideable Type

---

## Key Findings

1. Members completed significantly more rides than casual riders.
2. Casual riders had longer average ride durations than members.
3. Ride activity peaked during the summer months.
4. Weekend rides generally had longer ride durations.
5. Electric bikes were used more frequently than classic bikes.

---

## Recommendations

1. Offer targeted membership promotions to frequent casual riders.
2. Launch seasonal marketing campaigns during high-usage summer months.
3. Promote membership benefits during weekends when casual usage is highest.
4. Introduce loyalty rewards and discounts to encourage annual membership conversions.

---

## Dashboard

The Tableau dashboard provides an interactive view of rider behavior, ride duration trends, monthly patterns, and bike usage preferences.

Dashboard Visualizations:

* Ride Count by Member Type
* Average Ride Length by Member Type
* Ride Count by Day of Week
* Average Ride Length by Day of Week
* Ride Count by Month
* Average Ride Length by Month
* Ride Count by Rideable Type
* Average Ride Length by Rideable Type

---
## Dataset Note

The cleaned dataset is not uploaded due to GitHub file size limitations. The complete analysis can be reproduced using the provided jupiter Notebook and Tableau dashboard.

## Project Outcome

The analysis revealed clear behavioral differences between annual members and casual riders. These insights can help Cyclistic design targeted marketing strategies aimed at increasing annual memberships and improving customer retention.
