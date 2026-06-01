# Economic Analysis

## Aim
To examine how economic conditions, specifically unemployment rates, relate to mental health outcomes over time.

## Overview
This section of the project focuses on the relationship between economic stability and psychological wellbeing. It explores how fluctuations in unemployment may align with changes in anxiety levels across the UK population.

## Dataset Description
This analysis uses quarterly data relating to:

- Unemployment rate (%) over time
- Mean anxiety scores (ONS personal wellbeing data)

### Primary data sources:
- UK Office for National Statistics (ONS) – Unemployment rate (aged 16 and over, seasonally adjusted)
- UK Office for National Statistics (ONS) – Personal wellbeing estimates (anxiety)

### Data structure:
- Time series (quarterly)
- Combined dataset aligning unemployment and anxiety by period

## Methodology
The analysis follows a structured approach:

- Data extraction from ONS datasets
- Alignment of datasets by time period (quarterly)
- Data cleaning and formatting into a unified dataset
- Exploratory data analysis using Python (pandas)
- Visualisation using matplotlib (multi-line time series graph)

## Analysis
A multi-line graph is used to compare unemployment rates and anxiety levels over time, allowing for visual identification of trends and potential relationships.

## Insight
<img width="785" height="586" alt="image" src="https://github.com/user-attachments/assets/abf2520c-d1be-4d9d-a0de-43b9a56c02cf" />

Unemployment rates show a general upward trend over time, while anxiety levels remain relatively stable with minor fluctuations.

Despite worsening employment conditions, anxiety does not increase proportionally, suggesting that mental health outcomes are influenced by multiple factors beyond employment alone.

However, periods of higher unemployment coincide with slightly elevated anxiety levels, indicating that economic instability may still contribute to psychological stress.

This highlights the complex relationship between economic conditions and mental health and suggests that employment is one of several interacting systemic factors that may influence wellbeing.

## Tools Used
- Python (pandas, matplotlib)
- Exploratory Data Analysis (EDA)
- Data visualisation

## Files
- `economic_data.csv.csv` – cleaned dataset used for analysis
- `economic_analysis.ipynb` – notebook containing code, visualisation, and insight

## Further Development & Research Integration

To strengthen this analysis, further research will be incorporated to provide deeper context and explanation of the observed trends.

This includes:

- Academic literature on the relationship between unemployment and mental health
- Public health and economic studies exploring financial stress and psychological wellbeing
- Policy-based reports examining the impact of labour market conditions on population health

Incorporating these sources will allow for a more comprehensive interpretation of the data and support stronger, evidence-based conclusions.
