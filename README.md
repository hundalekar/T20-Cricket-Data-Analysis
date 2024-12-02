# T20 Cricket Data Analysis: Saving Earth from Planet Sporta!

## Problem Statement
Earth faces a cricket match challenge from Planet Sporta. The fate of our planet lies in assembling the best T20 cricket team based on statistical analysis of T20 World Cup data. The team must:

1. Score an average of 180 runs per game.
2. Defend a target of 150 runs.

## Project Overview
This project leverages statistical data analysis to assemble a cricket team of the top 11 players on Earth. Using performance metrics like batting average, strike rate, and bowling economy, a final team is selected through a systematic approach. 

The analysis is visualized in an interactive Power BI dashboard.

## Libraries
1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. os

## Methodology
### Parameters Considered
**1. Openers**:
- Batting Average: > 30
- Strike Rate: > 140
- Innings Batted: > 3
- Boundary %: > 50%
- Batting Position: < 4

**2. Anchors / Middle Order**:
- Batting Average: > 40
- Strike Rate: > 125
- Innings Batted: > 3
- Avg. Balls Faced: > 20
- Batting Position: > 2

**3. Finishers / Lower Order Anchors**:
- Batting Average: > 25
- Strike Rate: > 130
- Innings Batted: > 3
- Avg. Balls Faced: > 12
- Batting Position: > 4
- Innings Bowled: > 1

**4. All-Rounders**:
- Batting Average: > 15
- Strike Rate: > 140
- Innings Batted: > 2
- Batting Position: > 4
- Innings Bowled: > 2
- Bowling Economy: < 7
- Bowling Strike Rate: < 20

**5. Specialist Fast Bowlers**:
- Innings Bowled: > 4
- Bowling Economy: < 7
- Bowling Strike Rate: < 16
- Bowling Style: 'fast'
- Bowling Average: < 20
- Dot Ball %: > 40%

### Tools and Technologies
- **Python**: Data wrangling and analysis (jupyter notebook provided).
- **Power BI**: Interactive dashboard for data insights.
- **T20 World Cup Data**: Player stats and performance metrics.

## Repository Contents
- **`data/csv_data`**: Contains csv files like batting_summary.csv, bowling_summary.csv, match_summary.csv, dim_players.csv.
- - **`data/json_data`**: Contains json files like t20_wc_batting_summary.json, t20_wc_bowling_summary.json, t20_wc_match_summary.json, t20_wc_players.json.
- **`data/Paramaeter_Scoping.pdf`**: Detailed parameter criteria for player selection.
- **`data/Project1.pbix`**: Power BI file containing the dashboard.
- **`notebooks/code.ipynb`**: Python notebook for data analysis.
- **`scripts/`**: Placeholder for Python scripts if applicable.

## Final Output
An interactive Power BI dashboard highlights the insights, culminating in the "Final Team" dashboard showcasing the top 11 players.

## How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/hundalekar/T20-Cricket-Data-Analysis.git

2. Access the Power BI dashboard (Project1.pbix) using Power BI Desktop.
3. Review the Python analysis in the Jupyter notebook (code.ipynb).
