# Data Science Exam project 2023
This project includes a main Rmarkdown file "Datascience_full_analysis.Rmd" containing the full analysis of the project "Predicting goals and results in the Premier League from the perspective of Tottenham Hotspur". The report of the project is attached as a PDF.file with the name: "DS_exam.pdf"

## CSV files in the repository
All of the data in this repository is extracted or preprocessed from a database called "The European soccer database" on Kaggle.com URL: https://www.kaggle.com/datasets/hugomathien/soccer. This database is too large to upload to github, thus the relevant data is gathered in the following CSV files: 

"spurs_raw.csv" is a file containing all Tottenham Hotspur (Spurs) matches between season 2008/2009 and 2015/2016 before any added variables or preprocessing.

"team_df.csv" is a file containing all the team information from the teams in the dataset. In the project it is used to identify all of Spurs' matches and the opposing teams.

"spurs.csv" is a preprocessed dataframe written from the Rmarkdown in order to add team ratings from https://www.fifaindex.com/teams/. This CSV is not used directly when running the script but was put into https://docs.google.com/spreadsheets/ in order to manually decode the team ratings.

"spurs_edit.csv" is the data frame after the manually coding of the team ratings. This data frame is used for the majority of the analysis.


 