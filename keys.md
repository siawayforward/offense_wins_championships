# dataframe-keys

This file lists the column keys for each dataset used or retrieved in this project

***

## Players

### Seasonal breakdown of per game statistics

- Player - Player first and last names
- Pos - Position on court. Can be PG, SG, SF, PF, C or a combination of some
- Age - Age of player
- Tm - Team a player is on (see team key notes below)
- G - Total games played in a season
- GS - Total games starts in a season
- MP - Average minutes played per game
- FG - Average number of total field goals made per game
- FGA - Average number of total field goals attempted per game
- FG% - Total field goal percentage (FG/FGA)
- 3P - Average number of 3-point field goals made per game
- 3PA - Average number of 3-point field goals attempted per game
- 3P% - Three point field goal percentage (3P/3PA)
- 2P - Average number of 2-point field goals made per game
- 2PA - Average number of 2-point field goals attempted per game
- 2P% - Two point field goal percentage (2P/2PA)
- eFG% - Effective total field goal percentage, a scaled ratio accounting for the higher value of 3P. It is calculated as: (2P + 0.5 * 3P) / FGA
- FT - Free throws made
- FTA - Free throws attempted
- FT% - Free throw conversion percentage (FT/FTA)
- ORB - Average offensive rebounds collected per game
- DRB - Average defensive rebounds collected per game
- TRB - Total average rebounds collected per game
- AST - Average number of assists generated per game
- STL - Average number of steals collected per game
- BLK - Average number of blocked shots per game
- TOV - Average number of turnovers per game
- PF - Average number of personal fouls committed per game
- PTS - Average number of total points scored per game
- Year - Year of the NBA season's conclusion
- Champ - Binary indicator for whether a player's team was the champion that year (1 = Yes, 0 = No)
- Runner-Up - Binary indicator for whether a player's team lost in the finals that year (1 = Yes, 0 = No)

***

## Coaches

### Season Breakdown of Career, Regular, and Post season records

Current season, regular season = CR  
Current season, playoffs = CP  
Franchise, regular season = FR  
Franchise, playoff = FP  
Career regular season (experience) = Car  
Career playoffs = Car.P  

- Coach - Name of the team's coach
- Team - Team the coach works for (see team key notes below)
- F-Seasons - Total seasons spent as a head coach in the franchise
- Car-Seasons - Career seasons spent coaching
- CR-G - Total games coached, current regular season
- CR-W - Total games won, current regular season
- CR-L - Total games lost, current regular season
- FR-G - Total games coached for the francise in the regular season
- FR-W - Total games won for the francise in the regular season
- FR-L - Total games lost for the francise in the regular season
- Car-G - Career games coached
- Car-W - Career games won
- Car-L - Career games lost
- Car-W% - Career games win percentage (Car-W/Car-G)
- CP-G - Total games coached, current playoff season
- CP-W - Total games won, current playoff season
- CP-L - Total games lost, current playoff season
- FP-G - Total games coached for the franchise in the playoffs
- FP-W - Total games won for the franchise in the playoffs
- FP-L - Total games lost for the franchise in the playoffs
- Car.P-G - Career playoff games coached
- Car.P-W - Career playoff games won
- Car.P-L - Career playoff games lost
- Year - Year that the season ended on
- Champ - Binary indicator for whether a coach's team was the champion that year (1 = Yes, 0 = No)
- Runner-Up - Binary indicator for whether a coach's team lost in the finals that year (1 = Yes, 0 = No)

***

## Teams

Names of team abbreviations. This list can be found on the `teams.csv` file that will be generated once the `import_clean.ipynb` file is run.
