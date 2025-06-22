# Freshwater Quality Classification
🏆**PROJECT ACHIEVEMENTS**🏆
- Top 3 Public Score Leaderboard Classification Rumble NDC 2025
- Top 5 Private Score Leaderboard Classification Rumble NDC 2025

![FreshwaterQualityClassificationImage](https://github.com/user-attachments/assets/a616b0d6-49ce-447e-872c-f05b6d39ed26)

This project is an implementation of the analysis and modeling pipeline for the competitive data science project conducted as part of the **Neurontara Data Clash 2025** competition, specifically titled **"Classification Rumble NDC 2025"**

It aims to develop a machine learning model that predicts the quality grade of freshwater measurements — categorized as Good, Fair, Unknown, or Pending Review — based on a diverse set of features, including in-situ readings, laboratory workflows, ecological context, and regulatory frameworks.

## Business Understanding

Access to clean and safe freshwater is a fundamental human need and a key driver of public health, sustainable agriculture, and economic development. Governments and environmental agencies around the world continuously monitor freshwater sources to ensure compliance with safety standards and to inform remediation efforts when contamination occurs.

However, the vast heterogeneity in water quality data — stemming from variations in testing methods, geographic conditions, laboratory standards, and regulatory frameworks — makes it challenging to consistently assess and compare water quality across regions and time periods.

## Data Overview

This dataset contains freshwater quality records from diverse regions, labs, and measurement methods, each influenced by environmental and regulatory contexts. The goal is to predict Data Quality—a four-class label: Good, Fair, Unknown, or Pending Review.

Features cover in-situ measurements, lab workflows, climate conditions, land use, and location metadata. The data’s diversity reflects real-world challenges in automating water quality assessment across global monitoring systems.

Further information and metadata can be found at: [[Kaggle Competition](https://www.kaggle.com/competitions/classification-rumble-ndc-2025/data)].

## Evaluation Metrics
Macro-F1

![image](https://github.com/user-attachments/assets/3bc3e761-b31f-476b-a041-ce3c2940e041)

## Installation
### Local
1. Install dependencies (recommended using virtualenv or conda):
```
pip install -r requirements.txt
```
2. Run Classification.ipynb

### Jupyter Notebook
1. Launch Classification.ipynb
