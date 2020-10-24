# Board-Games-Group-F

# Project Title: How have the last 5 years of board game production changed from prior years?
 Team Members: Max Browning & Zach Gibbs
Project Description & Outline: Using Board Game Atlas, a popular forum for rating games and connecting with other gamers, we will look into board game trends over the last five years and see how those compare to prior years.

# Defining Variables:
1. Mechanics - The style of game play by the players’ prominent action, such as dice rolling or deck building.
2. Mechanical Complexity - Number of mechanics in a game.
3. Player Counts - The number of players who can participate in the game at the same time.

# Research Questions to Answer:
	- Have games become more mechanically complex over time?
		Null- If games have not become more mechanically complex over time, then games from the last 5 years will not have more
		mechanics than games from previously.
		Alternate- If games have become more mechanically complex over time, then games from the last 5 years will have more
		mechanics than games from previously.
	- Has the prevalence of one player games increased over time?
		Null- If one player games have not become more prevalent over the last 5 years, then the percentage of games 
		allowing one player will not have increased in the last 5 years.
		Alternate- If one player games have become more prevalent over the last 5 years, then the percentage of games
		allowing one player will have increased in the last 5 years.

# Datasets to Be Used:
[Board Game Atlas API](https://www.boardgameatlas.com/api/docs) 

# Rough Breakdown of Tasks:
- [x] Pull data from API (Top 100 games per year from 2000 to now)
- [x] Clean data
	- [x] Remove unnecessary rows
	- [x] Decrypt Mechanic ID's for each game into a readable state
	- [x] Remove any game with no mechanics listed
- [ ] Create summary dataframes for each year for mechanics and player count
- [ ] Create charts showing trends over time
