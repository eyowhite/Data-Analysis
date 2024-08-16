# Call Centre Data Analysis

The full project is available from [this link](https://eyowhite.com/how-to-analyse-call-centre-sentiments-data-using-python/)

# Overview

This project focuses on analysing a dataset from a call centre to gain insights into customer satisfaction, sentiment trends, call duration, and response times. The analysis aims to identify key factors influencing customer satisfaction and provide actionable recommendations to improve call centre performance.

# Project Structure

## •	Dataset: 
    The dataset used for this analysis is an Excel file containing call centre interaction data, including attributes like CSAT scores, sentiment, call duration, and response times.
## •	Scripts:
o	Data Loading and Inspection: The script begins by loading the dataset, checking its structure, and performing initial exploratory data analysis (EDA).
o	Summary Statistics: Summary statistics for both numerical and categorical variables are generated to provide an overview of the data.
o	Distribution Analysis: Histograms and boxplots are used to visualize the distribution of key numerical variables such as CSAT scores and call duration.
o	Sentiment Analysis: The script includes visualizations to explore the distribution of sentiments and their relationship with CSAT scores and call duration.
o	Correlation Analysis: A correlation matrix is computed to quantify the relationships between call duration, sentiment, and CSAT scores, with a heatmap for visualization.
o	Response Time Analysis: The script investigates patterns in delayed response times, analyzing how they impact CSAT scores, sentiment, and call duration.
o	Time-Series Analysis: Trends in sentiments and CSAT scores over time are explored through time-series plots.
o	Summary Statistics Tables: The script includes the generation of detailed tables for numerical and categorical summary statistics.

# Usage
1.	Data Loading: Ensure that the dataset (Call-Center-Sentiment-Data-for-Analysis.xlsx) is placed in the appropriate directory. The script reads this file and performs all subsequent analyses.
2.	Execution: Run the Python script to perform the full analysis, which includes generating visualizations, calculating correlations, and displaying summary statistics.
3.	Visualisations and Results: The script outputs various plots (e.g., histograms, boxplots, bar plots, heatmaps) and tables that provide insights into the dataset. These visualizations can be used to understand customer satisfaction trends and identify areas for improvement.

# Dependencies
•	Python 3.x
•	Pandas
•	Matplotlib
•	Seaborn


# Conclusion
This analysis provides a comprehensive look at the factors affecting customer satisfaction in a call centre. By understanding the relationships between sentiment, response times, and call duration, the analysis offers actionable insights that can be used to optimize call centre operations and enhance customer experience.

