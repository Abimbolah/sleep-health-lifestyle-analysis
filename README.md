# Sleep Health & Lifestyle Analysis

## Project Overview

This project explores relationships between sleep health, lifestyle habits, stress levels, and selected health indicators using Python. I used data cleaning, exploratory data analysis (EDA), feature scaling, and K-Means clustering to examine patterns and group individuals with similar lifestyle characteristics.

The project demonstrates how data analysis can help uncover patterns in a dataset and communicate findings that support further investigation.

## Objectives

- Clean and prepare the dataset for analysis.
- Explore patterns in sleep duration, stress, and physical activity.
- Examine relationships among selected lifestyle and health variables.
- Apply K-Means clustering to identify groups with similar characteristics.
- Evaluate clustering performance using the silhouette score.
- Interpret cluster profiles and compare them with sleep-disorder categories.

## Tools and Technologies

- **Language:** Python
- **Data manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Machine learning:** Scikit-learn
- **Environment:** Google Colab

## Methodology

1. **Data preparation:** Inspected the dataset, standardized selected category values, handled missing values, and prepared variables for analysis.
2. **Exploratory data analysis:** Examined distributions and relationships among sleep duration, stress, physical activity, and other health indicators.
3. **Feature scaling:** Used `StandardScaler` to scale the variables selected for clustering.
4. **K-Means clustering:** Grouped observations into four clusters using sleep duration, stress level, and physical activity level.
5. **Evaluation and interpretation:** Calculated the silhouette score and compared cluster characteristics, including selected health indicators and sleep-disorder categories.

## Key Findings

The cluster analysis highlighted different combinations of sleep duration, stress, and physical activity. The cluster profiles were then compared with health indicators and sleep-disorder categories to explore how these characteristics differed across groups.


## Limitations

- Clustering identifies similarities in the selected features; it does not establish cause and effect.
- Sleep-disorder categories were examined after clustering and were not the target of a predictive model in this analysis.
- Findings are based on the dataset and should not be interpreted as medical advice.

Project Notebook

https://colab.research.google.com/drive/1ZFNBLZLu6f5wRFyWLq-IpUbvn04cfYiW?usp=sharing

Skills Demonstrated

Data cleaning, exploratory data analysis, feature scaling, data visualization, unsupervised machine learning, cluster evaluation, interpretation of results, and analytical reporting.
