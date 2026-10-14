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
