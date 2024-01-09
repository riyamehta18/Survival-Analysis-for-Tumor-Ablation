# Real-Time Physics-Based Simulation of Ablation Volume: Early Clinical Outcomes in Radiofrequency Ablation of Hepatocellular Carcinoma

## Overview
This repository contains the code for a data analysis and statistical modeling project focused on tumor recurrence and mortality after Simulation-Guided Radiofrequency Ablation (RFA). The analysis involves the use of survival analysis, competing risk regression, and Cox mixed-effects models to understand factors influencing local recurrence, hepatic recurrence, and overall survival. The project aims to provide insights into the effectiveness of Simulation-Guided RFA in preventing tumor recurrence and improving patient outcomes.

## Key Features
Data Processing: The project involves reading and processing data from multiple CSV files.
Survival Analysis: Kaplan-Meier survival curves and cumulative incidence functions are utilized to analyze time-to-event data.
Competing Risk Regression: Competing risk regression models are employed to assess factors influencing local recurrence and hepatic recurrence.
Mixed-Effects Models: Cox mixed-effects models are fitted to explore the impact of various covariates on recurrence and mortality.
Sample Size Calculation: The repository also includes code for sample size calculation based on historical control rates and desired improvements.

## Environment and Dependencies

This project was developed using R version 2023.06.0+421 (2023.06.0+421). The following R packages and libraries were utilized for data analysis and statistical modeling:

- **tidyverse (version 1.3.1)**: A collection of R packages for data manipulation and visualization.
- **survival (version 3.2-13)**: Used for survival analysis, including Kaplan-Meier survival curves and cumulative incidence functions.
- **cmprsk (version 2.2-11)**: Employed for competing risk regression models.
- **coxme (version 2.2-16)**: Utilized for fitting Cox mixed-effects models.

To reproduce the environment and install these packages, you can use the following commands:

```R
install.packages("tidyverse", version = "1.3.1")
install.packages("survival", version = "3.2-13")
install.packages("cmprsk", version = "2.2-11")
install.packages("coxme", version = "2.2-16")
