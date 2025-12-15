---
title: "Clinical Decision Support System for Diabetes Risk"
date: 2025-04-28
season: Spring 2025
draft: false
language: en
featured_image: ../assets/images/featured/Projects_2025_04_DiabetesRisk.png
summary: Developed a preliminary prototype for a Clinical Decision Support System designed to predict the risk of diabetes using machine learning and Streamlit. Final project for Healthcare Information Systems course.
author: Carnegie Mellon University
location: City of Pittsburgh, PA, USA
authorimage: ../assets/images/global/logos/logo_cmu_seal.png
categories: Class
---

## Contents
- [Summary](#summary)
- [Project Objectives](#project-objectives)
- [System Architecture](#system-architecture)
- [Personal Contributions](#personal-contributions)
    - [Database Management](#database-management)
    - [User Interface](#user-interface)

## Summary

Find the project on GitHub: [A Preliminary Decision Support System for Early Detection of Type II Diabetes](https://github.com/daesavellano/Diabetes-Risk-Prediction/tree/main)

**Spring 2025 Project for Healthcare Information Systems**

Conducted by Danielle Aira Savellano, Hetong Wang, and Manraj Dhillon

Diabetes affects over 37 million people in the United States, with 8.5 million cases undiagnosed due to vague early symptoms. Early detection is critical to prevent serious complications and reduce the economic burden associated with diabetes. While current decision support tools integrated into electronic health records provide some predictive capabilities, they often rely primarily on clinical data. 

This project presents a Clinical Decision Support System (CDSS) designed to improve early diabetes risk detection by integrating both physical health indicators (e.g., BMI, glucose, blood pressure) and social determinants of health (e.g., physical activity, income level, mobility limitations). During routine clinical visits, the nurse collects relevant questionnaire data alongside vitals and medical history. The CDSS then evaluates this information to generate a probability score and flag whether the patient is at risk of developing Type II Diabetes (T2D).

*Developed with Python, SQL, Logistic Regression, and the Streamlit framework*

## Project Objectives

This study aimed to develop an accurate and insightful risk prediction model by addressing key analytical questions:

- **Descriptive Analysis**: Determine the distribution of diabetes status across different demographic groups and analyze feature correlations.
- **Predictive Modeling**: Build a classification model (e.g., Logistic Regression) using historical data to predict which individuals are at risk for diabetes and identify the key predictors among the 21 available features.
- **Sensitivity Analysis**: Quantify how changes in lifestyle factors (such as increased physical activity, higher fruit/vegetable consumption, or reduced heavy alcohol consumption) would impact the predicted prevalence of diabetes in the population.

## System Architecture

The system architecture integrates a SQL database for data storage, a Python-based logistic regression model for diabetes risk prediction, and a Streamlit user interface for physician interaction. Patient, survey, and user information are managed through Create, Read, Update, and Delete (CRUD) operations on the database. Data is preprocessed and fed into the trained model to generate diabetes risk scores, which are displayed to users and stored in the database. Python libraries including `psycopg2`, `pandas`, and `scikit-learn` support data handling, modeling, and prediction.

<center><img src="/images/posts/Projects/Diabetes_Risk/System_Architecture.png" alt="System Architecture" style="max-width: 100%; height: auto;" /></center>

## Personal Contributions

For the project, I held end-to-end ownership of the system's foundational infrastructure, specifically **designing and managing the SQL relational database for patient data**, and **developing the interactive Streamlit dashboard** that served as the primary CDSS interface for physicians. Other team members focused on the model training and evaluation (selecting from Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and XGBoost) and the creation of an implementation plan.

### Database Management

Python was used to run a SQL script, create the database, and populate the associated tables. A Python module containing reusable CRUD operations was developed to enable consistent interaction with the database across different system components. This module uses the `psycopg2` library to manage database connections and transactions.

<center><img src="/images/posts/Projects/Diabetes_Risk/Database_Design.png" alt="Database Design" style="max-width: 100%; height: auto;" /></center>

Our database includes seven entities: `Demographics`, `Survey`, `PatientReport`, `Lifestyle`, `Vitals`, `Users`, and `Patients`. Each entity’s attributes are shown above, with additional details and entity relationships listed in our group's full report. The entity relationship model has a flat structure, with no superclasses or subclasses.

### User Interface

The user interface was developed using Python's Streamlit library. It allows physicians to log in, create or transfer new patient records, view or update existing patient information, and submit survey responses. The interface triggers the risk prediction model upon data submission and displays the resulting diabetes risk scores. Updated patient information and prediction results are then stored back into the SQL database.

<center><img src="/images/posts/Projects/Diabetes_Risk/UI_Screenshots.png" alt="User Interface" style="max-width: 100%; height: auto;" /></center>

## Conclusion

By combining physical health indicators with social factors, our system aims to offer a more complete risk assessment than current tools. The CDSS is easy to use and fits naturally into existing clinical workflows, helping providers make quicker and more informed decisions. Through testing with multiple machine learning models, we achieved strong performance, especially focusing on minimizing missed high-risk cases. While challenges like nonuse and physician skepticism may arise, the tool’s advisory nature gives providers the flexibility to incorporate it into their practice as they see fit. Overall, our system has the potential to improve early detection of diabetes and support better patient outcomes with minimal disruption to everyday healthcare routines.
