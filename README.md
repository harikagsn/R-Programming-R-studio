## English Premier League Soccer Standings
The English Premier League (EPL) is a major soccer league in Great Britain consisting of 20 teams.  The season begins in August and concludes in May with each team playing each other team exactly twice (home and away).  Each team plays 38 games in a season while the total number of games is 380.  A team receives 3 points for a win and if the game is tied, both teams receive 1 point; no points are awarded for a loss.
The EPL game results are found at http://www.football-data.co.uk/englandm.php under the heading Premier League. 
Your Assignment: Develop a function with the inputs of date and season that returns the league standings for the date and season specified.  The season specified should, at a minimum, accept the current seasons and both of the two most recently completed seasons in order for your submission to be eligible for full credit.  
Data:
•	The csv data files available via the weblink provided above contain a lot of information that is not needed for this assignment.  The critical information is:
o	Date (in day/month/year format) 
o	Home Team
o	Away Team
o	FTHG – the number of goals scored by the home team
o	FTAG – the number of goals scored by the away team
o	FTR – the result of the match (H indicates home team won, A indicates the away team won, D indicates a draw or tie)
•	The data for previous seasons is static (unchanging) but the data for the current season changes whenever a game is played.  Your function should read the data directly from the web pages and not from a csv file stored on your hard drive.  The read.csv()command will do this easily where the url is used instead of the filename.
•	Notice that the year in the date column sometimes appears as a 2-digit value but sometimes it appears as 4-digit value.  Your function will need to address this issue.
•	Check that the data column names are consistent from season to season; if they are not, you need to address this issue in your function.


![image](https://user-images.githubusercontent.com/35073729/189964442-634d3a27-4c9e-4bd8-88a9-c2dd5322520e.png)
