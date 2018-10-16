# EEC731-Homework 4

Major Leagues
==================

NFL, MLB, NBA and Soccer scores
1. Set up a data science project structure in a new git repository in your GitHub account
2. Pick one of the game data sets depending your sports preference
https://github.com/fivethirtyeight/nfl-elo-game 
https://github.com/fivethirtyeight/data/tree/master/mlb-elo 
https://github.com/fivethirtyeight/data/tree/master/nba-carmelo 
https://github.com/fivethirtyeight/data/tree/master/soccer-spi 
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more regression models to determine the scores for each team using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub


Dataset
=============
The dataset I chose was the NBA predictions dataset.

This dataset contains information from the data behind The Complete History Of The NBA and our NBA Predictions.

nba_elo.csv contains game-by-game Elo ratings and forecasts back to 1946.


About the dataset
==================

How do you rate an NBA team across decades of play? One method is Elo, a simple measure of strength based on game-by-game results. We calculated Elo ratings for every NBA (and ABA) franchise after every game in history — over 60,000 ratings in total.

Elo ratings have a simple formula; the only inputs are the final score of each game, and where and when it was played. Teams always gain Elo points for winning. But they get more credit for upset victories and for winning by larger margins. Elo ratings are zero-sum, however. When the Houston Rockets gained 49 Elo points by winning the final three games of their Western Conference semifinal during the 2014-15 playoffs, that meant the Los Angeles Clippers lost 49 Elo points.

A rating of 1500 is approximately average, although the league average can be slightly higher or lower depending on how recently the league has expanded. (Expansion teams begin with a 1300 rating.) Select a team above, and zoom in to explore its history.

Reference: https://projects.fivethirtyeight.com/complete-history-of-the-nba/#warriors

--------------------------------------------------------------------------------------------------------------------------

Code for the project
====================
The notebook for this project can be found in the 1.0-EECS731-HW4.ipynb Jupyter notebook. 


Regression models
===================
Built Linear and Logistic Regression Models to predict scores of the teams, using other columns as features. 


-------------------------------------------------------------------------------------------------------------------------

