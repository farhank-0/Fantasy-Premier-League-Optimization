# FPL-CAPSTONE

Farhan Kassam <br>
farhankassam0@gmail.com <br>
https://github.com/farhank-0<br>

This project attempts to predict player points in FPL via modelling and select a team using mixed integer linear programming in Python. The following is a break-down of the files included in this repository.

The `summary-reports` folder contains one file:

1. `Farhan_Kassam_FPL_Capstone_Report.pdf` <br>
    - Final capstone written report

**NOTE TO RUN THE JUYPTER NOTEBOOKS YOU MUST HAVE THE FOLLOWING ENVIRONMENT**
- `capstone.yml` 

The `notebooks` folder contains three juypter-notebooks:

1. `1_Farhan_Kassam_FPL_Data_Cleaning_and_EDA.ipynb` <br>
    - Contains data preprocessing and exploratory data analysis on the features and exports a cleaned csv file to use in the modelling notebook.
2. `2_Farhan_Kassam_FPL_Modelling.ipynb` <br>
    - Contains the modelling process as well as hyper parameter optimization for the involved models with insights. The predictions from the best model are exported to a csv to use in the team select notebook.
3. `3_Farhan_Kassam_FPL_Team_Select_Conclusion.ipynb` <br>
    - Contains team selection and comparison between predictions from the model, predictions from FPL, and the true results as well as a conclusion on the entire project.

The `data` folder contains four comma separated files:

1. `merged-gw.csv` <br>
    - The original dataset from Vaastav's GitHub repository.
2. `cleaned.csv` <br>
    - The cleaned data returned from the data cleaning notebook to use in modelling
3. `aggregated.csv` <br>
    - Aggregated data to test our team selector MILP model on
4. `pred_df.csv` <br>
    - The predictions from the model to be used in the team selector MILP model

The `post_bootcamp` folder contains a `data` folder and a `notebooks` folder for all changes that occur after the bootcamp and may replace previous breakdown in the future.
Currently, the `notebooks` folder contains:
1. `1_FPL_API_get_data` <br>
    - Using the FPL API to retrieve and sort data using `pandasql`, saves outputs to csv files in `data` folder.

**References**
1. Anand, Vaastav. (2023). <i>FPL Historical Dataset</i>. https://github.com/vaastav/Fantasy-Premier-League/
2. Khalid, Irfan. Sep, 2021. <i>How to Build A Fantasy Premier League Team with Data Science</i>. https://towardsdatascience.com/how-to-build-a-fantasy-premier-league-team-with-data-science-f01283281236.
