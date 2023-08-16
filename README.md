<img src="Premier_leauge.jpg" width="1200" height="500" alt = "Premier Leauge Logo">

# English Premier League Exploratory Data Analysis

## Overview
This project involves an exploratory data analysis (EDA) of the English Premier League dataset. The dataset contains various performance metrics for different teams across multiple seasons(2000-2022).

## Motivation
The goal of this project is to gain insights into team performance, and trends across different seasons in the English Premier League.

## Dataset
| Column   | Description                                          |
|----------|------------------------------------------------------|
| Season   | Match Season                                         |
| DateTime | Match Date and Time (yyyy-mm-dd hh:mm:ss)            |
| HomeTeam | Home Team                                            |
| AwayTeam | Away Team                                            |
| FTHG     | Full Time Home Team Goals                            |
| FTAG     | Full Time Away Team Goals                            |
| FTR      | Full Time Result (H=Home Win, A=Away Win, D=Draw)    |
| HTHG     | Half Time Home Team Goals                            |
| HTAG     | Half Time Away Team Goals                            |
| HTR      | Half Time Result (H=Home Win, A=Away Win, D=Draw)    |
| Referee  | Match Referee                                        |
| HS       | Home Team Shots                                      |
| AS       | Away Team Shots                                      |
| HST      | Home Team Shots on Target                            |
| AST      | Away Team Shots on Target                            |
| HC       | Home Team Corners                                    |
| AC       | Away Team Corners                                    |
| HF       | Home Team Fouls Committed                            |
| AF       | Away Team Fouls Committed                            |
| HY       | Home Team Yellow Cards                               |
| AY       | Away Team Yellow Cards                               |
| HR       | Home Team Red Cards                                  |
| AR       | Away Team Red Cards                                  |


## Key Questions Explored
- How many matches were played in each season?
- Which teams were involved in the most matches?
- What is the distribution of full-time home goals (FTHG) and away goals (FTAG)?
- How many matches ended in a home win (FTR = 'H'), away win (FTR = 'A'), or draw (FTR = 'D')?
- Half-Time Analysis:
  - What is the distribution of half-time home goals (HTHG) and away goals (HTAG)?
  - How does the half-time result (HTR) correlate with the full-time result (FTR)?
- Referees and Fair Play:
  - Who are the most frequent referees and how do they impact match outcomes?
  - Are there any trends between the number of yellow cards (HY, AY) and red cards (HR, AR) received by teams and match results?
- Team Performance and Statistics:
  - What is the average number of shots (HS, AS) per match for home and away teams?
  - Are there any relationships between the number of corners (HC, AC) and match outcomes?
- Foul Analysis:
  - Is there a correlation between the number of fouls committed (HF, AF) by a team and their match result?
  - Are there teams with a higher number of red cards (HR, AR) that tend to lose more matches?
- Goal Distribution:
  - How many matches had a certain number of goals (FTHG + FTAG)? Plot a histogram.
  - Are there matches where the half-time goals (HTHG + HTAG) were significantly different from full-time goals?
- Home Advantage:
  - Is there a consistent home advantage? 
- Fair Play and Card Distribution:
  - How does the distribution of yellow and red cards differ between home and away teams?
- Shot Efficiency:
  - Which teams have the highest shot conversion rates (goals per shots on target)?


## Methodology
1. Data loading and preprocessing
2. Descriptive statistics and visualization
3. Correlation analysis


## Conclusion
This EDA provides valuable insights into team performance and attributes within the English Premier League. The findings can contribute to a better understanding of factors affecting team success.

## Acknowledgments
The dataset used in this project is sourced from : https://www.kaggle.com/code/laimingwa/premier-league-data-exploratory-data-analysis.

