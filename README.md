
# SRC FTBL Final Project

This project evaluates Messi's passing ability using data from statsbombpy and Statsbomb360. I use the programming language Python to write the code for my analysis within Jupyter Notebooks. The project is a part of a technical interview process for SRC FTBL.

# Libraries used

matplotlib.pyplot - a collection of functions used to create different displays using raw data

pandas - used to create dataframes to store Statsbomb data

numpy - used to support large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays

mplsoccer - used to import a two-dimensional soccer pitch to plot the location of data

statsbombpy - used to access and import public data provided by Statsbomb using Python

rcParams - used to import sophisticated text styles for aesthetics

json - used to directly access and import json files within the notebook using Python

IPython.display - used to display images for raw data within a notebook

os - used for accessing the directory folder and using its contents
# Soccer Analysis Code

This repository contains code for analyzing soccer data using Python libraries. The code is organized into different functions, each serving a specific purpose.

### Function 1: World Cup Final Passing Analysis

The `world_cup_final_passing_analysis` function retrieves event data from the 2022 World Cup Final between Argentina and France and generates a passing network visualization for Argentina, as well as a plot of Messi's passes using the `matplotlib` and `mplsoccer` libraries. Visualizations include total passes, passes by foot, and progressive passes. This is supported by data from https://fbref.com/en/comps/1/passing/World-Cup-Stats.

### Function 2: Messi's Incomplete Passes Analysis

The `messi_incomplete_passes_analysis` function analyzes Messi's incomplete passes during the 2020-21 La Liga season and generates a scatter plot of their location using the `statsbombpy` and `seaborn` libraries.

### Function 3: Player Heatmap Analysis

The `player_heatmap_analysis` function analyzes a player's heatmap based on their event data, allowing for customization of the heatmap colors and style.

### Function 4: Pass to Shot Analysis

The `team_shot_analysis` function combines Messi's passes with a team's shot data  and generates a visualization of their shot locations on the field, providing insights into their attacking patterns and scoring efficiency.

### Function 5: Match 360 Analysis

The 'match 360 Analysis' function combines event data with Statsbomb360 data to plot the location of passes as well as the location of surrounding players from both teams.

Please refer to the code comments and function documentation for further details on how to use each function. Make sure to install the required libraries before running the code.

# Next Steps

To provide a more complete analysis on this topic, I would run linear regression to evaluate the relationships between the passing variables. Based on the results from this analysis, I would update my existing analysis and gain better insights into what other factors are including within a player's passing ability. 

Additionally, valuing actions would be effective within the smaller sample size that is used throughout this project. This is because specific actions can be measured to evaluate how they affect the probability of the team scoring. Valuable metrics such as expected threat xT are included in this area of analysis.

