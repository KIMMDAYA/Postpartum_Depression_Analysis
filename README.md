# Postpartum_Depression_Analysis


## Project Overview
Postpartum depression (PPD) is a serious mental health condition that affects many new mothers. Identifying the key risk factors and symptoms can help provide better support and interventions for affected individuals. This project aims to analyze a dataset on postpartum depression symptoms and present key insights through data visualization.

## Table of Contents

- [Objectives](#objectives)
- [Dataset Overview](#dataset-overview)
- [Problem Statement](#problem-statement)
- [ Data Source](#data-source)
-  [ Data Tools](#data-tools)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Dashboard](#dashboard)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)


## Dataset Overview
The dataset includes survey responses from individuals experiencing postpartum depression. The key columns in the dataset include:
- Timestamp - The time of the response submission
- Age - Age group of the respondent
- Feeling sad or tearful - (Yes, No, Other)
- Feeling sad or tearful - (Yes, No, Other)
- Irritable towards baby & partner - (Yes, No, Other)
- Trouble sleeping at night - (Yes, No, 2 or more days a week)
- Problems concentrating or making decisions - (No, Often, Other)
- Overeating or loss of appetite - (Yes, No, Other)
- Feeling anxious - (Yes, No)
- Feeling of guilt - (Yes, No, Maybe)
- Problems bonding with baby - (Yes, No, Sometimes)
- Suicide attempt - (Yes, No, Not interested to say)

## Problem Statement
Postpartum depression is often undiagnosed, leading to severe mental health challenges for new mothers. By analyzing self-reported symptoms, we can identify high-risk individuals and patterns that can inform better healthcare interventions.


## Objectives

- **Assess Prevalence:** Determine the percentage of women experiencing postpartum depression symptoms such as sadness, irritability, sleep disturbances, and anxiety.
- **Identify Patterns:** Analyze relationships between different symptoms to identify common clusters associated with severe postpartum depression.
- **Highlight Risk Factors:** Examine correlations between factors like age, sleep disturbances, appetite changes, and suicidal thoughts.
- **Support Early Intervention:** Provide data-driven insights that can help healthcare professionals identify at-risk individuals early.
- **Raise Awareness:** Present findings using interactive dashboards for policymakers, healthcare providers, and the public.


## Data Source
[Kaggle](https://www.kaggle.com/code/mpwolke/postpartum-depression/input)


## Data Tools

- **Power BI:**  
  Used for data visualization, interactive dashboards, and advanced analytics using DAX.
- **Power Query Editor:**  
  Used for data cleaning and transformation.
- **Excel:**
  For initial data review.

## Exploratory Data Analysis (EDA)

1. **Data Cleaning & Transformation:**
   - Inspect dataset for missing or inconsistent values.
   - Standardize categorical responses (e.g., "Yes", "No", "Other").
   - Convert columns to appropriate data types (e.g., Age as numeric, Timestamp as date/time).

2. **Initial Visualization:**
 - Use slicers in Power BI to filter data by age group 

3. **Summary Statistics:**
   - Calculate basic metrics such as counts, percentages, and averages (e.g., average age of respondents with specific symptoms).
  
## Dashboard
- **Total Responses:** Displays the total number of participants in the survey.
- **Percentage of Participants with at Least One Risk Factor:** Shows how many respondents exhibit at least one symptom of postpartum depression.
- **Percentage of Participants with Multiple Risk Factors:** Highlights the proportion of respondents experiencing multiple symptoms.
- **Percentage Experiencing Bonding Issues with Baby:** Indicates how many respondents have difficulties bonding with their child.
- **Percentage Reporting Suicidal Thoughts:** A critical insight showing the severity of postpartum depression among participants.

  [PPD Dashboard] 
![Post partum depression dashboard](https://github.com/user-attachments/assets/61782808-c738-40e1-8573-4817beb2acd1)

## Key Insights
1.**99.87%** of respondents had at least one risk factor for PPD.

2. **52.85%** of respondents reported suicidal thoughts, highlighting an urgent need for intervention.
3. **62.84%** of respondents struggled with bonding with their baby, indicating emotional challenges.
4. **Sleep trouble** was common and correlated with concentration issues and anxiety.
5. **Women aged 30-35** had the highest average symptom score.


## Recommendations
- **Early Screening:**  
  Develop screening tools for healthcare professionals to identify early signs of postpartum depression based on key symptoms
- **Mental health interventions** pregnant women should prioritize sleep and anxiety management.
- **Therapy and support groups** should target the **30-40 age group**, as they reported the most severe symptoms.
- **Awareness programs** should focus on the emotional challenges of motherhood, particularly bonding difficulties.
- **More accessible mental health resources** should be provided for postpartum mothers.

- **Further Research:**  
  Further studies into the socio-economic factors and external stressors that might correlate with increased symptoms of postpartum depression should be encouraged.

   ## Conclusion

This analysis highlights the widespread nature of postpartum depression symptoms and the urgent need for better mental health support. The insights gained can help inform targeted interventions for new mothers experiencing mental health struggles.



