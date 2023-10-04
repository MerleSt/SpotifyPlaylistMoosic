# 🎵 Spotify Playlist Creation

## 🎯 Objective

Given a CSV file with audio features of 5,000 songs sourced from Spotify, the goal is to create playlists consisting of a minimum of 50 songs and a maximum of 250 songs, ensuring the features within each playlist are as similar as possible.

This represents a clustering problem, ideally suited for unsupervised machine learning, given the absence of predefined clusters. The subsequent sections provide a structured breakdown of the approach I undertook, including a step-by-step walkthrough. Detailed annotations can be found within the notebooks themselves.

Within the **notebooks** folder, two primary notebooks can be observed:

1. Data Cleaning 🧹
2. Analysis 📊

Additionally, the **Data** folder contains:

1. The original dataset 📁
2. The cleaned dataset, prepared for analysis 📁
3. The project can be broadly divided into three pivotal sections:

## 1️⃣ Data Preparation 📚

- Reading the data
- Initial overview and exploration
- Exclusion of non-essential features
  
## 2️⃣ Modelling 🖥️

- Potential data scaling and additional transformations
- Initial exploration with K-Means (employing techniques such as the elbow method and silhouette coefficient)
- Finalized K-Means model
  
## 3️⃣ Cluster Exploration 🔍

- Univariate and bivariate analysis of clusters
- Manual categorization and labeling of clusters
