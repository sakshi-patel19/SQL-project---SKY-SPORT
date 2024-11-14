# SQL Project-SKY SPORT

Sky Sports Channel's coverage of the FIFA World Cup includes a post-match TV program called Football Digest: Post Match Analysis. On the show, Football Pundits discuss insights and gameplay derived by the Sports Analyst using backend data analysis.

## Role of the Sports Analyst

The Sports Analyst is responsible for:
Analyzing data from each match to provide detailed statistics.

Highlighting key moments, performances, and tactical decisions.

Presenting insights on the program, helping viewers understand each match's events and contributing factors to a team's success or failure.


## Data Analysis with MySQL

To carry out these tasks, by the uses of MySQL to access two tables:

group_stage_team_stats: Contains information on each team's performance in each game.

overall_wc_stats: Contains data on individual team statistics.

Both tables are updated with each match.

## group_stage_team_stats

This table includes columns such as:

team_name: Name of the team.

game_date: Date of the game.

goals_scored: Goals scored by the team.

goals_conceded: Goals conceded by the team.

shots_on_target: Number of shots on target.

shots_off_target: Number of shots off target.

possession: Percentage of possession.
and many more.

## overall_wc_stats
This table includes columns such as:

player_name: Name of the player.

position: Player's position.

number_of_appearances: Number of appearances.

goals_scored: Goals scored by the player.

assists: Number of assists.

yellow_cards: Number of yellow cards.

red_cards: Number of red cards.
and other relevant information.

Both tables contain a column team, which is common and can be used for joining.

## Comprehensive Analysis

The analyst uses this data to provide insights into each match, highlighting key moments, performances, and tactical decisions made by the coaches. These insights are presented on the program, giving viewers a deeper understanding of each match's events and the factors that contributed to a team's success or failure.

## Results and Insights

The detailed analysis provided by the Sports Analyst translates into various insights shared on the Football Digest: Post Match Analysis program. These may include:
Performance Metrics: Breakdown of how each team performed in different aspects of the game such as attacking, defending, and possession.

Player Analysis: Highlighting standout performances by individual players, their contributions to the team, and key statistics like goals, assists, and defensive actions.

Tactical Insights: Explanation of the tactical decisions made by coaches, such as formations, substitutions, and strategies employed during different phases of the game.

Key Moments: Identification of pivotal moments that influenced the outcome of the match, such as goals, saves, and critical fouls.

Comparative Analysis: Comparison between teams’ performances in group stage and overall tournament statistics to provide context on their progress and strategies.

### These insights help viewers gain a comprehensive understanding of the game, enhancing their overall viewing experience of the FIFA World Cup matches.
