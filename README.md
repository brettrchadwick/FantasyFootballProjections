# FantasyFootballProjections

To work with a large dataset containing NFL player and game statistics in order to conduct machine learning algorithms that will allow for predictions future performance. The data will be cleaned using python and Scikit-learn algorithms will be implemented for machine learning. Data will be further explored and visualized using Tableau to provide a story and explanation of specific key features of player statistics.

# Data Source:
This data was obtained from Kaggle and originally scraped from the web. Data on individual players and games dates to the 1940s. This dataset gives us the opportunity to investigate details about players that can be used to predict their future performance for the purpose of developing a fantasy football team. We’ll be filtering the data for the past few seasons. We’ll break the 

Machine Learning:
We will explore the following machine learning algorithms to determine the best fit for our fantasy football model: 
•	Nearest Neighbor
•	Decision Trees
•	Support Vector Machine (SVM)
•	Random Forest
•	Neural Networks

# Extra Information about the Data
Dataset Details:
Player Statistics fields:
*	Player ID: The assigned ID for the player.
*	Name: The player's full name.
•	Position: The position the player played abbreviated to two characters. If the player played more than one position, the position field will be a comma-separated list of positions (i.e. "hb,qb").
•	Height: The height of the player in feet and inches. The data format is -. So 6-5 would be six feet and five inches tall.
•	Weight: The weight of the player in pounds.
•	Current Team: The three-letter code of the team the player plays for. This is null if they are not currently active.
•	Birth Date: The day, month, and year the player was born. This is null if unknown.
•	Birth Place: The city, state or city, country the player was born in. This is null if unknown.
•	Death Date: The day, month, and year the player died. This is null if they are still alive.
•	College: The name of the college they played football at. This is null if they did not play football in college.
•	High School: the city, state or city, country the player went to high school. This is null if the player didn't go to high school or if the school is unknown.
•	Draft Team: The three letter code of the team that drafted the player. This is null if the player was not drafted.
•	Draft Position: The draft position number the player was taken. Again, null if the player was not drafted.
•	Draft Round: The round of the draft the player was drafted in. Null if the player was not drafted.
•	Draft Position: The position the player was drafted at as a two-letter code. Null if the player was not drafted.
•	Draft Year: The year the player was drafted. Null if the player was not drafted.
•	Current Salary Cap Hit: The player's current salary hit for their current team. Null if the player is not currently active on a team.
•	Hall of Fame Induction Year: The year the player was inducted into the NFL Hall of Fame. Null if the player has not been inducted into the HOF yet.
This dataset contains the following game stats fields:
•	Player ID: The assigned ID for the player.
•	Year: The year the game took place.
•	Date: The date the game took place.
•	Game Number: The number of the game when all games in a season are numbered sequentially.
•	Age: The age of the player when the game was played. This is in the format -. So 22-344 would be 22 years and 344 days old.
•	Team: The three-letter code of the team the player played for.
•	Game Location: One of H, A, or N. H=Home, A=Away, and N=Neutral.
•	Opponent: The three-letter code of the team the game was played against.
•	Player Team Score: The score of the team the player played for.
•	Opponent Score: The score of the team the player played against. You can use this field and the last field to determine if the player's team won.
Passing Stats:
•	Passing Attempts: The number of passes thrown by the player.
•	Passing Completions: The number of completions thrown by the player.
•	Passing Yards: The number of passing yards thrown by the player.
•	Passing Rating: The NFL passer rating for the player in that game.
•	Passing Touchdowns: The number of passing touchdowns the player threw.
•	Passing Interceptions: The number of interceptions the player threw.
•	Passing Sacks: The number of times the player was sacked.
•	Passing Sacks Yards Lost: The cumulative yards lost from the player being sacked.
Rushing Stats:
•	Rushing Attempts: The number of times the the player attempted a rush.
•	Rushing Yards: The number of yards the player rushed for.
•	Rushing Touchdowns: The number of touchdowns the player rushed for.
Receiving Stats:
•	Receiving Targets: The number of times the player was thrown to.
•	Receiving Receptions: The number of times the player caught a pass thrown to them.
•	Receiving Yards: The number of yards the player gained through receiving.
•	Receiving Touchdowns: The number of touchdowns scored through receiving.
Kick/Punt Return Stats
•	Kick Return Attempts: The number of times the player attempted to return a kick.
•	Kick Return Yards: The cumulative number of yards the player returned kicks for.
•	Kick Return Touchdowns: The number of touchdowns the player scored through kick returns.
•	Punt Return Attempts: The number of times the player attempted to return a punt.
•	Punt Return Yards: The cumulative number of yards the player returned punts for.
•	Punt Return Touchdowns: The number of touchdowns the player scored through punt returns.
