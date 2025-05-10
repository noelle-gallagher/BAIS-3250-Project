# BAIS-3250-Project
Repository for final project looking at top 25 college football teams of the past 4 seasons
## Data: Sources
2024 AP Poll College Football Rankings, Final Rankings - ESPN https://www.espn.com/college-football/rankings/_/poll/1/week/1/year/2024/seasontype/3
This source, scraped off of the ESPN website, is the main statistics such as team, final rank, and wins and losses for the top 25 ranked teams at the end of each season. For this project, I used the previous four seasons (2021-2024)

2024 FBS Team Defense Statistics | The Football Database - https://www.footballdb.com/college-football/stats/teamstat.html?group=D&cat=T&yr=2024&lg=FBS
The source, scraped off the the Football Database website, has the main defensive categories for all College football teams, by season. I also used the 2021-2024 season for this website.

2024 FBS Team Offense Statistics | The Football Database - https://www.footballdb.com/college-football/stats/teamstat.html?group=O&cat=T&yr=2024&lg=FBS
Similar to scraping for the defensive statistics, this source is also from the Football Database, and it has the major offensive statistics for each FBS team, by season.

## Runing the Files
To begin, fun the "project_cleaning_scraping.ipynb" file, as it scrapes all of the websites, cleans the data, and prepares it in a csv file to be used for the analysis.

the "2021-2024stats.csv" file is the final dataframe following the cleaning and scraping of the inital data. This will be imported as a csv into a pandas dataframe for the analysis part of this project on a different Jupyten Notebook.

Next, run the "BAIS3250_project_analysis.ipynb". This file contains the hypothesis tests, regression and classification models based on the main questions for this project, including the target variables of Points/Game, Points Allowed/Game, and how the top 5 teams compare to the other teams.
