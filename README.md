# Netflix Content Strategy Analysis

This repository contains an in-depth analysis of Netflix's content library and provides actionable insights for improving its business strategy across different countries. The analysis focuses on identifying trends in the types of shows and movies Netflix produces, understanding its content's global distribution, and recommending ways to enhance Netflix’s content offerings based on data-driven insights.

## Project Overview
Netflix is a leading global streaming platform, with over 222 million subscribers and a content library of more than 10,000 movies and TV shows as of 2021. This project aims to analyze Netflix’s existing dataset, which includes details about the shows and movies available on the platform, such as:

- **Show ID**: Unique identifier for each title
- **Type**: Whether the content is a movie or TV show
- **Title**: Name of the movie or TV show
- **Director**: Director of the content
- **Cast**: Actors involved in the production
- **Country**: Country where the content was produced
- **Date Added**: The date the content was added to Netflix
- **Release Year**: Year the movie or show was released
- **Rating**: TV rating (e.g., PG, R, TV-MA)
- **Duration**: Duration of the content (minutes or number of seasons)
- **Genre**: Categories or genres associated with the content
- **Description**: Summary of the content

## Business Problem
The objective of this case study is to generate insights that can help Netflix make informed decisions regarding:
- **What type of shows or movies should Netflix focus on producing?**
- **How can Netflix grow its business and subscriber base in different countries?**

## Files in this Repository
- **README.md**: This file provides an overview of the project, business context, and a guide to the repository.
- **Netflix_Content_Strategy_Analysis.ipynb**: A Google Colab notebook containing the complete analysis, data preprocessing, visualization, and insights derived from the Netflix dataset.
- **Netflix_dashboard** : A tableau dashboard file

## Key Steps and Methodology
The project involves the following key steps:
1. **Defining the Problem Statement**: Analyzing Netflix’s content strategy to recommend actions for content production and subscriber growth.
2. **Data Preprocessing**: Handling missing data, converting categorical variables, extracting insights from non-standard data like lists (e.g., country, cast).
3. **Exploratory Data Analysis**:
   - **Non-Graphical Analysis**: Value counts, unique values, missing value detection.
   - **Visual Analysis**: Univariate and bivariate visualizations, including count plots, scatter plots, box plots, and heatmaps.
4. **Business Insights**: Observing patterns and trends across different genres, countries, release years, and content duration to inform business decisions.
5. **Recommendations**: Providing actionable suggestions for Netflix's content strategy and regional growth, based on the analysis.

## Insights and Recommendations
Based on the analysis, we offer several key insights, such as:
- Continue investing in popular genres such as International Movies, Dramas, and Comedies to cater to global audiences.
- Since the majority of content consumed is between 90-120 minutes for movies and 1 season for TV shows, producing movies with this runtime could boost engagement.
- Plan releases around peak times (e.g., first week of winter months for new TV shows and movies), around December 1st would be the most appropriate date.
- Consider releasing movies with actors like Shahrukh Khan and Anupam Kher, and directors such as Rajiv Chilaka and Jan Suter to increase audience engagement.
- Focus on adding Movies and TV Shows released recently, as 75% of content added is from 2011-2015.

## Tools and Technologies
- **Python**: For data analysis and visualization.
- **Pandas**: Data manipulation and preprocessing.
- **Seaborn & Matplotlib**: For data visualizations.
- **Google Colab**: Used for running the notebook and analyzing the dataset.
