## 🏗️ Medallion Architecture

This project follows the **Medallion Architecture** concept to organize data from raw survey responses into business-ready analytics.

![Medallion Architecture]<img width="1536" height="1024" alt="ff04ea74-93c1-4449-8562-eb524346f57b" src="https://github.com/user-attachments/assets/14ff91f0-3ee1-4738-a50a-34c3d5ba7dd5" />


### 🥉 Bronze Layer – Raw Data

The Bronze layer contains the original survey export with no transformations applied.

**Data Source**

* Raw Survey Responses (Excel)

**Characteristics**

* Original survey structure
* Wide-format dataset
* No cleaning or transformations
* Source for all downstream processing

---

### 🥈 Silver Layer – Data Preparation & Modeling

The Silver layer prepares the raw survey data for analytics using Power Query.

**Data Preparation**

* Removed blank records
* Standardized data types
* Cleaned and validated data
* Unpivoted multi-response questions
* Split brand and response attributes
* Created lookup keys
* Merged reference tables

**Fact Tables**

* `Fact_Respondent`
* `Fact_BrandFunnel`
* `Fact_Sensory_`
* `Fact_Benefits`
* `Fact_DishesUsage`
* `Fact_Pricing`
* `Fact_BrandSalience`
* `Fact_DislikesAboutCannedOlives`
* `Fact_PSM`
* `Fact_PurchaseDrivers`
* `Fact_SOA`
* `Fact_TOP3PurchaseDrivers`
* `Fact_Purchase_Platform`

**Dimension Tables**

* `Dim_Centre`
* `Dim_Brands`
* `Dim_Attribute`
* `Dim_Legend`
* `Dim_AgeRange`
* `Dim_Benefits`
* `Dim_Cuisine`
* `Dim_DishUsage`
* `Dim_ExperienceKey`
* `Dim_Frequncy of Usage`
* `Dim_Gender`
* `Dim_Olives Usage Frequency`
* `Dim_Price`
* `Dim_Purchase_Platform`
* `Dim_PurchaseDrivers`
* `Dim_Role`
* `Dim_Stage`

---

### 🥇 Gold Layer – Business Analytics

The Gold layer provides business-ready metrics and interactive reporting through DAX calculations.

**Business Measures**

* Respondent Count
* Response %
* Mean Score
* Brand Funnel Metrics
* JAR Metrics
* Price Sensitivity Metrics
* Dynamic Overall vs. City Comparison

**Analytical Reports**

* Brand Funnel Analysis
* Usage & Attitude Analysis
* Benefits Analysis
* Sensory Analysis
* Just-About-Right (JAR) Analysis
* Van Westendorp Price Sensitivity Analysis

The final output is an interactive Power BI report that enables stakeholders to explore consumer insights across brands, sensory attributes, pricing perceptions, and demographic segments.
