# Using Machine Learning to Predict Whether a Game is a Win or a Loss in League of Legends

In this notebook we will acquire player data from Riot's API using riotwatcher (https://github.com/pseudonym117/Riot-Watcher). This data is from the player's last 100 matches. 

The data we are interested in for the purposes of this notebook are the kills, deaths assists and gold earned by that player for each game. We then do some cleaning of this data. 

Finally, we use machine learning to build a logistic regression model that predicts whether that game is a win or a loss and review our results using statistical metrics such as precision, recall and F1 score.

You can easily edit this notebook to analyze your own data. GLHF!
