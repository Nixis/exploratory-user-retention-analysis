# Exploratory Behavioural Analysis of User Retention Patterns Using Python

## Project Overview

This project explores behavioural differences between retained and churned users using Python-based exploratory data analysis (EDA).

The objective was to identify usage patterns potentially associated with user retention and churn risk through data cleaning, visualization, statistical exploration, and behavioural trend analysis.

The analysis demonstrates a structured analytical workflow involving:

- data preprocessing
- exploratory data analysis (EDA)
- outlier assessment
- behavioural interpretation
- statistical reasoning
- communication of analytical findings

---

## Business Problem

User retention is a critical metric for mobile applications. Understanding behavioural patterns associated with churn can help support retention strategies, improve user engagement, and guide data-driven decision-making.

This analysis investigates whether differences in driving activity, engagement intensity, and usage behaviour exist between retained and churned users.

The project focuses on identifying behavioural trends rather than building a production-ready predictive model.

---

## Dataset Description

| Item | Description |
|---|---|
| Dataset | Waze user activity dataset |
| Records | ~14,999 users |
| Target Variable | User churn status |
| Features | Sessions, drives, distance travelled, activity days, driving duration, device type, etc. |
| Tools Used | Python, pandas, NumPy, matplotlib, seaborn |

The dataset contains behavioural and engagement metrics associated with Waze users. The analysis focuses on exploring differences between retained and churned users and identifying variables potentially linked to churn behaviour.

---

## Project Workflow

1. Data cleaning and preprocessing  
2. Exploratory data analysis (EDA)  
3. Behavioural trend analysis  
4. Outlier assessment  
5. Statistical exploration  
6. Visualization and interpretation  
7. Analytical conclusions and limitations assessment  

---

## Key Findings

### User Retention Distribution

Approximately 82% of users were retained while roughly 18% were classified as churned.

This class imbalance is important because it can influence interpretation of aggregate metrics and future predictive modelling approaches.

---

### Device Type Does Not Strongly Influence Churn

The analysis found no strong evidence suggesting that device type (Android vs iPhone) significantly influenced churn behaviour.

This suggests that user retention patterns are more likely associated with behavioural engagement metrics rather than device preference alone.

---

### Churned Users Show Higher Driving Intensity

One of the clearest behavioural trends observed was that churned users tended to display higher driving intensity.

Metrics such as:

- distance driven per driving day
- total driving activity
- driving duration

were generally higher among churned users compared with retained users.

---

### Presence of Highly Active Outlier Users

Several variables exhibited heavy skewness caused by a relatively small number of extremely active users.

These users disproportionately influenced overall distributions and highlighted the importance of:

- robust exploratory analysis
- careful interpretation of averages
- outlier-aware visualization
- distribution-based analysis

---

## Visualizations

The project includes several exploratory visualizations, including:

- churn distribution count plots
- driving intensity boxplots
- feature correlation heatmaps
- activity distribution histograms
- behavioural comparison plots

---

## Statistical Exploration

Additional statistical exploration included hypothesis testing to assess whether differences existed between user groups.

This stage reinforced concepts related to:

- hypothesis testing
- statistical significance
- p-value interpretation
- analytical decision-making
- sampling variability

---

## Repository Structure

```text
waze-user-retention-analysis
│
├── data
├── notebooks
├── images
├── README.md
└── requirements.txt
```

---

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Jupyter Notebook / Google Colab

---

## Limitations

Several limitations should be considered when interpreting the results:

- The dataset represents a simplified analytical sample rather than full production-scale user behaviour.
- Correlation does not imply causation.
- Behavioural variables alone may not fully explain churn decisions.
- Several variables exhibited strong skewness and outlier sensitivity.
- The project focused on exploratory analysis rather than predictive deployment.

---

## Conclusion

This project demonstrated a structured analytical workflow for exploring behavioural drivers associated with user retention and churn.

Beyond the technical analysis itself, the project emphasized:

- analytical reasoning
- uncertainty awareness
- behavioural interpretation
- exploratory data analysis
- communication of findings

The workflow and analytical approach are transferable across multiple domains involving behavioural analytics, user engagement analysis, and data-driven decision-making.

---

## Future Work

Potential future extensions of this project could include:

- predictive churn modelling
- feature engineering
- classification models
- clustering analysis
- user segmentation
- time-series behavioural analysis
- model evaluation metrics

These additions could help transition the project from exploratory analytics toward predictive user retention modelling.

---

## Author

**Nixis Carrero Candelas**

Geoscientist | Data Analytics 