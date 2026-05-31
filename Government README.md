# Government & Policy Analysis

## Aim

To examine how government and policy institutions respond to increasing demand for mental health services, and whether service provision is keeping pace with patient needs.

## Overview

This section explores the relationship between mental health service demand, waiting times, and performance against NHS access targets.

Government policies play a significant role in shaping access to healthcare services through funding decisions, service planning, workforce allocation, and performance targets. This analysis investigates whether mental health services are effectively meeting demand by examining service backlogs, waiting times, and treatment performance indicators.

## Research Question

How effectively are mental health services meeting demand?

## Dataset Description

This analysis uses NHS England Referral to Treatment (RTT) data relating to:

Total number of incomplete pathways
Median waiting time (weeks)
Percentage of patients treated within 18 weeks

These indicators were selected to represent:
| Indicator	| Represents |
|---|---|
|Total incomplete pathways | Service demand and backlog pressure|
|Median waiting time | Patient experience and access to care|
|Within 18 weeks (%) |	Performance against NHS treatment targets|

### Primary Data Sources

* NHS England Referral to Treatment (RTT) Waiting Times Statistics
* NHS England Mental Health Dashboard

### Supporting Sources

* British Medical Association (BMA) Mental Health Pressures Analysis
* NHS England Medium-Term Planning Framework

## Methodology

The analysis follows a structured approach:

Data extraction from NHS England sources
Data cleaning and preparation
Exploratory Data Analysis (EDA)
Data normalisation to allow comparison of indicators with different scales
Multi-line time series visualisation
Interpretation of trends within a healthcare policy context

## Analysis

A normalised multi-line graph was produced to compare:

Total incomplete pathways
Median waiting time (weeks)
Percentage treated within 18 weeks

Normalisation was applied to enable meaningful comparison between variables measured on different scales.

## Data Quality Considerations

When interpreting these findings, it is important to note that NHS England reported data quality issues between October and December 2022 due to missing submissions from one or more NHS Trusts.

Specifically:

* October 2022: Frimley Health NHS Foundation Trust and Manchester University NHS Foundation Trust did not submit data.
* November 2022: Frimley Health NHS Foundation Trust and Manchester University NHS Foundation Trust did not submit data.
* December 2022: Manchester University NHS Foundation Trust did not submit data.

The figures used in this analysis are the published NHS England figures. However, NHS England advises that trends during this period should be interpreted with caution due to the missing provider submissions.

Additional time-series estimates accounting for non-reporting providers are available within NHS England's RTT Overview Timeseries files.


## Insight
<img width="991" height="482" alt="image" src="https://github.com/user-attachments/assets/b7033c09-b3a9-4df1-9b3c-2ca7e4b905ea" />

Between 2022 and late 2023, incomplete pathways and median waiting times generally increased while the proportion of patients treated within 18 weeks declined.

This suggests increasing pressure on NHS services and growing challenges in meeting demand.

From late 2023 onwards, incomplete pathways and waiting times decreased while performance against the NHS 18-week target improved.

Together, these trends highlight the relationship between service demand, patient waiting times, and healthcare system performance.

## Tools Used

Python
Pandas
Matplotlib
Google Colab

## Files

* `government_data.csv` – cleaned dataset used for analysis
* `government_policy_analysis.ipynb` – notebook containing code, visualisation, and interpretation
* `government.md` — project documentation

## Further Development & Research

To strengthen this analysis, further research will be incorporated to provide deeper context and explanation of the observed trends.

This includes:

* Research on NHS waiting times and healthcare access
* Studies exploring the impact of delayed treatment on mental health outcomes
* Academic literature examining policy implementation and service capacity
* Government and NHS reports evaluating mental health service performance

Incorporating these sources will allow for a more comprehensive interpretation of the data and support stronger evidence-based conclusions.
