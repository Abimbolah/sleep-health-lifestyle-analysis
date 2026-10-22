# Sleep Health and Lifestyle Analysis: Data Cleaning, Exploratory Analysis, and K-Means Clustering

## Project Overview

This project explores sleep health and lifestyle data for 374 participants across 13 original variables. Using Python in Google Colab, I cleaned and prepared the dataset, conducted exploratory data analysis (EDA), examined relationships among lifestyle and health indicators, and applied K-Means clustering to identify groups with similar sleep duration, stress levels, and physical activity levels.

The analysis also compares the resulting clusters with recorded sleep-disorder categories to explore how these characteristics vary across groups.

## Objectives

- Clean and prepare the dataset for analysis.
- Explore patterns and relationships among sleep, stress, physical activity, and other health indicators.
- Use visualizations to communicate key findings.
- Apply K-Means clustering to identify distinct lifestyle profiles.
- Compare cluster characteristics with recorded sleep-disorder categories.
- Evaluate the clustering results using the silhouette score.

## Tools and Techniques

- **Programming:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn
- **Techniques:** Data cleaning, exploratory data analysis, data visualization, feature scaling, K-Means clustering, and cluster evaluation.

## Clustering Approach

K-Means clustering was performed using three standardized features: sleep duration, stress level, and physical activity level. The remaining variables were used for exploratory analysis and to help interpret the resulting clusters.

Sleep-disorder categories were not used as clustering inputs. They were examined after clustering to compare the distribution of recorded categories across groups.

## Project Scope and Limitations

This is an exploratory analysis of the available dataset. Clusters describe similarities among participants based on the selected features; they do not establish causation, diagnose medical conditions, or predict an individual's health outcomes.
Project Notebook

https://colab.research.google.com/drive/1mU4kolCxGneMUIIDIWNdgbX3InisUNOB?usp=sharing

Skills Demonstrated

Data cleaning, exploratory data analysis, feature scaling, data visualization, unsupervised machine learning, cluster evaluation, interpretation of results, and analytical reporting.
