# Online Store Data Analysis Project

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Hypotheses Prioritization](#hypotheses-prioritization)
- [A/B Test Analysis](#ab-test-analysis)
- [Statistical Significance](#statistical-significance)
- [Decision](#decision)
- [Conclusion](#conclusion)

## Introduction
This project is a deep dive into online store data, aimed at helping the marketing department make data-driven decisions. The primary objectives are to prioritize hypotheses, launch an A/B test, and analyze the results to boost revenue and improve the store's overall performance.

## Data
The project uses three main datasets:

- **Hypotheses Dataset**: This dataset contains a list of hypotheses for improving the online store. It includes columns such as "Hypothesis," "Reach," "Impact," "Confidence," and "Effort."

- **Orders Dataset**: This dataset provides information about customer orders. It includes columns like "transactionId," "visitorId," "date," "revenue," and "group."

- **Visits Dataset**: This dataset tracks visitor data, including "date," "group," and "visits."

## Data Preprocessing
Data preprocessing involves cleaning the data and adjusting column types. Key steps include:

- Converting appropriate columns to categorical types.
- Converting date columns to datetime types.
- Identifying and removing any duplicated or missing data.

## Hypotheses Prioritization
We prioritize hypotheses based on the ICE and RICE frameworks. ICE (Impact, Confidence, Effort) and RICE (Reach, Impact, Confidence, Effort) help us identify the most promising hypotheses. These frameworks take into account various factors to prioritize actions.

## A/B Test Analysis
We analyze the results of the A/B test, including:

- Graphing cumulative revenue by group.
- Graphing cumulative average order size by group.
- Calculating the relative difference in cumulative average order size.
- Calculating daily conversion rates for both groups.

## Statistical Significance
We determine the statistical significance of differences in conversion rates and average order size between groups using the raw data and the filtered data to account for anomalies.

## Decision
Based on the analysis, we make a decision regarding the A/B test. The possible decisions include:

1. Stop the test, consider one of the groups as the leader.
2. Stop the test and conclude that there is no significant difference between the groups.
3. Continue the test.

## Conclusion
In the final conclusion, we summarize the key findings, including whether the A/B test yielded statistically significant results and whether there are actionable insights to improve the online store's performance.

This README provides an overview of the project, highlighting the key steps, data, and results. The full analysis can be found in the project's Jupyter Notebook.

For detailed code and analysis, refer to the Jupyter Notebook in this project repository.
