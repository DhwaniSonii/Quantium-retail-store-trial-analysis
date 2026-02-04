# Task 2: Store Trial Performance Analysis
## Objective

The objective of Task 2 is to evaluate the impact of new store layout trials on sales performance and customer behavior. This analysis supports a recommendation on whether the trial layout should be rolled out across additional stores.
## Business Questions Addressed
1. Did the trial stores outperform comparable control stores during the trial period?
2. Were observed changes statistically significant?
3. What factors drove performance changes: more customers, more purchases, or both?
4. Should the new layout be rolled out across the wider store network?

## Methodology
### Control Store Selection
* Defined monthly store-level KPIs:
  * Total sales revenue
  * Number of customers
* Transactions per customer
* Selected control stores using:
  * Pearson correlation to assess trend similarity
  * Magnitude distance to compare overall performance levels

### Trial vs Control Comparison
* Scaled control store metrics to align with pre-trial trial store performance
* Compared trial and control stores during the trial period
* Calculated percentage differences and confidence intervals
* Conducted t-tests to assess statistical significance

## Analysis Performed
* Time-series analysis of sales and customer metrics
* Visualization of trial vs control performance with confidence bands
* Identification of performance drivers behind observed uplift

## Key Findings 
* Two out of three trial stores demonstrated statistically significant sales uplift
* One trial store showed no meaningful difference compared to its control
* Sales uplift was primarily driven by an increase in purchasing customers
* Results varied by store, highlighting the importance of localized performance analysis

## Recommendation
* Roll out the new store layout selectively, prioritizing stores with customer profiles similar to successful trial locations
* Continue monitoring post-rollout performance to validate long-term impact
* Combine layout changes with targeted promotions to maximize uplift
