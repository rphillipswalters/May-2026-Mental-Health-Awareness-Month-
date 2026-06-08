# Social Stratification Analysis

## Aim

This project aimed to investigate whether mental health pressures are experienced equally across different demographic groups in England.

The analysis sought to explore how broader social factors may influence wellbeing, engagement with support services, and the likelihood of reaching crisis point. Particular attention was given to three dimensions of social stratification:

* Race
* Age
* Socioeconomic Deprivation

Social stratification refers to the ways in which people are organised within society. These social positions can create both barriers and sources of support, influencing access to resources, opportunities, social relationships, and health outcomes.

The project was particularly interested in understanding whether different groups experience different forms of social, economic, cultural, and environmental friction before reaching crisis point.

## Proposed Framework

The intended analytical framework was:

Population → Wellbeing → Service Use → Crisis Intervention

The objective was to examine whether different groups experience different forms of friction before reaching crisis point, and whether these differences are reflected in help-seeking behaviour and Mental Health Act detention outcomes.

Rather than viewing mental health solely through the lens of illness, the project aimed to explore how broader social circumstances may influence wellbeing, support-seeking behaviour, and crisis outcomes.

## Exploratory Findings

Although the full framework could not be completed, preliminary analysis identified several patterns of interest.

### Race

Population-adjusted detention rates suggested notable differences between ethnic groups. Black groups experienced substantially higher detention rates than White groups despite relatively similar levels of reported life satisfaction. Mixed ethnic groups also demonstrated comparatively high detention rates alongside lower life satisfaction scores.

These findings suggest that factors beyond wellbeing alone may influence crisis outcomes and warrant further investigation.

### Age

Detention rates were highest among adults aged 18–34, which aligned with expectations given the range of social, economic, educational, and relational pressures often experienced during this life stage.

However, comparatively elevated detention rates were also observed among adults aged 65 and over. This was notable, as mental health discussions and interventions often focus on younger and working-age populations. The age-by-ethnicity heatmap further suggested that the distribution of detentions among older adults varied across ethnic groups.

Together, these observations raise questions about the potential role of social, cultural, familial, and healthcare factors in shaping later-life mental health experiences. However, the factors underlying these differences were not explored within this project and would require further investigation.


### Deprivation

A strong relationship was observed between deprivation and detention rates. Detention rates increased steadily as deprivation increased, with the most deprived groups experiencing substantially higher rates of detention than the least deprived groups.

This was the clearest pattern identified during the exploratory phase and suggests that socioeconomic factors may play an important role in shaping crisis outcomes.

# Graphs (can also be accessed via '[social stratification.ipynb](./social.ipynb)')
## Figure 1: Mental Health Act Detention Rate by Age Group, 2022-23:
<img width="1104" height="614" alt="image" src="https://github.com/user-attachments/assets/770d6d51-d960-438f-9946-02530f775e22" />
Detention rates were highest among adults aged 18–34, with rates more than doubling those observed among 16–17 year olds. This aligned with expectations given the range of social, economic, educational, and relational pressures often experienced during this life stage, including transitions into higher education, employment, housing, financial independence, and long-term relationships.

Detention rates generally declined with age after 35. However, comparatively elevated detention rates were still observed among adults aged 65 and over. This was notable, as mental health discussions and interventions often focus on younger and working-age populations.

The age-by-ethnicity heatmap further suggested that the distribution of detentions among older adults varied across ethnic groups. Together, these observations raise questions about the potential role of social, cultural, familial, and healthcare factors in shaping later-life mental health experiences. However, the factors underlying these differences were not explored within this project and would require further investigation.

## Figure 2: Life Satisfaction and Mental Health Act Detention Rate by Race, 2022-23:
<img width="990" height="546" alt="image" src="https://github.com/user-attachments/assets/0b10f7de-229e-4648-a6a2-f8eb24dd4724" />
The bars represent population-adjusted detention rates, while the black line represents mean life satisfaction scores. White and Asian ethnic groups reported the highest life satisfaction scores and experienced comparatively lower detention rates. However, this pattern was not consistent across all groups, as Black ethnic groups reported relatively high life satisfaction scores while also experiencing the highest detention rates. This suggests that life satisfaction alone may not fully explain differences in detention outcomes.

