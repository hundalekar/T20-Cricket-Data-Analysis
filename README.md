# T20 Cricket Data Analysis: Saving Earth from Planet Sporta!

## Problem Statement
Earth faces a cricket match challenge from Planet Sporta. The fate of our planet lies in assembling the best T20 cricket team based on statistical analysis of T20 World Cup data. The team must:

1. Score an average of 180 runs per game.
2. Defend a target of 150 runs.

## Project Overview
This project leverages statistical data analysis to assemble a cricket team of the top 11 players on Earth. Using performance metrics like batting average, strike rate, and bowling economy, a final team is selected through a systematic approach. 

The analysis is visualized in an interactive Power BI dashboard.

## Methodology
### Parameters Considered
**Openers**:
- Batting Average: > 30
- Strike Rate: > 140
- Boundary %: > 50%
- Batting Position: < 4

**Anchors / Middle Order**:
- Batting Average: > 40
- Strike Rate: > 125
- Avg. Balls Faced: > 20
- Batting Position: > 2

**Finishers / Lower Order Anchors**:
- Batting Average: > 25
- Strike Rate: > 130
- Avg. Balls Faced: > 12
- Batting Position: > 4

**All-Rounders**:
- Batting Average: > 15
- Strike Rate: > 140
- Bowling Economy: < 7
- Bowling Strike Rate: < 20

**Specialist Fast Bowlers**:
- Bowling Economy: < 7
- Bowling Strike Rate: < 16
- Dot Ball %: > 40%

### Tools and Technologies
- **Python**: Data wrangling and analysis (notebook provided).
- **Power BI**: Interactive dashboard for data insights.
- **T20 World Cup Data**: Player stats and performance metrics.

## Repository Contents
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
