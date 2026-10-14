Regression 2.1: Predicting the goal difference of a match
This notebook constructs a linear regression model to predict the goal difference in a FIFA World Cup 2026 match.
Predictors and data set
The study is based on 104 match records. The result is goal_difference. It employs eight pre-match predictors: home and away FIFA ranks; home prior matches; home and away prior goals-for averages; home and away prior goals-against averages; and host advantage.

Run:
1. Place the notebook and the source data file(s) that you need into your project folder.
2. In the data-loading field of the notebook, change file_path to wherever you have the FBref file on your computer.
3. Run the notepad cells from the top to the bottom. It loads and stores regression_2_1_dataset.csv, trains the model, then tests the model with a date based train/test split keeping matches on each date together.
The notebook is written in Python with pandas, NumPy, scikit-learn, and matplotlib.
Regression 2.2: Team Goals Number Prediction

The research uses a linear regression model to estimate the number of goals scored by a team in one match in the FIFA World Cup 2026.
Training data
The code reads in the file world_cup_2026_enriched_matches.csv and expands the 104 matches into 208 team-matches. The answer variable is goals_scored;
The model has eight pre-match predictors: team FIFA rank, opponent FIFA rank, team prior goals-for average, opponent prior goals-against average, home/away, team rest days, opponent rest days, and days since tournament started.

Run 
1. Put the notebook and the CSV file in the same folder.
2. Open the regression2.2(1).ipynb file in Jupyter Notebook or JupyterLab.
3. Run the cells in the notepad from top to bottom.
This notebook is in Python and uses pandas, scikit-learn, matplotlib and seaborn. It analyzes the model with a chronological train/test split and compares it to a training-mean baseline.
