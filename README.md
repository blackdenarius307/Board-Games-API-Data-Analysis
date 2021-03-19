# Board-Games-An analysis

# Project Title: How have board games changed over the last 20 years?
Team Members: Max Browning & Zach Gibbs

Project Description & Outline: Using Board Game Atlas, a popular forum for rating games and connecting with other gamers, we will look into board game trends over the last five years and see how those compare to prior years.

# Defining Terms:
1. Mechanics - The style of game play by the players’ prominent action, such as dice rolling or deck building.
2. Mechanical Complexity - Number of mechanics in a game.
3. Player Counts - The number of players who can participate in the game at the same time.
4. One Player Games - Games that allow for a single player, but may include more. 

# Research Questions to Answer:
	- Has the prevalence of one player games increased over time in the top 100 games of each year?
		Null- If one player games have not become more prevalent over time, then the percentage of games 
		allowing one player will not have increased over time.
		Alternate- If one player games have become more prevalent over time, then the percentage of games 
		allowing one player will have increased over time.
	- Have games become more mechanically complex over time in the top 100 games of each year?
		Null- If games have not become more mechanically complex over time, then the average number of mechanics per game 
		will not increase year over year.
		Alternate- If games have become more mechanically complex over time, then the average number of mechanics per game 
		will increase year over year.
# Datasets to Be Used:
[Board Game Atlas API](https://www.boardgameatlas.com/api/docs) 

# Rough Breakdown of Tasks:
- [x] Pull data from API (Top 100 games per year from 2000 to now)
- [x] Clean data
	- [x] Remove unnecessary rows
	- [x] Decrypt Mechanic ID's for each game into a readable state
	- [x] Remove any game with no mechanics listed
- [x] Create summary dataframes for each year for mechanics and player count
- [x] Create charts showing trends over time

# Visualizations Created
![Scatter plot showing increase of one player games increasing over time](https://github.com/MaxBrowning/Board-Games-Group-F/blob/main/Images/One%20Player%20Game%20Scatter%20Plot.png)

![Box plot showing number of mechanics per game per year](https://github.com/MaxBrowning/Board-Games-Group-F/blob/main/Images/GameMechanicsPerYearBoxPlot.png)

![Linear regression of number of mechanics per game per year](https://github.com/MaxBrowning/Board-Games-Group-F/blob/main/Images/GameMechanicsPerYearScatter.png)
