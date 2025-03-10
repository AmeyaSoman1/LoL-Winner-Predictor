# LoL-Winner-Predictor
This project is a machine learning-based winner predictor for League of Legends (LoL) matches. The predictor takes in-game statistics and outputs the probability of each team winning. The main objective is to provide insights into how certain features impact the likelihood of victory in a competitive match.

Credit must be given to the following Kaggle dataset from which I extracted the data: https://www.kaggle.com/datasets/datasnaek/league-of-legends

## Introduction
League of Legends (LoL) is a popular multiplayer online battle arena (MOBA) game where two teams of five players compete to destroy the opposing team's Nexus (a structure at the heart of their base). The outcome of a match can often be predicted by various in-game factors and this project leverages historical data and machine learning techniques to predict the winner of a LoL match, using the result of those factors.

## Model Training
The model is trained using a logistic regression algorithm on a dataset of historical League of Legends matches. The key features used for training include:

Champion Selection: Champions (the characters) chosen by each team.  
"First" Objectives: Know the team that took the first kill, such as the tower, dragon, etc.

#### Please go ahead and read the Jupyter Notebook for the thought process throughout this investigation 🔎

