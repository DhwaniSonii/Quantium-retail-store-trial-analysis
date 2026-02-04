# Quantium-retail-store-trial-analysis
## Project Overview 
This project is an end-to-end retail analytics case study focused on understanding customer purchasing behavior and evaluating the performance impact of in-store layout trials for the chips category. The analysis simulates a real client engagement, delivering data-driven insights to support category strategy and rollout decisions.
Using Python-based exploratory data analysis (EDA), KPI evaluation, and statistical testing, this project translates transactional data into actionable business recommendations for a Category Manager.

## Key Outcomes
* Identified high-value customer segments driving the majority of category sales
* Determined that increased units per customer, rather than price increases, was a key driver of higher spend
* Validated statistically significant sales uplift in 2 out of 3 trial stores during the trial period
* Recommended targeted rollout of new store layouts based on control vs trial performance analysis

## Business Context
Quantium’s Category Manager for Chips introduced new store layouts in selected trial stores to assess whether changes in shelf placement could improve sales performance. The objectives were to:
* Understand who purchases chips and what drives their spending
* Evaluate whether trial layouts delivered measurable uplift compared to comparable control stores

The findings directly support a decision on whether the layout should be rolled out across the wider store network.

## Task 1: Customer & Sales Analysis
### Objective:
Analyze historical transaction data to uncover customer purchasing patterns and key sales drivers within the chips category.
### Analysis Performed:
* Segmented customers by life stage and premium status
* Defined and analyzed core retail KPIs, including:
* Total sales revenue
* Number of customers
* Units per customer
* Average price per unit
* Conducted EDA with visualizations to identify trends and anomalies
* Applied statistical testing (t-tests) to validate differences between customer segments
* Analyzed brand and pack size preferences, with a focus on young and mid-age couples
### Insights:
* Sales growth was primarily driven by higher purchase volumes, not price inflation
* Young and mid-age couples contributed disproportionately to total sales
* Larger pack sizes were a key contributor to higher spend in family-oriented segments

## Task 2: Store Trial Evaluation
### Objective:
Assess whether the new store layouts resulted in statistically significant performance improvements.
### Methodology:
* Aggregated transaction data into monthly store-level KPIs
* Selected control stores using:
  * Pearson correlation
  * Magnitude distance metrics
* Scaled control store KPIs to align with trial store baselines
* Compared trial vs control performance during the trial period
* Conducted t-tests and confidence interval analysis
* Visualized results using time-series plots and confidence bands
### Results:
* Two trial stores demonstrated sales uplift outside the 95% confidence interval of their control stores
* One trial store showed no statistically significant change
* Increases were driven by more purchasing customers, rather than increased transaction frequency alone

## Tools & Techniques
* Programming: Python (Pandas, NumPy)
* Visualization: Matplotlib, Seaborn
* Analytics: Exploratory Data Analysis (EDA)
* Statistics: Correlation analysis, scaling techniques, t-tests
* Business Metrics: Retail KPIs, customer segmentation  
