# Renewable-Energy-Analysis-and-Prediction
Renewable Energy Data analysis and prediction for Germany

Renewable Energy (RE) analysis and prediction for Germany is done in this notebook. This dataset is taken from Kaggle ( source: https://www.kaggle.com/datasets/belayethossainds/renewable-energy-world-wide-19652022  ). The dataset is for all countries from 1965-2022. Some files were used for the analysis and are in the Data folder: 

03 modern-renewable-prod.csv : RE production sources e.g. from Solar, hydro, wind, etc.

04 share-electricity-renewables.csv: This is the share of electricity from RE. 

09 cumulative-installed-wind-energy-capacity-gigawatts : Installed capacity from Wind Energy.

13 installed-solar-PV-capacity.csv : Installed capacity from Solar Energy.

17 installed-geothermal-capacity.csv : Installed capacity from Geothermal Energy.

The files below are created during the execution of the notebook.

20model_Factors_Renewable.csv : Features for modelling. Some features are computed in the notebook and are included in this csv file.

model_pre.csv: Predicted results file.

Initially, Exploratory Data Analysis is done to the data aiming over Germany. Comparison of ‘percentage’ generated from RE in Germany, Europe and World. Different sources of RE generation and its comparison is done for World and Germany. Other countries could also be selected for this comparison.  

In the prediction part, the features ‘Total Installed capacity’ is computed from files mentioned above. The Data for the second feature ‘Investment in RE’ by German government’s is taken from https://de.statista.com. Initially only Linear Regression is applied and later feature engineering is done. The results are then evaluated.   
