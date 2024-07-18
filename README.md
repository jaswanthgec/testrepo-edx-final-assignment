# Predicting Postseason Success in NCAA Basketball Using Advanced Metrics
the final assignment of the Machine Learning with Python: A Practical Introduction cource offered by EDX.

The CSV file contains data on college basketball teams with 1,406 entries and 24 columns. Here's a detailed breakdown of the columns:

TEAM: The name of the team.
CONF: The conference the team belongs to.
G: The number of games played.
W: The number of games won.
ADJOE: Adjusted Offensive Efficiency (points scored per 100 possessions).
ADJDE: Adjusted Defensive Efficiency (points allowed per 100 possessions).
BARTHAG: A team's overall efficiency or power rating.
EFG_O: Effective Field Goal Percentage (offense).
EFG_D: Effective Field Goal Percentage (defense).
TOR: Turnover Rate (offense).
TORD: Turnover Rate (defense).
ORB: Offensive Rebound Percentage.
DRB: Defensive Rebound Percentage.
FTR: Free Throw Rate (offense).
FTRD: Free Throw Rate (defense).
2P_O: Two-Point Shooting Percentage (offense).
2P_D: Two-Point Shooting Percentage (defense).
3P_O: Three-Point Shooting Percentage (offense).
3P_D: Three-Point Shooting Percentage (defense).
ADJ_T: Adjusted Tempo (possessions per 40 minutes).
WAB: Wins Above Bubble (a metric indicating how many more wins a team has compared to a typical bubble team).
POSTSEASON: Postseason outcome (e.g., Champions, E8 for Elite 8).
SEED: Seed in the NCAA tournament.
YEAR: The year of the season.

The POSTSEASON column represents the outcome of each team's performance in the postseason tournaments. This includes different stages of progress such as:

Champions: The team won the tournament.
Finals: The team reached the final game but did not win.
F4: The team reached the Final Four.
E8: The team reached the Elite Eight.
S16: The team reached the Sweet Sixteen.
R32: The team reached the Round of 32.
R64: The team reached the Round of 64.
2ND: The team made it to the second round.
1ST: The team made it to the first round.
This column is crucial as it indicates the farthest stage a team achieved in the tournament, providing insight into their postseason success. Since not all teams make it to the postseason, many entries in this column are null, representing teams that did not qualify for the tournament.
