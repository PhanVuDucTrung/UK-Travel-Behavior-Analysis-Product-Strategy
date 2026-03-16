# UK Travel Behavior Analysis & Product Strategy

## Executive Summary
This project analyzes the **Travelpac 2022–2023 dataset** provided by the UK Office for National Statistics (ONS). By consolidating and analyzing over **70,000+ travel records** (representing 156 million UK outbound visits and £124 Billion in expenditure), the objective is to extract **actionable insights** regarding traveler behaviors and formulate **data-driven business strategies**
The analysis identified the 55+ age group as the most profitable segment, leading to the proposal of the **"Platinum Comfort & Care"** premium tour package, projected to increase segment revenue by 15%

## Tools & Technologies
* **Data Preparation (ETL):** Advanced Excel (Power Query) 
* **Data Visualization:** Excel Dashboards
* **Statistical Modeling:** SPSS (Hypothesis Testing, ANOVA, Multiple Regression)

## Data Preparation & Cleansing
To ensure data readiness and accuracy for statistical modeling, the following ETL processes were executed:
* **Data Consolidation:** Merged 4 disparate quarterly files into a unified dataset of over 70,000+ records using **Power Query**
* **Data Cleansing:** Addressed extreme outliers inherent in tourism spending data by focusing on medians and applying **Log-transformation**
* **Data Encoding:** Transformed categorical variables (e.g., Purpose, Mode, Package) into numerical formats for SPSS analysis

## Methodologies & Analytical Approach
The project applied a robust statistical framework to evaluate operational and business metrics [1]:
1. **Exploratory Data Analysis (EDA):** Built performance dashboards to track key metrics (seasonality, destination popularity, average spend)
2. **Interval Estimation:** Utilized **Bootstrap BCa (1,000 samples)** to establish 95% confidence intervals, mitigating the impact of right-skewed VIP pending outliers
3. **Hypothesis Testing:** 
   * *Independent T-test:* Revealed that male travelers spend 13.1% more per visit than female travelers
   * *Chi-Square Test:* Uncovered a strong generational divide, showing the 55+ age group significantly prefers package tours over independent travel
4. **Welch ANOVA & Post-hoc:** Proved that the 55-64 and 65+ age groups spend 30-40% more than younger demographics
5. **Multiple Regression:** Modeled the drivers of travel expenditure, confirming that choosing a "Package tour" increases per-visit spending by 27.7% compared to independent trips

## Actionable Insights & Business Recommendations
Based on the data-driven findings, the following continuous improvement initiatives were proposed:
* **Target Segment Identified:** The 55+ age demographic traveling on package tours
* **Strategy 1 - "Platinum Comfort & Care":** Designed a premium 12-day Mediterranean itinerary (Spain, Italy, Portugal) tailored for older travelers prioritizing safety and all-inclusive convenience. Projected to boost Average Revenue Per Booking (ARPB) by 10%
* **Strategy 2 - "Early-Bird & Loyalty Flywheel":** Proposed to mitigate Q3 seasonal peaks by incentivizing Q1-Q2 early bookings, aiming for a 20% increase in early booking rates

## 📁 Warehouse Structure
* 📂 `Data/`: Contains both raw and cleaned datasets (transformed via Power Query to ensure data accuracy)
* 📂 `Dashboard/`: Includes an Excel dashboard designed to enhance data visibility for operations managers
* 📂 `Report/`: Contains a comprehensive Operations Report detailing methodologies, statistical results, and business implications
* 📂 `Project Brief & Data Dictionary`: Include the information about dataset and business problem context
