# SQL Baseball Analysis: Texas Rangers Attendance & Performance (1961–2023)

This project analyzes historical baseball data, focusing on the Texas Rangers’ performance, player salaries, and fan attendance from 1961 to 2023 using SQL. It explores trends between team success and attendance, salary extremes, and more.

## Objectives

- Compare Rangers attendance to league-wide ballpark attendance
- Identify seasons with salary extremes (Min/Max paid players)
- Measure year-over-year fan engagement (e.g. fans per win)
- Visualize long-term trends in ballpark usage, performance, and salaries

## Data Sources

- `homegames.csv`: Game-level attendance data across parks
- `parks.csv`: Parknames and location
- `salaries.csv`: Player salary data by year
- `people.csv`: Player name data
- `teams.csv`: Seasonal performance (Wins, DivWins, WSWin, etc.)

## Tools Used

- SQL (via SQLite in Python)
- Python 
- Kaggle Notebook
- PowerPoint (for visualizations)

## Key SQL Queries

The `sql-baseball-analysis.ipynb` notebook includes:
- Team success at major events
- Highest-paid and lowest-paid players per season
- Rangers wins vs. attendance over time
- Fans-per-win ratio

## Visualizations and Highlights

The `tableauBaseballVisualizations.pptx` file includes:
- Wins and runs for the team per year
    ![Wins and Runs](images/Wins_Runs.jpg)
- Batting average trends
- Win comparison within the division
    ![Win Comparison](images/WinComparison.jpg)
- Salary box plots
- Batting average, wins, and runs dashboard
    ![Dashboard](images/Dashboards.jpg)

## Insights

- Texas Rangers have won 2 Wild Card, 4 Division wins, 3 League wins, and 1 world series between 2000-2023
- Between 2000 and 2023, the team has been ranked 1st place on 4 occasions
- The highest Texas Rangers' attended game was in 2012 at Rangers Ballpark in Arilingtion, TX with 3,460,280 people present
- They played 51 home games between 1969-2023

## Next Steps

- Integrate playoff appearance data for deeper context
- Integrate more game data (only had home games)
- Analyze visiting team impact on Rangers attendance
- Add more intricate Tableau dashboards

## Acknowledgements
- Arpan Gupta Data Scientist, IITian on Youtube for a very helpful SQL queries in Kaggle tutorial
- Professor Schneider at Arizona State University for the initial assignment, data, and encouragement
