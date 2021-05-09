# Predicting-NBA-Salaries-Using-Player-Metrics

# Introduction
# Goals
In this project, we are attempting to accurately predict an NBA basketball player’s salary as a function of several metrics gathered about their basketball gameplay. We want to answer the following question: given a player’s performance over a set of metrics (commonly referred to as “Advanced Metrics”, since they are computed with a level of analysis beyond the most basic metrics collected about a player), what is their salary likely to be?

# Background
The National Basketball Association (NBA) is the largest and most competitive men’s professional basketball league in North America. It is comprised of 30 teams in the United States and Canada, and at any time, each team has a roster of about 15-20 players. The NBA plays basketball in a cycle of seasons that starts in October and ends in April of each year - during this time, each team plays 82 games. Players on these teams are paid salaries on a per-season basis. These salaries can range from thousands of US dollars to tens of millions of US dollars, and they are governed and limited by a complicated set of rules that limits teams to paying players a certain amount based on various parameters about the player and the team. However, at the core, the assumption is that better players are paid more. This report is trying to figure out if there is a relationship between a player’s skill at the game of basketball, as measured by various metrics, and the amount they are paid.

There’s lots of variables in the data, but the meat of it is 19 “advanced statistics”. These range from things like the percentage of times the player was able to assist a teammate in scoring (AST%) to the rate at which the player got involved with attempting to score (USG%) to an attempted comprehensive metric about the total value a player provides a team (VORP). In addition to these advanced stats, there are more mundane variables, like the team a player is on, the position/role they typically serve, and their age. The response variable will be Salary, which is the amount the player was paid that year in US dollars.

There’s a few important things to note about this dataset. First, a specific player can play for more than one team per season - often, teams will “trade” players (swap them for some competitive advantage) in the middle of a season.

Second, this dataset represents multiple seasons of NBA players’ data - player data from the last 4 seasons are used: 2016-17, 2017-18, 2018-19, and 2019-20. The last season was cut short because of the pandemic, but the majority of the games were played - so the predictor statistics are still available for players.

Third, it’s possible that salary is a lagging indicator of a player’s skill level. If the player’s skill level is accurately represented by the metrics we have chosen as our predictor variables, it’s possible that as a player ages and declines in quality, they are still overpaid to an extent, because their contracts were written earlier, when they were younger and had better statistics. Our report doesn’t explore this possiblity of linking a player’s statistics in a given season to their salary in a later season, but it’s a common sense possiblity that could be a confounding factor in our search for a good model.

# Appendix
## Citations:
All data for this project was downloaded from basketball-reference.

The initial dataset (which we appended with subsequent seasons) was found on kaggle, and served as the inspiration for the project. It was appended with additional data points from the above site to bring the total number of observations higher.

Salary data was also downloaded from ESPN’s historical NBA salary database.

## Authors:
Chaaru Dingankar
Hoa Le
Sreyashi Das
