# Football-Prediction

# Spanish Second Division Football Matches Dataset
This repository contains a dataset of Spanish second division football matches, including the final results of each game. The aim of this project is to use the information available in the dataset to predict the result probabilities of future matches.

## Dataset Description
The dataset consists of two CSV files:

matches.csv: Contains information about each match played in the 2021/2022 season of the Spanish second division. Each row represents a match and includes the following columns:

home_team: The name of the home team.
away_team: The name of the away team.
home_goals: The number of goals scored by the home team.
away_goals: The number of goals scored by the away team.
date: The date of the match.
teams.csv: Contains information about the teams that participated in the 2021/2022 season of the Spanish second division. Each row represents a team and includes the following columns:

team_name: The name of the team.
team_id: A unique identifier for the team.
## Project Overview
The goal of this project is to use the information available in the dataset to predict the result probabilities of future matches. To achieve this, we will use machine learning models to learn from the historical data and make predictions about future matches.

The project is organized as follows:

data: Contains the matches.csv and teams.csv files.
notebooks: Contains Jupyter notebooks that were used to explore and analyze the data, as well as to train and evaluate the machine learning models.
src: Contains the Python source code used to preprocess the data, train the machine learning models, and make predictions.
