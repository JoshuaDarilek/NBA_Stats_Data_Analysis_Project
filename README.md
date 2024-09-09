# NBA Player Stats Analysis

## Project Overview

This project analyzes performance metrics for NBA players using data from the 2023 season. The analysis is crucial for teams, coaches, and fans to understand player contributions, make strategic decisions, and engage with the sport more deeply.

### Scope

Maintaining and analyzing performance metrics for NBA players is vital for:

- Teams to make informed decisions during games and for player management
- Coaches to understand player strengths and weaknesses
- Fans to gain a deeper understanding of the game
- The sports betting industry, which relied on $119.84 billion in wagers in 2023

### Research Questions

1. Which offensive metric is most strongly associated with player points per game?
2. Which defensive metric is most strongly associated with a player's average plus/minus per game?

## Dataset

- File: `2023_nba_player_stats.csv`
- Source: [NBA Players Stats 2023 Season on Kaggle](https://www.kaggle.com/datasets/amirhosseinmirzaie/nba-players-stats2023-season)
- Description: This dataset contains comprehensive statistics for NBA players from the 2023 season.

## Analysis

The analysis is conducted in the Jupyter notebook `nba_stats_analysis.ipynb`. This notebook includes:

- Data preprocessing
- Exploratory data analysis
- Statistical analysis to answer the research questions
- Visualizations of key findings

## Project Structure

- `2023_nba_player_stats.csv`: Raw data file
- `nba_stats_analysis.ipynb`: Jupyter notebook containing the analysis
- `README.md`: This file, providing an overview of the project
- `.gitignore`: Specifies intentionally untracked files to ignore

## Requirements

To run this project, you'll need Python 3.11.0 or later, along with the following libraries:

- numpy
- pandas
- scipy
- matplotlib
- seaborn
- jupyter
- plotly

You can install the required packages using the `requirements.txt` file:

```
pip install -r requirements.txt
```
