# Sleep Health and Lifestyle Analysis: Data Cleaning, Exploratory Analysis, and K-Means Clustering

## Project Overview

This project analyzes the [Sleep Health and Lifestyle Dataset from Kaggle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset), containing 374 participants across 13 original variables. Using Python in Google Colab, I performed data cleaning, exploratory data analysis (EDA), and K-Means clustering to identify lifestyle patterns and explore their relationship with recorded sleep-disorder categories.

## Objectives

- Clean and prepare the dataset for analysis.
- Explore relationships among sleep, stress, physical activity, and other health indicators.
- Visualize key patterns and findings.
- Apply K-Means clustering to identify distinct lifestyle profiles.
- Compare cluster characteristics with recorded sleep-disorder categories.
- Evaluate clustering performance using silhouette scores.

## Tools and Techniques

- **Programming:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Techniques:** Data cleaning, exploratory data analysis, data visualization, feature scaling, unsupervised machine learning, K-Means clustering, and silhouette analysis.

## Clustering Approach

K-Means clustering was applied to three standardized features: sleep duration, stress level, and physical activity level. Other variables were used to explore the dataset and interpret the resulting clusters.

I compared solutions with 4, 5, 6, and 10 clusters using cluster sizes, feature averages, the elbow method, and silhouette scores. I selected **five clusters** as a practical balance between meaningful separation and interpretability.

Sleep-disorder categories were excluded from the clustering inputs and examined afterward to compare their distribution across the resulting groups.

## Key Analytical Focus

The analysis examines:

- Differences in sleep duration, stress, and physical activity across clusters.
- How lifestyle profiles vary among participants.
- The distribution of recorded sleep-disorder categories across clusters.
- The usefulness of clustering for identifying exploratory patterns in sleep and lifestyle data.

## Project Notebook

[View the complete analysis in Google Colab](https://colab.research.google.com/drive/1mU4kolCxGneMUIIDIWNdgbX3InisUNOB?usp=sharing)

## Skills Demonstrated

Data cleaning, exploratory data analysis, feature scaling, data visualization, Python programming, unsupervised machine learning, K-Means clustering, model evaluation, cluster interpretation, and analytical reporting.

## Limitations

This project is an exploratory analysis of the available dataset. The clusters represent similarities based on the selected features and depend on the chosen variables and clustering parameters. They do not establish causation, diagnose medical conditions, or predict individual health outcomes.
