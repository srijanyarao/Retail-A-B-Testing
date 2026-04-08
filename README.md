# 📊 Retail A/B Testing & Sales Lift Analysis (Python)
Measuring the impact of a new store strategy using Sales Lift, Difference‑in‑Differences (DiD), and Secondary Metrics

## 🧠 Project Overview
This project analyzes a real‑world retail A/B test to measure the impact of a new store strategy on sales performance.
I compare treatment vs control stores across baseline and trial periods using weekly KPIs, then deepen the analysis with secondary metrics to understand why sales changed.
The goal is to replicate how data analysts evaluate store performance in retail environments using Python.

## 🎯 Business Questions
- Did the new store strategy increase sales?
- How did customer behavior change during the trial period?
- Which factors — foot traffic, conversion, or basket value — contributed most to the sales lift?
- Should the strategy be rolled out to more stores?

## 🧪 Experiment Design
- Treatment stores: Stores where the new strategy was implemented
- Control stores: Similar stores without the strategy
- Baseline period: Jul–Dec 2018
- Trial period: Jan–Jun 2019
- Granularity: Weekly KPIs (to smooth daily noise)

## 📈 1. Sales Lift Analysis
To measure the impact of the strategy, I compare weekly sales for treatment and control stores across baseline and trial periods.
Because treatment stores are much smaller than control stores, raw comparisons would be misleading.
To solve this, I use a Difference‑in‑Differences (DiD) approach:
DiD compares how much treatment stores changed relative to how much control stores changed, isolating the true effect of the strategy.

Result:

✔ Sales Lift: +13.9%

Treatment stores improved 13.9% more than control stores during the trial period.
This indicates a positive and meaningful impact from the new strategy.

## 📊 2. Secondary Metrics
Sales lift tells what happened.
Secondary metrics explain why it happened.
I calculated three behavioral KPIs:

### a. Foot Traffic (unique customers per week)
- Control: +2.7%
- Treatment: +12.9%
  
✔ Strongest driver of the sales lift
Treatment stores attracted significantly more visitors during the trial.

### b. Conversion Rate (transactions per unique customer)
- Slightly higher in treatment stores during the trial
- Indicates customers were more likely to buy once inside the store
  
✔ Positive but moderate contributor

### c. Average Transaction Value (ATV)
- Treatment ATV increased from 6.95 → 7.02
- Control ATV remained flat
  
✔ Customers spent slightly more per purchase

## 🧠 Overall Insights
- The new strategy generated a 13.9% sales uplift.
- Foot Traffic increased the most, suggesting the strategy improved store visibility or customer appeal.
- Conversion Rate and ATV also improved slightly, indicating better in‑store execution and basket value.
- All three metrics align to support a consistent positive impact.

## ✅ Final Recommendation
Based on the combined results:

✔ Roll out the strategy to more stores with similar profiles.

✔ Continue monitoring weekly KPIs to ensure the uplift is sustained.

✔ Run follow‑up tests to isolate which elements (layout, promotions, product mix) drove the strongest effects.

This project demonstrates how data analysts use A/B testing, DiD, and customer behavior metrics to drive business decisions.

## 🛠 Tools & Skills Used
- Python: Pandas, NumPy, Matplotlib/Seaborn
- A/B Testing
- Difference‑in‑Differences (DiD)
- KPI Engineering
- Retail Analytics
- Data Cleaning & Transformation
- Business Insight Development

## 🙌 About This Project
This project is part of my Data Analyst portfolio, showcasing my ability to:
- Analyze real business problems
- Build KPIs
- Apply causal inference methods
- Communicate insights clearly
- Translate data into actionable recommendations

