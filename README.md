# Analysis of the Impact of Transfers on NBA Team Win Percentage

## Project Overview
The goal of this project is to analyze the impact of NBA player transfers on a team's win percentage over the season. The analysis considers both team and individual player statistics to assess how roster changes may influence team performance. The developed model can support NBA managers in making transfer decisions by predicting the impact of new players on the seasonal win percentage. However, these models are influenced by various factors and should be used as supplementary decision-making tools.

## Project Structure
- **Data**: Collected from [Basketball Reference](https://www.basketball-reference.com/), covering seasons from 1989-90 to 2021-22. The data includes game stats, such as points, assists, steals, rebounds, blocks, turnovers, and fouls.
- **Data Preprocessing**: Missing values were filled using column averages, and for players who played in multiple teams during a season, the team in which they played the most games was selected.
- **Experiments**: The project uses linear regression and SVM to predict win percentage changes based on transfers and team statistics.

## Results
The project results and detailed descriptions are available in the report (PDF file in the data_scraping folder).

## Tech Stack
- Python
- Libraries: `pandas`, `scikit-learn`, `matplotlib`

##Author
Igor Podgórniak
