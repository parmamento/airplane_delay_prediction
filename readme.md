# Airplane Flight Delay

## Overview
This repository contains a Python code that imports the dataset from the Office of Airline Information, Bureau of Transportation Statistics (BTS). The dataset contains date, time, origin, destination, airline, distance, and delay status of flights for flights between 2014 and 2018. 

The data are in 60 compressed files, where each file contains a CSV for the flight details in a month for the five years (from 2014 - 2018). The data can be
downloaded from this link: https://ucstaff-my.sharepoint.com/personal/ibrahim_radwan_canberra_edu_au/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fibrahim%5Fradwan%5Fcanberra%5Fedu%5Fau%2FDocuments%2Fteaching%5Fjunction%2F2021%2Fs2%2Fdsts%2Ffinal%5Fproject%2Fdata%5Fcompressed&ga=1

The ipynb files contains the Problem Formulation, Data Processing and Visualisation, Model Training and Evaluation, Deployment, Feature Engineering, and Visualisation using Tableau.


## How to Run

Follow these steps to run the regression and classification models:

1. **Clone the repository**:
   Use the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/parmamento/airplane_delay_prediction.git

2. **Navigate the project folder**:
   cd airplane_delay_prediction

3. **Install the required dependecies**:
   os
   pandas
   numpy
   matplotlib
   seaborn
   pathlib2
   warnings
   scikit-learn
   zipfile
   time
   subprocess
   
   
   **run command to install dependencies**
   pip install os pandas numpy matplotlib seaborn pathlib2 warnings scikit-learn zipfile time subprocess

4. **Run Jupyter Notebooks**:
   jupyter notebook 3246782_Armamento_Final_onpremises.ipynb


## Expected Output

When you run the script, you can expect the following:

Data Processing: Successful importation and extraction of CSV files from ZIP files, followed by comprehensive data loading, visualization, and exploratory analysis.

Model Development and Evaluation: Implementation and evaluation of baseline classification models, generating key performance metrics such as accuracy, precision, recall, and F1-score. Additionally, visualization of the confusion matrix and ROC curve will be provided.

## Author

Pauline Armamento

## Dependencies
To run this project, install the following Python libraries:
- `os`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `pathlib2`
- `warnings`
- `scikit-learn`
- `zipfile`
- `time`
- `subprocess`

Use the following command to install the required libraries:
```bash
pip install os pandas numpy matplotlib seaborn pathlib2 warnings scikit-learn zipfile time subprocess





