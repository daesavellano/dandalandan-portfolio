---
title: "Independent Study on ML Applications in Healthcare"
date: 2025-03-21
season: A.Y. 2024-2025
draft: false
language: en
featured_image: ../assets/images/featured/Projects_2025_03_DVizDash.png
summary: Added k-means and k-prototypes clustering functionality to an R-based disease risk visualization tool to identify groups of patients with similar profiles, enabling the identification of key shared characteristics.
description: This project focused on enhancing DataViz Version 5, a visualization tool designed to analyze large patient risk datasets. My work utilized k-means and k-prototypes clustering to identify groups of patients with similar risk profiles, enabling the identification of key characteristics associated with the disease. The tool's new features were integrated into an R Shiny-based user interface, providing an interactive web experience for users.
author: Carnegie Mellon University
location: City of Pittsburgh, PA, USA
authorimage: ../assets/images/global/logos/logo_cmu_seal.png
categories: Featured
tags: ["Data Analysis","Policy","Health"]
---

### Summary

**A.Y. 2024 - 2025 Independent Study under Dr. Rema Padman**

This project focused on enhancing DataViz Version 5, a visualization tool designed to analyze large patient risk datasets. My work utilized k-means and k-prototypes clustering to identify groups of patients with similar risk profiles, enabling the identification of key characteristics associated with the disease. The tool's new features were integrated into an R Shiny-based user interface, providing an interactive web experience for users.

*Developed with R, RShiny, and JS/HTML/CSS*

### Diabetes is a critical public health issue

<center><img src="/images/posts/DataVizDash/DiabetesPrevalence.png" alt="Diabetes Prevalence is increasing" style="max-width: 70%; height: auto;" /></center>

In 2022, the US **estimated economic burden of diagnosed diabetes was $412.9 billion**, including $306.6B in direct medical costs and $106.3B in indirect expenses such as reduced productivity (Parker et al., 2024).

Beyond the financial impact, millions of individuals are affected, with **many cases remaining undiagnosed for prolonged periods**, delaying treatment and leading to more severe complications and costs.

Effective diabetes management requires timely risk assessment. Strengthening **clinical decision support systems** (CDSS) with **data-driven methodologies** offers a pathway to enhance early detection and personalize intervention strategies.

### Research Objectives

This study aimed to enhance diabetes risk assessment and improve the interpretability of risk factors through visualization techniques. This was achieved by

1. Applying k-means and k-prototypes clustering to characterize patient risk groups
2. Integrating clustering functionality within the visualization tool, and
3. Analyzing clustering results and comparing them with existing classification methods such as LDA and PCA

### About the dataset

The dataset used comes from the **American Diabetes Association**. It contains 588 records and 23 features. The dataset includes a mix of numerical and categorical variables, representing various risk factors associated with the incidence of Type II Diabetes.

Preliminary EDA was performed to assess variable distributions and correlation coefficients. The dataset showed **no missing values** and variables demonstrated **approximately normal distributions**.

Correlation analysis revealed several moderate-to-strong relationships between variables. While these correlations reflect meaningful clinical relationships, they raise concerns about multicollinearity — especially among BP measurements, treatments (i.e. checkups and medication), and disease history.

Multicollinearity can lead to redundancy in clustering algorithms, where highly correlated variables may dominate or distort the clustering structure. This can cause the algorithm to overweigh related features and reduce the distinctiveness of patient subgroups.

### Two Types of Clustering

Clustering was chosen for its ability to reveal natural groupings and patterns based on shared characteristics. Segmenting populations by common risk factors (e.g., age, lifestyle choices, and vital signs) can identify distinct risk profiles, allowing for more personalized intervention strategies. Two methods were used to create distinctive clusters: **k-means** and **Huang’s k-prototypes clustering** (Szepannek, 2018).

<center><img src="/images/posts/DataVizDash/ClusteringTechniques.png" alt="Two Types of Clustering: k-means and k-prototypes" style="max-width: 70%; height: auto;" /></center>

Both methods are iterative, unsupervised learning algorithms that require scaled variables and a predefined number of clusters. The k-prototypes algorithm extends k-means to handle both numerical and categorical data. However, both approaches are sensitive to the initial random cluster centers, which can lead to convergence at a local optimum.

The k-means algorithm minimizes the Euclidean distance between a point A and a cluster center B—the straight-line distance in a multidimensional space—making it suitable only for numerical data. Since categorical variables can skew the results, k-means is computationally faster but less flexible when handling mixed data types.

In contrast, k-prototypes combines Euclidean distance for numerical features with a dissimilarity measure for categorical features. In Huang’s k-prototypes algorithm, the categorical distance is calculated using a simple matching coefficient, where λ = 0 if the categories are the same and 1 otherwise. In this study, λ was set to `NULL`, allowing the algorithm to estimate the appropriate weighting based on the data structure. This approach ensures both numerical and categorical data influence the clustering process effectively.

The clustering results were evaluated using confusion matrices and silhouette scores. The silhouette index is a common internal validation metric for clustering, ranging from -1 to +1 (Szepannek, 2018). The silhouette score measures how similar each point is to its assigned cluster compared to other clusters, with higher values indicating better-defined and more cohesive clusters.

### Main Finding

Clustering is best utilized for its strengths in segmenting groups rather than classifying risk levels. While k-means and k-prototypes struggled to align with heart attack outcomes, clustering still offers valuable insights by highlighting patient risk patterns. To improve performance, future work should focus on refining feature selection and evaluating models with alternative methods. Despite its limitations, clustering enhances the visualization tool’s ability to identify broad risk groups, making it a useful tool for guiding further analysis and decision-making.