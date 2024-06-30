# Thesis Score-driven Tensor Factor Model

## Description files

The files can be distributed in two sections: files relevant for the Simulation Study and files for the Empirical Application

### Files Simulation Study

_**Simulation Study.ipynb**_ : Jupyter Notebook code to run the two Simulation Studies. The code should be easy to interpret.  

_**Simulation_Results_K=1_d1=5_Check.xlsx**_ : Files that contain the results of the Simulation Study. The "Check" implies a manual check and this way it cannot be overwritten by the code _Simulation Study.ipynb_  
_**Simulation_Results_K=2_d1=5_Check.xlsx**_ : See above  
_**Simulation_Results_K=3_d1=5_Check.xlsx**_ : See above  
_**Simulation_Results_r=1_d1=10_Check.xlsx**_ : See above  
_**Simulation_Results_r=1_d1=10_Check.xlsx**_ : See above  
_**Simulation_Results_r=1_d1=10_Check.xlsx**_ : See above  

_**Result Analyser (Simulation).ipynb**_ : Program to analyze the six Excel files with the Simulation outcomes. This program presents the results with Boxplots.   
_**Calculations Simulation Study.xlsx**_ : Excel file that summarizes the six simulation results and includes some extra small calculations.    

### Files Empirical Application

_**Direction_of_Trade_Statistics.xlsx**_ : Trading data between 50 countries from Q1 1998 until Q4 2022.  
_**Country_Statistics.xlsx**_ : Statistics about the 50 countries, such as their GDP, continent, and income level.  

_**Empirical Application.ipynb**_ : Code that employs the score-driven tensor factor model on the two data files.  
_**Optimized_Parameters_Check.xlsx**_ : An Excel that potentially saves the intermediate optimization parameters from _Empirical Application.ipynb_ . This way, the results can be quickly ran from the program without having to estimate the parameters again.

