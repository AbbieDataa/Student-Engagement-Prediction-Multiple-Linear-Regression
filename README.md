# Student-Engagement-Prediction-Multiple-Linear-Regression
This project leverages Multiple Linear Regression to analyze and predict student engagement scores based on historical participation data. It was built entirely in Microsoft Excel using the Data Analysis ToolPak. The primary objective was to identify key drivers of student activity and build a reliable model to forecast future engagement levels. 

## Project files
task3_excel_format.xlsx - Full dataset with engineered features, regression output, predictions, and pivot-based visualizations
Multiple_Linear_Regression_.docx - Written methodology report covering model design, output interpretation, and diagnostic analysis

## Project Objective
The objective is to establish a functional relationship between measurable learner attributes and their Engagement Score, then use the resulting model to predict outcomes, classify learner status, and identify which opportunity types drive the strongest engagement.

## Model Specification
Regression Type: Multiple Linear Regression
Dependent Variable (Y): EngagementScore — a continuous numeric score reflecting a learner's level of platform activity
Independent Variables (X): ParticipationFrequency (X1) - Total number of times a learner participated across opportunities
Age (X2) - Learner's age in years

## Excel Implementation
Step 1 — Run the Regression :The regression was executed via Data → Data Analysis → Regression in Excel, targeting EngagementScore as Y and ParticipationFrequency + Age as X.

Step 2 — Add Predicted Engagement Column

Step 3 — Classify Learner Status: A predicted_status column was added to classify learners against a 50-point engagement threshold
A new column predicted_engagement was created in Sheet 1 using the extracted intercept and coefficients.
