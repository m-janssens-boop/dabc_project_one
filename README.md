# DABC_project_one

This script cleans and analyzes wine production and profitability metrics and weather data for the state of California from 1980 to 2020. It focuses on looking for correlations between changing weather patterns and the production level and profit of the wine industry in the five counties with the highest profit for wine in 2020: Napa, Sonoma, Marin, Santa Cruz, and Placer counties. 

data_exploration.ipynb cleans the data and creates usable dataframes and csv files.
data_stats_analysis.ipynb runs linear regressions and looks for correlations between metrics.
data_visualization.ipynb visualizes the cleaned data and looks for visual comparisons via plotting.
weather.ipynb cleans data further and plots specific weather metrics over time.

Our research questions included: How have shifting climate patterns impacted the wine industry in California?
Are there correlations between weather of a given year, wine production, and profitability?
Will the 2020 top five wine producing counties continue to be the most profitable over the next 10 years based on trends from the last 40 years?

Although we would prefer to have more concrete answers to our research questions, after running this analysis, we concluded that our dataset was too small to see any correlations if they do exist. Thus, it would be beneficial to run this code with a much larger dataset to see if there are meaningful results.
