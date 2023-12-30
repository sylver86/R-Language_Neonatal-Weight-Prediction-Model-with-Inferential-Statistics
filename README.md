# Neonatal-Weight-Prediction-Model-with-Inferential-Statistics-in-R

Introduction

This project focuses on developing a statistical model to predict neonatal weight based on a dataset collected from three hospitals, encompassing records of 2500 newborns.
Dataset Overview

    File: neonati.csv
    Variables:
        Mother's age
        Number of pregnancies
        Maternal smoking (0=NO, 1=YES)
        Weeks of gestation
        Weight in grams of the newborn
        Length in mm of the newborn
        Diameter in mm of the newborn's skull
        Type of delivery: Natural or Cesarean
        Hospital: 1, 2, 3
        Sex of the newborn: M or F
    Objective: Explore the feasibility of predicting neonatal weight considering various factors, especially examining maternal variables for potential significant effects (e.g., the impact of smoking).

Project Summary

This README outlines the steps undertaken in the project and provides insights into the statistical analyses performed.
Project Workflow

    Data Import: Import the neonati.csv dataset and ensure its accuracy.
    Descriptive Analysis: Describe the dataset, its variables, and the research objective.
    Exploratory Data Analysis (EDA): Conduct a comprehensive exploratory analysis using statistical indices and visual tools.
    Hypothesis Testing: Assess if sample means of weight and length differ significantly from the population.
    Sex-Based Analysis: Investigate significant differences in weight and length between sexes.
    Hospital Cesarean Rate Hypothesis: Determine if significant differences exist in Cesarean rates among hospitals.

Multivariate Analysis

    Regression Model: Develop a multiple linear regression model using all variables and interpret the results.
    Model Selection: Employ various criteria for selecting the best model and explain their application.
    Nonlinear Effects and Interactions: Explore nonlinear effects or interactions between variables.
    Residual Analysis: Conduct a thorough diagnostic of the model's residuals and identify influential values.
    Predictive Performance: Evaluate the model's effectiveness for predictions.
    Prediction Example: Provide an example predicting the weight of a third pregnancy at the 39th week, considering no ultrasound measurements.

Visual Representations and Further Analysis

    Model Visualization: Create graphical representations to aid in understanding the model.
    Out-of-the-Box Analysis: Encourage unconventional analyses and highlight noteworthy findings.
    Resources and References: Document the R packages or external resources utilized for enhanced analysis.
