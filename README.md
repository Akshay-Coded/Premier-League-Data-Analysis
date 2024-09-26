# Premier League 2024/25 Player Statistics Dataset
![liv](img.webp)
## Overview

This repository contains a dataset of detailed player statistics from the **Premier League 2024/25 season**. The dataset is designed to provide insights into various performance metrics, including goals, assists, expected goals (xG), progressive passes, and more. By analyzing this data, you can evaluate player contributions, compare performances across different positions, and explore offensive and defensive impact.

### Dataset Columns

- **Player**: The name of the player.
- **Nation**: The player's nationality.
- **Pos**: The player's position on the field (e.g., forward, midfielder, defender).
- **Age**: The player's age during the season.
- **MP (Minutes Played)**: The total number of minutes played by the player.
- **Starts**: The number of matches the player started.
- **Min (Minutes)**: The same as MP, representing the total minutes played.
- **90s (90s Played)**: The equivalent of 90-minute matches played (e.g., 1.5 = 135 minutes).
- **Gls (Goals)**: The total number of goals scored by the player.
- **Ast (Assists)**: The total number of assists made by the player.
- **G+A (Goals + Assists)**: The combined total of goals and assists.
- **G-PK (Goals - Penalty Kicks)**: Goals scored excluding penalty kicks.
- **PK (Penalty Kicks)**: The number of goals scored from penalties.
- **PKatt (Penalty Kicks Attempted)**: The number of penalty kicks attempted.
- **CrdY (Yellow Cards)**: The number of yellow cards received by the player.
- **CrdR (Red Cards)**: The number of red cards received by the player.
- **xG (Expected Goals)**: The expected number of goals based on the player's shots.
- **npxG (Non-Penalty Expected Goals)**: Expected goals excluding penalties.
- **xAG (Expected Assists)**: The expected number of assists based on the player's passes.
- **npxG+xAG (Non-Penalty xG + xAG)**: The total of non-penalty expected goals and expected assists.
- **PrgC (Progressive Carries)**: The number of times the player carried the ball forward.
- **PrgP (Progressive Passes)**: The number of forward-moving passes made by the player.
- **PrgR (Progressive Runs)**: The number of times the player made runs forward with the ball.

## Objective

This repository aims to provide a starting point for data analysis of player statistics in the Premier League 2024/25 season. The primary areas of analysis include:

1. **Player Performance Analysis**: Understanding the top performers in terms of goals, assists, and expected goals (xG).
2. **Positional Breakdown**: Comparing the performance metrics across different positions (e.g., forwards, midfielders, defenders).
3. **Progressive Play Analysis**: Evaluating player contributions in advancing the ball through progressive carries, passes, and runs.
4. **Discipline Analysis**: Analyzing yellow and red card data to assess player discipline.

## How to Use This Dataset

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/premier-league-2024-25-player-stats.git
    ```

2. **Load the Dataset**:
    The dataset is available in `.csv` format and can be loaded using pandas in Python:
    ```python
    import pandas as pd
    data = pd.read_csv('path-to-dataset.csv')
    ```

3. **Perform Basic Data Analysis**:
    You can use the dataset for basic exploratory data analysis (EDA) or more advanced machine learning models.

## Example Analysis

Here are some possible analyses you can perform with this dataset:

- **Top Scorers and Playmakers**: Identify the top scorers and assist providers, and compare them based on xG and xAG.
- **Player Discipline**: Analyze the most disciplined (or undisciplined) players based on yellow and red card counts.
- **Progressive Players**: Discover which players are most involved in advancing the ball through progressive actions (PrgC, PrgP, PrgR).

Feel free to explore the data and create your own analyses!

## Contribution Guidelines

We welcome contributions to this project! If you'd like to add new analysis, improve existing content, or provide other enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

