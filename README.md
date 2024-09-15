
# FIFA World Cup Data - Exploratory Data Analysis (EDA)





## overview
This project involves an Exploratory Data Analysis (EDA) on FIFA World Cup data to analyze team performances, player statistics, and tournament trends. The goal was to uncover meaningful insights regarding team dynamics, strategies, and key patterns across various tournaments.


## Techstack
- **Python:** For data cleaning, manipulation, and analysis.
- **Pandas:** For efficient data handling and exploration.
- **Matplotlib & Seaborn:** For generating insightful visualizations, including bar plots, line charts, KDE plots, and pie charts.
- **Plotly:** For creating interactive, dynamic visualizations that allow deeper exploration of the data.
- **Jupyter Notebook:** To document and run the analysis interactively.
## Data Description
The dataset contains match-level data from the FIFA World Cup. Below is a brief summary of the columns:

- **home_team, away_team:** Names of the home and away teams.
- **home_score, away_score:** Final scores for the home and away teams.
- **home_xg, away_xg:** Expected goals (xG) for home and away teams (available for 128 matches).
- **home_penalty, away_penalty:** Penalties awarded to home and away teams.
- **home_manager, away_manager:** Managers of the home and away teams.
- **home_captain, away_captain:** Captains of the home and away teams (available for 644 entries).
- **Attendance:** Number of spectators in each match.
- **Venue:** Location where the match was held.
- **Round:** Stage of the tournament (e.g., group stage, knockout).
- **Date:** Date of the match.
- **Referee, Officials:** Referee and officials overseeing the match.
- **Host:** Host country of the tournament.
- **Year:** Year of the World Cup.
- **Goals and Penalties:** Information on goals scored, own goals, penalties, and penalty shootouts.
- **Cards:** Red and yellow card information for both teams.
- **Substitutes:** Information on substitutes brought on during the match.
## Inferences and findings
### Team Performances
- Brazil holds the record for the most FIFA World Cup titles, followed by Italy and Argentina.
- Argentina, the Netherlands, and West Germany have finished as runners-up the most times.
- Germany has secured third place (second runner-up) the most times.
- Brazil is the only team to have participated in every edition of the World Cup.
- New entrants to the tournament include Qatar, Canada, and Wales.
- Teams such as Cuba, Israel, Kuwait, Jamaica, Ukraine, and Togo have only participated in a single edition of the World Cup.
### Knockout Stage Insights
- Italy shows strong knockout stage performance with a 75% win probability in quarter-finals, 86% in semi-finals, and 67% in finals.
- Spain wins the title if they advance past the quarter-finals.
- France has a good quarter-final record but struggles in the semi-finals and finals.
- Sweden has never reached a final, while Argentina has a high probability of winning once it reaches the semi-finals.
### Game Strategies
- Teams generally play more aggressively in the second half, regardless of whether it's a knockout or non-knockout stage.
- Mexico tends to score only in the first half during knockout tournaments, often defending their lead in the second half.
- Teams like Romania and Peru maintain consistent aggression throughout both halves of the game.
- Spain adopts a passive approach in the first half during knockout matches, scoring more aggressively in the second half and extra time.
- Canada has never scored a second-half goal, a factor that may contribute to their absence from knockout stages.
### Substitution Impact
- No substituted player has ever scored a goal in FIFA World Cup history.
- Teams like France, Argentina, Portugal, Australia, Germany, Spain, and the Netherlands benefit from substitutions, suggesting strong in-game management.
- Substitutions have a positive impact on team performance, but teams cannot rely on them for goal-scoring directly.
### Underdogs and Overperformers
- In the 2018 World Cup, Argentina underperformed in home games but overperformed in non-home matches.
- Russia was the most attacking team in 2018, scoring 60% more goals than expected, likely due to home advantage.
- The Netherlands emerged as the underdog in 2022, scoring 52% more goals than expected.
- Among top teams, Portugal scored 40% more goals than expected in recent tournaments.
- Brazil was the most overrated team in both 2018 and 2022, scoring 32% and 40% fewer goals than expected, respectively.
## visualizations
A variety of visualizations were generated during the analysis to support the findings:

- **Bar Plots:** Displaying teams with the most wins and goals across tournaments.
- **Line Charts:** Highlighting trends in participation and performance over time.
- **KDE (Kernel Density Estimation) Plots:** Showcasing the distribution of goals scored across different teams.
- **Pie Charts:** Breaking down the share of wins, losses, and draws across teams.
- **Heatmaps:** Showing correlations between performance metrics, such as team wins and goals scored.
