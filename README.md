# Health & Wellness Clustering Analysis

# Project Overview

This project applies machine learning techniques to cluster patient wellness profiles based on simulated health data. The objective is to identify meaningful patient segments using features such as daily exercise, healthy meals, sleep duration, stress level, and BMI. These insights aim to help healthcare organizations design more personalized and effective wellness programs.


# Dataset Description

The dataset contains 200 simulated patient records with the following features:

| Feature Name            | Description                                 |
|-------------------------|---------------------------------------------|
| Exercise_Time_Min       | Daily exercise duration (in minutes)        |
| Healthy_Meals_Per_Day   | Number of healthy meals consumed per day    |
| Sleep_Hours_Per_Night   | Average sleep duration (in hours)           |
| Stress_Level            | Stress score on a scale from 1 (low) to 10 |
| BMI                     | Body Mass Index                             |

---

# Project Tasks

# 1. Exploratory Data Analysis (EDA)
- Visualized the distribution of all features
- Analyzed patterns using seaborn and matplotlib

# 2. Data Preprocessing
- Standardized all features using z-score normalization

# 3. Clustering Techniques
- **K-Means Clustering**: Optimal `k` selected using Elbow Method and Silhouette Score
- **Hierarchical Clustering**: Dendrogram used to visualize nested clusters

# 4. Dimensionality Reduction
- **Principal Component Analysis (PCA)** used to reduce dimensionality and improve clustering interpretability

# 5. Model Evaluation
- Evaluated clustering performance before and after PCA using:
  - Silhouette Score
  - Within-Cluster Sum of Squares (WCSS)


# Key Findings

- Identified multiple distinct clusters with varying wellness behaviors
- PCA revealed the dominant patterns in stress, exercise, and diet-related variables
- Recommended different wellness programs tailored to each cluster's needs



