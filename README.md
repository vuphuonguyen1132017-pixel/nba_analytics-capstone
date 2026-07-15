# nba_analytics-capstone
NBA Analytics Dashboard using Tableau, Python, and SQL

## Overview
An end-to-end data analytics project exploring over 35 years of NBA player statitics (1980 - 2017). The project uses Python for data cleaning, SQL for data querying, and Tableau to build interactive dashboards.

## Tools Used
 - **Python** (Pandas) - data cleaning, exploratory data analysis
 - **SQL** (SQLite) - aggregate queries, filtering, ranking
 - **Tableau Public** - interactive dashboard

## Dataset
NBA Players Stats since 1950 (Kaggle) - filtered to 1980-2017, 18,900 player-season records across 50+ statistical categories.

## Main Questions
1. Who are the all-time leading scorers?
2. How has league-wide scoring hanged from 1980 to 2017?
3. Which tea have scored the most points historically?

## Key Findings
1. Karl Malone leads all-time scoring in this dataset (36,928 pts)
2. League-wide average points per game declined from 11.0 (1980) to 9.8 (2017), likely due to league expansion diluting per-player stats.
3. Sharp scoring dips in 1999 and 2012 correspond to NBA lockouts, which shortened those seasons - not player performance decline .
4. Denver Nuggets recorded the highest total franchise scoring all teams from 1980 to 2017, with 326,751 points, slightly surpassing the Phoenx Suns and Golden State Warriors.

## Live DashBoard
https://public.tableau.com/views/NBAAnalyticsDashboard_17840843017610/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Methodology 
1. **Data Cleaning (Python)**: Claened the dataset by removing unnecessary columns, filtering records from 1980 onward, and handling missing values in advanced statistics that were not available in earlier seasons.
2. **Data Analysis (SQL)**: Analyzed scoring performance using SQL with GROUP BY, aggregate functions (SUM, COUNT DISTINCT), and filtering conditions to remove "TOT" records and avoid duplicate team totals.
3. **Data Visualization (Tableau)**: Created an interative 3-section dashboard highlighting top scores, scoring trends across seasons, and franchise scoring rankings.

## Conclusion
This project highlights how NBA scoring are affected by both player performance and larger league changes, including lockouts and expansion. Using Pyhton, SQL, and Tableau, I analyzed historical scoring patterns and created visualization to make the insights easier to understand.
