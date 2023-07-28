# Project 4: Childhood Lead Poisoning Prevention & Modeling Project
Machine learning models to identify children at risk for lead poisoning.

## Table of Contents
* [General Info](#general-information)
* [Visuals](#visuals)
* [Data Sources](#data-sources)
* [Badges](#badges)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Grading Info](#grading-info)


# General Information
## Contributors (Who?)

| Name          | Role          | Responsibilities |
| ------------- | ------------- | ---------------- |
| [Dakota Newcomb](https://github.com/DakNewcomb) | Project Manager | Manage the Project & presentation |
| [Abby Boulter](https://github.com/Abby-Boulter) | Database Lead | Manage the Database and ETL Process |
| [Brittany Brooks](https://github.com/brooksbb11)  | Modeling Lead | Manage the Machine Learning Model and Design |
| [Noelle Martinez](https://github.com/noellemtz) | Dashboard Lead | Presentation Dashboard & Manage the GitHub Repository/Documentation |

## Background (What?)
Lead poisoning can cause irreversible neurological damage in children. Lead in drinking water or paint are typical sources of lead poisoning. Currently, public health focuses response after children test for elevated lead levels. But we may be able to get ahead of the curve by using machine learning models. More information on childhood lead poisoning prevention can be found at the [CDC](https://www.cdc.gov/nceh/lead/overview.html). 

## Motivation (Why?)
We are motivated to address lead poisoning prevention as we all are impacted indirectly by lead issues. Dakota has children, Brittany is an educator, and we all care about preventing poisoning in our communities. 

## Timeframe (When?)
The data is limited to 2020.

## Modeling (How?)
We used NYS data on blood lead levels and school water quality. We coupled the data with the Social Vulnerability Index data from CDC, which includes demographics and housing data. The machine learning models predicted childhood lead exposure by using the aforementioned data.

# Visuals

# Data Sources
Childhood Blood Lead Testing and Elevated Incidence by Birth Year and Zip Code: Beginning  2000 https://health.data.ny.gov/Health/Childhood-Blood-Lead-Testing-and-Elevated-Incidenc/dyed-4zxh

Lead Testing in School Drinking Water Sampling and Results: Compliance Year 2020 https://health.data.ny.gov/Health/Lead-Testing-in-School-Drinking-Water-Sampling-and/4n6n-zu56

Centers for Disease Control and Prevention/ Agency for Toxic Substances and Disease Registry/ Geospatial Research, Analysis, and Services Program. CDC/ATSDR Social Vulnerability Index. 2020. Database. New York.

# Badges
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" />

## Project Status
Project is: _in progress_ 


## Acknowledgements
- Many thanks to...

# Grading Info
This project was a part of the University of Arizona Data Analaysis Bootcamp (2023). The project is focused on working together to solve, analyze, and visualize a problem using machine learning (ML)

## Requirements
1. Data Model Implementation (25 points)
* A Python script initializes, trains, and evaluates a model (10 points)
* The data is cleaned, normalized, and standardized prior to modeling (5 points)
* The model utilizes data retrieved from SQL or Spark (5 points)
* The model demonstrates meaningful predictive power at least 75% classification accuracy or 0.80 R-squared. (5 points)

2. Data Model Optimization (25 points)
* The model optimization and evaluation process showing iterative changes made to the model and the resulting changes in model performance is documented in either a CSV/*9 Excel table or in the
* Python script itself (15 points)
* Overall model performance is printed or displayed at the end of the script (10 points)

3. GitHub Documentation (25 points)
* GitHub repository is free of unnecessary files and folders and has an appropriate gitignore in use (10 points)
* The README is customized as a polished presentation of the content of the project (15 points)

4. Group Presentation (25 points)
* All group members speak during the presentation. (5 points)
* Content, transitions, and conclusions flow smoothly within any time restrictions. (5 points)
* The content is relevant to the project. (10 points)
* The presentation maintains audience interest. (5 points)
