# 🎯 FRVR: Senior Analyst Business Case

This github repo contains my work for case study presented to me by FRVR.

### Introduction

FRVR has presented me with a Business Case Study, in which FRVR has been testing a new rewarded ad model.

The case study aims to evaluate a Sr. Analysts ability to:
- analyze data efficiently
- derive actionable insights
- communicate findings to different stakeholders

The focus is on:
- cohort analysis
- retention trends
- AI-driven automation
- stakeholder alignment

## Tasks & How I've answered them

##### Task 1: SQL Query – Cohort Analysis & Retention Trends

- Everything presented in notebook including: SQL Query, Output Table, Additional Insights
- [frvr_notebook_task_1.ipynb](https://github.com/maxbenjs/frvr/blob/main/frvr_notebook_task_1.ipynb)


##### Task 2: A/B Test Analysis – Business Decision Making

Approach: 
Create multiple python functions, which:
1. Creates a dynamic dataframe (using SQL) so that we can easily create data to test KPIs at day-n
2. Chi2 Stat Test (Used for Retention Rate. A binary outcome and where we make no assumptions about the data distribution)
3. Independent T-Test (Used for ARPU. Where revenue is a continuous variable (i.e. revenue can be an infinite number of values within a given range) 
4. Visualise Retetention Rate data
5. Visualise ARPU

Finally, we run those functions sequentially to get all the relevant data in an output Cell

Workings in the following Notebook: [frvr_notebook_task_2.ipynb](https://github.com/maxbenjs/frvr/blob/main/frvr_notebook_task_2.ipynb)


##### Task 3 & 4: Executive-Level Data Visualization, Final Business Recommendation & Executive Summary

Approach:
I've combined these tasks into a single presentation. 
- The presentation can be found here: [frvr_presentation_task_3_4.pdf](https://github.com/maxbenjs/frvr/blob/main/frvr_presentation_task_3_4.pdf)
- The workings for the data & visulisations were done in the following notebook: [frvr_notebook_task_3_4.ipynb](https://github.com/maxbenjs/frvr/blob/main/frvr_notebook_task_3_4.ipynb)

Reasoning:
