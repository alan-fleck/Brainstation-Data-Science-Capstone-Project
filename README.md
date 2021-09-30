# Brainstation-Capstone-Project
## Eyes in the Sky: Predicting Aircraft Damage Caused by Bird Strikes Using Machine Learning

## Author: Alan Fleck

Following is a description of the files contained in this project, as well as a recommendation of the order of visualization. Please note that the Plotly plots from Part 1 and Part 4 are not rendered by Github. For this reason, they are displayed here as static. Please follow the instructions in the these two notebooks to view the interactive versions of the plots in your Jupyter Notebook.

	1.	Part_1_PreProcessing_EDA.ipynb
Background, Data Preprocessing and Exploratory Data Analysis (EDA) for this project. Using Plotly, we looked at the relationship between the different features with the number of bird strikes, the number of damaging strikes to the aircrafts, and the damage rate.

	2.	Part_2_SupervisedML.ipynb
Part 2 of this project aimed to identify the coefficients associated with damaging strikes, and to use supervised machine learning to predict the outcome of these incidents.
For the former objective, a statistical model using Logistic Regression was used. For the latter objective, the initial predictive models explored were Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machines (SVM) and Decision Trees, as well as advanced models like Random Forest and XGBoost.

	3.	Part3_Neural_Networks.ipynb
In Part 3 of this project, we built a neural network to predict damaging bird strikes on airplanes. This notebook is a natural extension to Part 2, and the results of the advanced model built here were compared to the results of the models from the previous notebook.

	4.	Part_4_TimeSeries.ipynb
In Part 4 of this project, we used time series analysis to describe temporal trends and seasonality in bird strikes - thus expanding the insights from the EDA of Part 1. Additionally, autoregressive models to forecast future incidents were also built.


Other files presented in this submission are:

	5.	environments.txt
A file containing instructions to set the recommended environments to run each one of the above notebooks. 

	6.	data 
A folder containing the csv files used in this project.

	7.	Alan_Fleck_Capstone_Final_Report.pdf
The final report containing a summarized description of the background, objectives, data preprocessing, results and conclusions of this project.


