# IPL Data Analytics Project

# End-to-End Exploratory Data Analysis using Python
## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Technical Implementation](#technical-implementation)
- [Results](#results)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

## Overview

This project performs comprehensive **Exploratory Data Analysis (EDA)** on Indian Premier League (IPL) cricket data spanning from 2008 to 2017. The analysis uncovers patterns in team performance, player contributions, toss impacts, and venue characteristics through statistical analysis and data visualization.

## Objectives

Answer key questions about IPL dynamics:
- **Which teams are most successful in IPL history?**
- **Does winning the toss increase chances of winning?**
- **Who are the top-performing batsmen and bowlers?**
- **Which venues host high-scoring matches?**
- **What patterns emerge across different seasons?**

## Dataset

The project uses two primary datasets:

### 1. **matches.csv** (636 matches)
Contains match-level information:
- Match ID, season, date, venue
- Teams, toss details, result
- Winner, win margin, player of the match

### 2. **deliveries.csv** (150,460 deliveries)
Contains ball-by-ball details:
- Match ID, innings, over, ball
- Batsman, bowler, runs scored
- Extras, dismissal information

## Project Structure
IPL-Data-Analytics/
│
├── data/
│ ├── matches.csv # Match-level data
│ └── deliveries.csv # Ball-by-ball data
│
├── notebooks/
│ └── IPL_EDA_Complete.ipynb # Main analysis notebook
│
├── src/
│ ├── data_loader.py # Data loading utilities
│ ├── preprocessor.py # Data cleaning functions
│ ├── analyzer.py # Analysis functions
│ └── visualizer.py # Visualization functions
│
├── requirements.txt # Python dependencies
├── README.md # This file


### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Google Colab
The notebook is compatible with Google Colab. Simply upload the notebook and datasets to your Google Drive.

### Key Findings
## Team Performance
Mumbai Indians are the most successful team (highest win percentage)
Chennai Super Kings and Kolkata Knight Riders follow closely
Team performance matrices show consistent patterns across seasons

### Toss Impact Analysis
Winning the toss provides a significant advantage
Teams prefer batting first (59.3%) over fielding first (40.7%)
Toss winners win matches in 53.7% of cases

### Top Performers
## Batsmen:
SK Raina - Highest run scorer
Virat Kohli - 4 centuries, 31 fifties
DA Warner - Most consistent (36 fifties)
CH Gayle - Most explosive (5 centuries)

## Bowlers:
Dwayne Bravo - Most wickets in a season (32)
Bhuvneshwar Kumar - Most consistent Indian bowler
## All-Rounders:
Dwayne Bravo - Best all-rounder (1500+ runs, 183 wickets)

## Scoring Patterns
Death overs (16-20) show highest scoring rates
Powerplay overs exhibit controlled aggression
Middle overs have scoring fluctuations
Brabourne Stadium hosts highest-scoring matches

### Visualizations
The project includes 25+ different visualizations:

## 1. Basic Charts
Bar charts for top performers
Pie/donut charts for distributions
Line graphs for trends
Scatter plots for relationships

## 2. Advanced Visualizations
Heatmaps for team matchups and win probabilities
Violin plots for runs distribution per over
Bubble charts for milestone comparisons
Parallel coordinates for bowler analysis
Sankey diagrams for score flows
Radar charts for multi-dimensional comparison

## 3. Dashboard
Comprehensive 2x3 dashboard showing:
Top 10 run scorers
Matches per season trend
Toss decision split
Runs scored over overs


#### Technical Implementation
Data Processing Pipeline
Data Loading & Inspection
Data Cleaning
Handling missing values
Removing duplicates
Correcting data types
Feature Engineering
Derived metrics (strike rate, economy rate)
Performance indicators
Milestone tracking
Exploratory Analysis
Statistical summaries
Correlation analysis
Trend identification

## Analysis Methods
Descriptive Statistics: Mean, median, mode, variance
Correlation Analysis: Pearson correlation coefficients
Time Series Analysis: Season-wise trends
Comparative Analysis: Team vs team, player vs player
Probability Analysis: Win probabilities, toss impact

## Results
Statistical Insights
Average match score: 310 runs (median)
Most common dismissal: Caught (73.2%)
Boundary frequency: 4s every 10.3 balls, 6s every 23.7 balls
Extras contribution: Average 11.2 runs per match

Performance Metrics
Batting: Strike rate vs runs scatter analysis
Bowling: Wickets distribution by over
Fielding: Catches and stumpings analysis
Team: Win probability by venue
## Future Work
Planned Enhancements
Predictive Modeling
Match outcome prediction
Player performance forecasting
Fantasy points prediction
Advanced Analytics
Sentiment analysis of commentary
Player valuation models for auctions
Network analysis of partnerships
Interactive Dashboard
Real-time match analysis
Player comparison tool
Team strategy simulator
Extended Analysis

## Include 2018-2023 data

International player impact
Economic analysis of franchise performance

## Acknowledgements
Data Source: Kaggle
Visualization Libraries: Matplotlib, Seaborn
Analysis Tools: Pandas, NumPy
Development Environment:  Google Colab

Akshay kumar mp
8156942767



