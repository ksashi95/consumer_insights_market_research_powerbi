# 📊 Consumer Insights & Market Research Analytics Report

## 📌 Overview

This project demonstrates the development of an end-to-end interactive Market Research Analytics Report in Power BI. The report was designed to transform raw consumer survey data into meaningful insights using data modeling, Power Query transformations, advanced DAX calculations, and interactive visualizations.

The analysis focuses on understanding consumer awareness, product usage, sensory perceptions, and pricing expectations across different respondent segments and locations. The report enables stakeholders to explore consumer behavior through an interactive reporting experience rather than static tables or spreadsheets.

---

## 🎯 Business Objectives

The report was developed to answer the following business questions:

* Which brands have the highest consumer awareness and recall?
* Which brands are most preferred and regularly consumed?
* How do consumers perceive different sensory attributes of the product?
* Which product benefits are most strongly associated with the brand?
* How is the product used across different occasions?
* What is the acceptable price range from a consumer perspective?
* How do responses vary across different cities and demographic groups?

---

## 📈 Analytical Areas

The report includes the following analyses:

* Brand Funnel Analysis
* Usage & Attitude Analysis
* Benefits Analysis
* Sensory Analysis (Unipolar & Bipolar)
* Just-About-Right (JAR) Analysis
* Van Westendorp Price Sensitivity Analysis
* Demographic Analysis
* Location-wise Benchmarking

---

## 🛠️ Technologies Used

* Power BI
* Power Query
* DAX
* Microsoft Excel

---

## 🏗️ Data Model

The report follows a star-schema architecture with multiple fact and dimension tables.

### Fact Tables

* Fact_Respondent
* Fact_BrandFunnel
* Fact_Sensory_
* Fact_Benefits
* Fact_DishesUsage
* Fact_Pricing
* Fact_BrandSalience
* Fact_DislikesAboutCannedOlives
* Fact_PSM
* Fact_PurchaseDrivers
* Fact_SOA
* Fact_TOP3PurchaseDrivers
* Fact_Purchase_Platform


### Dimension Tables

* Dim_Centre
* Dim_Brands
* Dim_Attribute
* Dim_Legend
* Dim_AgeRange
* Dim_Benefits
* Dim_Cuisine
* Dim_DishUsage
* Dim_ExperienceKey
* Dim_Frequncy of Usage
* Dim_Gender
* Dim_Olives Usage Frequency
* Dim_Price
* Dim_Purchase_Platform
* Dim_PurchaseDrivers
* Dim_Role
* Dim_Stage
  

---

## ⚙️ Power Query

Key transformations performed:

* Data cleaning
* Standardizing data types
* Unpivoting survey responses
* Merging and Appending queries
* Creating analytical fact and dimension tables

---

## 🧮 DAX Highlights

The report uses DAX to calculate:

* Dynamic respondent counts
* Response percentages
* Mean Score
* Brand Funnel Metrics
* Overall vs. City Comparison
* Dynamic Filtering
* Price Sensitivity Metrics

---

## 📸 Report Pages

* Executive Summary
* Brand Funnel Analysis
* Usage & Benefits Analysis
* Sensory Analysis
* JAR Analysis
* Price Sensitivity Analysis

---

## 🧮 Advanced DAX Techniques
* Dynamic Overall calculations using AVERAGEX()
* Context transition with CALCULATE()
* Filter manipulation using REMOVEFILTERS()
* Disconnected table implementation with TREATAS()
* Context detection using SELECTEDVALUE()
* Variable-based calculations using VAR and RETURN


## 💡 Key Learnings

Through this project I gained experience in:

* Designing a star-schema data model
* Transforming survey data using Power Query
* Developing reusable DAX measures
* Applying market research methodologies in Power BI
* Building interactive analytical reports

---

## 📌 Disclaimer

This repository is intended for educational and portfolio purposes. The published version uses anonymized data while preserving the original analytical methodology and report structure.
