# Assignment 5 - Toddler Project
## Overview

This Jupyter Notebook is part of Assignment 5, focusing on basketball analytics. Initially, a different dataset was planned, but due to challenges in replicating historical data, a new dataset was chosen. The core objective of this assignment remains the same—analyzing basketball performance trends using statistical and visualization techniques.
Dataset Information

The analysis is based on two primary datasets:

Regular_Season_Cleaned.csv – Contains cleaned data related to regular-season performance metrics.
Playoffs_Cleaned.csv – Focuses on playoff performance statistics.

These datasets include various basketball statistics such as player performance, team scores, and other key indicators. The data has been pre-processed to ensure consistency and accuracy.
Key Objectives

This notebook aims to:

Load and explore cleaned datasets for regular-season and playoff performances.
Perform exploratory data analysis (EDA) to identify patterns, trends, and anomalies.
Use statistical summaries to describe key features of the datasets.
Generate visualizations to compare regular-season and playoff performances.

### Libraries Used

The following Python libraries are required to execute the analysis:

pandas – For data manipulation and analysis.
matplotlib.pyplot – For creating static visualizations.
seaborn – For enhanced visual representation of statistical insights.
numpy – For numerical operations.
re – Used for handling regular expressions in data cleaning.

### Data Exploration & Processing

The notebook first reads the cleaned CSV files using pandas and loads them into DataFrames.
A high-level summary of the data is presented using .describe() to display statistical properties such as mean, median, standard deviation, and range.
The .head() function is used to preview the first few rows of both datasets to understand their structure.
Visualizations using seaborn and matplotlib help highlight trends and comparisons between the regular season and playoff performances.

### Credit
The datasets used in this assignment were the NBA statistical records of the 2023-2024 regular and post season posted by Vivo Vinco on Kaggle.
https://www.kaggle.com/datasets/vivovinco/2023-2024-nba-player-stats/data