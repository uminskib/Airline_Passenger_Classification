# Airline passenger classification - data science project

## Introduction

The repository contains a data science project based on a training database that comes from the [Kaggle](https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction)
The database, called Airline passenger satisfaction, contains responses to questions from a survey of 103904 passengers on one airline. Each passenger is described by 22 variables.
The main goal of the study is to find the best model to accurately predict passenger satisfaction based on the information collected. 
The structure of the project is as follows:
- First file: Preparation_data_EDA:
1. Introduction and development environment preparation
2. Preparation data
3. Exploratory Data analysis
- Second file: Feature_selection_generation:
1. Feature selection
2. Feature generation/engineering
- Third file: Modelling:
1. Logistic regression
2. K-Nearest Neighbors
3. Random Forest
4. Gradient Boosting
5. Summary

In the repository are:
* Folder data - contain data from Kaggle, all dataset created during the analysis and txt files with column names.
* Folder img - there are images created during the analysis: corrleation matrix and feature importance plot.
* Folder reports - contain html/pdf files created from main files with analysis.
* 1.Preparation_data_EDA.ipynb - first file contains introduction and data preparation.
* 2.Feature_selection_generation.ipynb - second file with feature engineering.
* 3.Modelling.ipynb - third file in which the best machine learning model is selected.
 
The whole project was realized in June 2021 for the purpose of passing classes and was prepared in Polish language. It was designed to test knowledge of machine learning techniques and the ability to perform data science analysis.

Note:
Some models take quite a long time to train, so a reports folder has been created that contains html files with all the analysis done. All cells are called there and you don't have to do it anymore to see the results.

## Technologies

The following tools were mainly used for the study:
* Python 3.8.0
* pandas 1.1.3
* numpy 1.19.1
* scikit-learn 0.24.2
* seaborn 0.11.1
* matplotlib 3.4.2

Rest of required packages in requirements.txt file

## Setup
To run the project: 
1. Download the entire repository and unzip it or clone repository by git.
2. Install the required packages included in the requirements.txt file:
     * Launch any command-line interface (e.g. Anaconda Prompt).
     * If you have one, set up a custom virtual environment for the program in which the project will run.
     * Set the destination path to the folder with the project: "cd 'your destination path to project'"
     * Type "pip install -r requirements.txt".
3. Start Jupyter Notebook or LupyterLab and select the first file Preparation_data_EDA.ipynb
4. Run all cells

Application developed and tested in Jupyter Notebook. 
