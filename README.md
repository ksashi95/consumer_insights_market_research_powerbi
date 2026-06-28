# 📊 Consumer Insights & Market Research Analytics Report

## 📌 Overview

This project presents an end-to-end Market Research Analytics Report developed in Power BI. The report transforms raw consumer survey data into interactive insights through data modeling, Power Query transformations, and advanced DAX calculations.

The analysis focuses on brand performance, product usage, consumer perceptions, sensory evaluation, and price sensitivity across multiple respondent segments and locations.

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
* Fact_Sensory
* Fact_Benefits
* Fact_DishesUsage
* Fact_Pricing

### Dimension Tables

* Dim_Centre
* Dim_Brand
* Dim_Attribute
* Dim_Legend

---

## ⚙️ Power Query

Key transformations performed:

* Data cleaning
* Standardizing data types
* Unpivoting survey responses
* Creating lookup tables
* Merging queries
* Creating analytical fact tables

---

## 🧮 DAX Highlights

The report uses DAX to calculate:

* Respondent Count
* Response %
* Mean Score
* Brand Funnel Metrics
* Overall vs. City Comparison
* Dynamic Filtering
* Price Sensitivity Metrics

---

## 📸 Report Pages


## 💡 Key Learnings

Through this project I gained experience in:

* Designing a star-schema data model
* Transforming survey data using Power Query
* Developing reusable DAX measures
* Applying market research methodologies in Power BI
* Building interactive analytical reports

---

## 📌 Disclaimer

This repository is intended for educational and portfolio purposes. The published version uses anonymized and/or synthetic data while preserving the original analytical methodology and report structure.