## Figure 3: Mental Health Act Detention Rate by IBD Deprivation Decile, 2022-23
<img width="982" height="487" alt="image" src="https://github.com/user-attachments/assets/44296c63-ab0c-418b-9968-1b66335486b7" />
A clear positive relationship was observed between deprivation and detention rates. Detention rates increased progressively across deprivation deciles, with the highest rates occurring in the most deprived populations. The upward trend shown by the line of best fit further supports the presence of a strong association between deprivation and detention outcomes.

## Figure 4: Distribution of Detentions by Race and Deprivation Decile, 2022-23
<img width="988" height="524" alt="image" src="https://github.com/user-attachments/assets/fbee2500-6b4c-4e0d-96dc-e780600b1e8d" />
Across all ethnic groups, the proportion of detentions generally increased as deprivation increased. The highest concentrations of detentions were consistently observed within the most deprived deciles, while the lowest concentrations were observed within the least deprived deciles. This pattern suggests that deprivation may influence detention outcomes across multiple ethnic groups rather than being confined to a single population.

## Figure 5: Distribution of Mental Health Act Detentions by Race and Age Group
<img width="990" height="629" alt="image" src="https://github.com/user-attachments/assets/0d6ed1b5-0662-4932-84bd-ae654998420c" />
Across all ethnic groups, the largest proportion of detentions occurred among adults aged 18–34, reinforcing the finding that young adulthood may represent a particularly vulnerable life stage. Detentions generally decreased with age thereafter, although the distribution varied between ethnic groups. Notably, White ethnic groups showed a relatively larger proportion of detentions among adults aged 65 and over compared with several other groups, suggesting that later-life mental health experiences may differ across populations and warrant further investigation.

## Limitations

This analysis was ultimately paused due to limitations in data availability and comparability.

While population and Mental Health Act detention data were available, equivalent measures of wellbeing and mental health service use were not consistently available across all demographic groups and reporting periods.

Several datasets also used different demographic categories, making direct comparison difficult. For example, age categories used within wellbeing datasets did not align closely enough with those used in detention datasets to support confident interpretation without introducing additional assumptions.

In particular:

* Ethnicity-based mental health service use data could not be obtained in a format comparable to the other variables.
* Wellbeing measures were not consistently available beyond the 2022–23 reporting period.
* Deprivation measures were not consistently represented across datasets.
* Some demographic categories differed substantially between datasets, limiting comparability.

A key challenge was that while crisis outcomes could be measured through detention data, it was not possible to consistently measure all stages leading up to crisis across race, age, and deprivation. This meant the full pathway from wellbeing and support-seeking behaviour to crisis intervention could not be examined with sufficient confidence.

As a result, it was not possible to construct a sufficiently robust framework across race, age, and deprivation to answer the original research question reliably.

Rather than drawing conclusions from incomplete evidence, the analysis was paused and identified as an area for future research.

## Future Research

Despite these limitations, the exploratory analysis identified several areas that warrant further investigation.

Future work could examine:

* How cultural attitudes towards mental health influence help-seeking behaviour?
* Differences in engagement with NHS mental health services across ethnic groups?
* Whether disparities in service use contribute to differences in detention outcomes?
* The relationship between deprivation and crisis intervention.
* The role of social labelling, stigma, bias, and discrimination in mental health pathways.
* Factors contributing to elevated detention rates among adults aged 65 and over.
* How different forms of social, economic, cultural, and environmental friction influence mental health outcomes before crisis point is reached?

Access to more comprehensive NHS, ONS, or linked administrative datasets would allow a more complete examination of mental health inequalities across demographic groups.

Although the full analysis could not be completed, the exploratory findings suggest that social and demographic factors may play an important role in shaping mental health experiences, support-seeking behaviour, and crisis outcomes.
