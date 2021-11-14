# European-Soccer-Dataset
This soccer database comes from Kaggle is well suited for data analysis.
The link to the Database is: https://www.kaggle.com/hugomathien/soccer

It contains data for soccer matches, players, and teams from several European countries (11 Countries) from 2008 to 2016. +25,000 matches +10,000 players 11 European Countries with their lead championship Seasons 2008 to 2016 Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates Team line up with squad formation (X, Y coordinates) Betting odds from up to 10 providers Detailed match events (goal types, possession, corner, cross, fouls, cards etc...) for +10,000 matches.

The dataset consists of 7 tables as following:  
1- Matches (contains all data for matches within the period described above i.e. Line-ups, scores, home and away teams)  
2- Country (specifies the 11 European countries that their data are being analyzed)  
3- League (lists the league in each country)  
4- Player (contains all the personal data of the players in consideration)  
5- player Attributes (contains all soccer related skills for each player)  
6- Team (Contains all teams' names from all the leagues in consideration)  
7- Team Attributes (Contains all teams' attributes and properties from all the leagues in consideration)

My Analysis includes mostly numpy and pandas with the help of matplot for the data visualization.  
1- It looks for correlation between various player attributes like age, stamina, acceleration etc.  
2- It looks for change in attributes with age.
3- It looks for the advantages of top players
4- It looks for scored goals per league and their classifications.

The following are the highlights of this Analysis:
1- Age has a negative effect on the physical related football skills like
strength, stamina and so on.
2- only about 1 player in 4 is left footed. Majority of players are right
footed.
3- Players’ weights have a negative impact on their speed.
4- Left footed players are slightly better at dribbling.
5- Home teams have advantage in scoring more goals than away teams.
6- Both the Spanish League (La Liga) and the English League (EPL) are the most in goals scored.
