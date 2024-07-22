# NBA-Data-2010-2024 🏀
This repository contains CSV files containing comprehensive NBA data spanning from the year 2010 to 2024, offering valuable insights into player statistics, team performances, game outcomes, and more.


> [!IMPORTANT]  
> In the future, I plan to update this dataset twice a year, after the end of the regular season and after the end of the playoffs.


## Schema of box scores ([play_off_box_scores_2010_2024.csv](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/play_off_box_scores_2010_2024.csv), [regular_season_box_scores_2010_2024_part_1.csv](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/regular_season_box_scores_2010_2024_part_1.csv), [regular_season_box_scores_2010_2024_part_2.csv](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/regular_season_box_scores_2010_2024_part_2.csv), [regular_season_box_scores_2010_2024_part_3.csv](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/regular_season_box_scores_2010_2024_part_3.csv))

### Dimensions
- **season_year**: The year of the basketball season.
- **game_date**: The date of the game.
- **gameId**: Unique identifier for the game.
- **teamId**: Unique identifier for the team.
- **teamCity**: The city where the team is based.
- **teamName**: The name of the team.
- **teamTricode**: A three-letter code representing the team.
- **teamSlug**: A unique identifier for the team.
- **personId**: Unique identifier for the person (player).
- **personName**: The name of the person (player).
- **position**: The position of the player.
- **comment**: Any additional comments or notes.
- **jerseyNum**: The jersey number of the player.

### Metrics
- **minutes**: The number of minutes played by the player.
- **fieldGoalsMade**: The number of field goals made by the player.
- **fieldGoalsAttempted**: The number of field goals attempted by the player.
- **fieldGoalsPercentage**: The shooting percentage for field goals.
- **threePointersMade**: The number of three-pointers made by the player.
- **threePointersAttempted**: The number of three-pointers attempted by the player.
- **threePointersPercentage**: The shooting percentage for three-pointers.
- **freeThrowsMade**: The number of free throws made by the player.
- **freeThrowsAttempted**: The number of free throws attempted by the player.
- **freeThrowsPercentage**: The shooting percentage for free throws.
- **reboundsOffensive**: The number of offensive rebounds by the player.
- **reboundsDefensive**: The number of defensive rebounds by the player.
- **reboundsTotal**: The total number of rebounds by the player.
- **assists**: The number of assists by the player.
- **steals**: The number of steals by the player.
- **blocks**: The number of blocks by the player.
- **turnovers**: The number of turnovers by the player.
- **foulsPersonal**: The number of personal fouls committed by the player.
- **points**: The total number of points scored by the player.
- **plusMinusPoints**: The plus-minus statistic for the player, indicating the team's score differential when the player is on the court.

## Schema of game totals ([play_off_totals_2010_2024.csv](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/play_off_totals_2010_2024.csv), [regular_season_totals_2010_2024.csv](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/regular_season_totals_2010_2024.csv))

### Dimensions
- **SEASON_YEAR**: The year of the NBA season.
- **TEAM_ID**: Unique identifier for the team.
- **TEAM_ABBREVIATION**: Abbreviated name of the team.
- **TEAM_NAME**: Full name of the team.
- **GAME_ID**: Unique identifier for the game.
- **GAME_DATE**: Date of the game.
- **MATCHUP**: Matchup details indicating the teams involved.
- **WL**: Outcome of the game (Win or Loss).

### Metrics
- **MIN**: Total minutes played in the game.
- **FGM**: Field goals made.
- **FGA**: Field goals attempted.
- **FG_PCT**: Field goal percentage.
- **FG3M**: Three-point field goals made.
- **FG3A**: Three-point field goals attempted.
- **FG3_PCT**: Three-point field goal percentage.
- **FTM**: Free throws made.
- **FTA**: Free throws attempted.
- **FT_PCT**: Free throw percentage.
- **OREB**: Offensive rebounds.
- **DREB**: Defensive rebounds.
- **REB**: Total rebounds.
- **AST**: Assists.
- **TOV**: Turnovers.
- **STL**: Steals.
- **BLK**: Blocks.
- **BLKA**: Opponent's blocks.
- **PF**: Personal fouls.
- **PFD**: Personal fouls drawn.
- **PTS**: Total points scored.
- **PLUS_MINUS**: Plus-minus statistic.
- **GP_RANK**: Rank based on games played.
- **W_RANK**: Rank based on wins.
- **L_RANK**: Rank based on losses.
- **W_PCT_RANK**: Rank based on win percentage.
- **MIN_RANK**: Rank based on minutes played.
- **Ranks for various statistical categories like field goals made, rebounds, assists, etc., indicated by suffix _RANK.**
- **AVAILABLE_FLAG**: Indicates if the data for this row is available.

## Usage
These tables can be queried to analyze player performance, team statistics, and game trends over different seasons. I personally upload data to Google Cloud BigQuery and analyze it using SQL.


## Authors

- [@NocturneBear](https://github.com/NocturneBear)

## License

[MIT](https://github.com/NocturneBear/NBA-Data-2010-2024/blob/main/LICENSE)
