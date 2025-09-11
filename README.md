# andreas-football-predictor-project
A repository with all the files and documentation from my self challenged machine learning project where I created a model which predicts the outcomes of Premier League football matches.

# Project Purpose
The main purpose of this project was to create and train a machine learning model which predicts the outcome of Premier League football matches, which can then be used to make live predictions during the current Premier League season.
Then, the outcomes of these live predictions can be displayed in a dashboard in order to show how many correct predictions the model makes each week, and show the trend of its prediction accuracy over the course of the season, to see if the model needs to be retrained.

# Link to Tableau Public dashboard
https://public.tableau.com/app/profile/andreas.wong/viz/PremierLeagueMatchPredictions/PremierLeagueMatchPredictorDashboard?publish=yes

# Elements
Files called '20xx-20xx Fixtures' contain the Premier League fixtures for each season, per gameweek. These are used in the Live Predictor.

Files called '20xx-20xx Results' contain the results of each Premier League fixture per gameweek. These are used in the Live Predictor

'Documentation' contains the Data Flow Diagram and Process Flow Diagram which are displayed below in the README file.

'Encode Tables' contains each Premier League team (across all seasons) and their corresponding numerical value, created via encoding when training the machine learning model.

'Lookup tables' contains the matchweek lookup file, used to match the date of a game with a gameweek of a season in the tableau dashboard, to enable the showing of weekly prediction accuracies.

'Stored prediction latest' contains the predictions the model has made for the upcoming gameweek

'Stored predictions' contains the predictions made by the model for each gameweek

'Stored predictions_results' contains the predicted results and actual result of each gameweek's games

'Stored predictions_results_master' contains a masterlist of every single gameweek's predicted and actual results combined into one dataframe.

'Team data' contains the data used to train the machine learning model, and to make the live predictions

Football_Predictor_Second_Iteration.ipynb is the file containing the code to (re)train the machine learning model

Live_Predictor_202526.ipynb is the file containing the code used to make live predictions on each gameweek's results.

football-match-prediction-model.pkl is the Python object associated with the machine learning model.


# Data Flow Diagram
![DataFLowDiagram](Documentation/FootballPredictorDataFlowDiagram.png)

# Detailed Process Flow Diagram
![DetailedProcessDiagram](Documentation/FootballPredictorDetailedDiagram.png)

