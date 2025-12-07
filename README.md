## 📉 Vanguard A/B Test Analysis 📈

<a href="https://prezi.com/view/LHHavwiSJLts2NLWv4dH/?referral_token=w0QQB7lnB3FN" style="color:#5CE1E6;" target="_blank">A/B Test Analysis Presentation</a>

--- 
## Overview
The Vanguard A/B Test Project evaluates whether differences observed between the Control and Test design variants are statistically meaningful in explaining changes in user interactions and conversion rates.
We formulated several hypotheses and applied statistical tests, primarily proportion z-tests and corresponding p-value evaluations, to determine whether these differences are statistically significant or random.

For each hypothesis, we calculated:

* the conversion or error rates for both variants

* the z-statistic measuring the size of the difference

* the p-value indicating statistical significance


## 🔸 Demographic Analysis
This analysis explores how customer demographics and the interaction timing with the design influence conversion rates. Specifically, we analyzed age, high-value customer segments, and time spent on each step of the flow. Based on these factors, we tested the following hypotheses:

1. Did the Test variation significantly impact the conversion rate?
2. Does age influence the conversion difference between Test and Control?
3. Does the Test variant convert better (or worse) than the Control within the high-value customer segment?
4. Does the Test variant convert users faster than the Control?

## 🔹 Step Errors Analysis

This analysis focuses on understanding user behavior among visitors who **did not follow the expected funnel sequence**:

> **start → step_1 → step_2 → step_3 → confirm**

We tested the following hypotheses:

1. Does the frequency of step errors differ between clients in the Control versus Test variants?
2. For users who follow an invalid step sequence, is there a significant difference in conversion between Test and Control?
3. Does client tenure impact conversion among clients with invalid step sequences?
4. How does conversion change with invalid step count across Control and Test variants?

## Dashboards

**Tableau**: <a href="https://public.tableau.com/views/ABtestingfinalproject/DashboardABtesting?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">Error Steps Dashboard</a>

<p align="center">
  <img src="images/hypotheses.png" width="55%" />
  <img src="images/hypotheses-2.png" width="35%" />
</p>
