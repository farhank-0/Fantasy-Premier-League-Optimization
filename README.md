# FPL-CAPSTONE

Farhan Kassam 
farhankassam0@gmail.com
https://github.com/farhank-0

This project attempts to predict player points in FPL via modelling and select a team using mixed integer linear programming in Python. The following is a break-down of the files included in this repository.

The notebooks folder contains three juypter-notebooks:

1. 1_Farhan_Kassam_FPL_Data_Cleaning_and_EDA <br>
    a. Contains data preprocessing and exploratory data analysis on the features and exports a cleaned csv file to use in the modelling notebook.
2. 2_Farhan_Kassam_FPL_Modelling <br>
    a. Contains the modelling process as well as hyper parameter optimization for the involved models with insights. The predictions from the best model are exported to a csv to use in the team select notebook.
3. 3_Farhan_Kassam_FPL_Team_Select_Conclusion <br>
    a. Contains team selection and comparison between predictions from the model, predictions from FPL, and the true results as well as a conclusion on the entire project.

The data folder contains 4 comma separated files:

- merged-gw
  - The original dataset from Vaastav's GitHub repository.
- cleaned
  - The cleaned data returned from the data cleaning notebook to use in modelling
- aggregated
  - Aggregated data to test our team selector MILP model on
- pred_df
  - The predictions from the model to be used in the team selector MILP model

