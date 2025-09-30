### Article materials
This repository contains the data, code, and figures used in the article. 
All materials are provided to ensure transparency and reproducibility.

Repo has the following structure.

1. Code - contains all python codes needed to fully reproduce the results of the article

01_data_pre_processing.py - Prepares and cleans raw data  
02_main.py - Runs the main results of the paper  
03_additional_analysis.py - Performs additional analysis (main paper)  
04_results_appendix.py - Runs all appendix results 

Each code is numbered according execution order. 


2. Output - contains all output materials graphs and figures used in paper

Figures are numbered according its appearance in the paper with additional figures on the appendix.

3. Data - contains all data used to generate outputs.

Two datasets 
a) raw_data_survey_qualtricks.csv contains raw data collected from survey.
b) processed_data_by_x.json file contains output of the data preprocessing. Output of the code 01_data_pre_processing.py
In order to generate processed data run the following command 
```bash
python 01_data_pre_processing.py
```



