# offense wins championships

The saying goes defense wins championships. However in the last few years, the rise of Steph Curry and crew has changed how every team is built. Timofey Mosgov went from being vital on the Cleveland Cavaliers to obsolete after Steph started to shoot from the logo. SO what happened? :confused:

This project aims to create a sort of game using the last half decade of finals data to see if someone could predict the finals winner given a blind resume of a team from all teams that made the playoffs in the last 50 years.

## Data Extraction and Cleaning

- Scrapped and read from [Basketball Reference](https://www.basketball-reference.com/) and the [NBA website](https://stats.nba.com/teams)
- Teams consolidated names and abbreviations read from [this Wikipedia list](https://en.wikipedia.org/wiki/wikipedia:WikiProject_National_Basketball_Association/National_Basketball_Association_team_abbreviations)
- For teams that changed names or locations, the names and abbreviations were cross-referenced manually on basketball reference's site for that particular season. This is documented on the `import_clean.ipynb` Jupyter notebook

### Instructions **

** These instructions are subject to change as the project is updated

- Have Jupyter notebooks compatibility with your machine and editor of choice; either with [Anaconda or miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html) for a lighter download.
- Download the all `.ipynb` files from this repository, and run in this order

> - `import_clean.ipynb` and `team_data_import.ipynb` to scrape and read html tables and clean them before exploring data features
> - `data_wrangling.ipynb` to explore missing feature values, and see documentation (on Jupyter notebook) on how decisions were made to handle the missing data
> - `EDA_finals.ipynb` to see some descriptive statistics and correlations for data on finals appearing teams from the last decade

### Next Steps

- Exploratory Data Analysis of selected data for all teams stats
- Explore player and coaches career and playoff experiences
- Extract feature importances and determine best model representations of data to create prediction game
