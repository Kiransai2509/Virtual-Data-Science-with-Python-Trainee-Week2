# Week 2 — Exploratory Data Analysis and Visualization

## Objective
Use descriptive statistics and visualizations to understand the customer population, campaign activity and term-deposit subscription outcome.

## Files
- `YuvaIntern3_week2.ipynb` — executed EDA notebook.
- `Week2_Exploratory_Data_Analysis_Visualization_Report.docx` — detailed report.

## Work Completed
- Target-class distribution and subscription rate.
- Age and balance distributions.
- Subscription rates by job and customer categories.
- Education, marital status and housing-loan comparisons.
- Subscription rates by contact month.
- Previous campaign outcome analysis.
- Campaign contact frequency and call-duration distributions.
- Numeric correlation heatmap.

## Verified Headline Results
- Total customers: 45,211.
- Subscribed: 5,289 (11.7%).
- Not subscribed: 39,922 (88.3%).
- Previous campaign outcome `success`: approximately 64.7% observed subscription rate across 1,511 records.

## Interpretation Notes
Rates must be interpreted alongside group sizes. Observed group differences are descriptive and do not establish causation.

Call `duration` is included only for retrospective EDA. It is measured during the call and is excluded from pre-call predictive modelling.

## Re-running
Open the notebook in Google Colab and select **Runtime → Run all**. Save the generated figures for use in the report.
