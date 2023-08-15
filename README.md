# Bike Sharing Prediction Project

This repository contains the code and analysis for predicting the number of total rental bikes in a bike-sharing system. The goal of this project is to explore, preprocess, build a prediction model, and evaluate its accuracy based on the provided dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Preprocessing](#preprocessing)
- [Prediction Model](#prediction-model)
- [Evaluation](#evaluation)
- [Code](#usage)

## Introduction

Bike sharing systems have gained popularity as a new generation of bike rentals, offering an automated process from membership to bike rental and return. This project aims to predict the number of total bikes rented (count) based on various features recorded from bike-sharing systems.

## Dataset

The dataset used in this project contains a set of features recorded from bike-sharing systems. It includes information such as weather conditions, time of day, and other relevant factors that may influence bike rentals. The dataset is available [here](https://github.com/AriolaLeka/Bike-Rental-Prediction/blob/main/hour-Train.csv).

## Exploratory Data Analysis

In this section, we performed standard descriptive statistics, visualized variables using graphs, drew distributions and histograms, and explored correlations between different features. Some interesting observations and insights we discovered include:  casual and registered have the highest correlation ( 71% , 97% ), atemp and temp seem to carry the same information (99%), hr , temp and hum seem to be that will be the most important variables for the model. 

## Preprocessing

Before building the prediction model, we preprocessed the data to handle unknown values, normalize features, and prepare the dataset for training. This step ensures the data is in the right format and quality for model development.

## Prediction Model

We use 3 prediction models to estimate the number of total rental bikes based on the provided features. We use Random Forest Regression, Linear Regression and Multi-layer Perceptron.

## Evaluation

To evaluate the accuracy of our prediction model, we used MSE, MAE, R-squared evaluation metrics to assess the model’s performance and compare them amongst each other. The model's performance was compared against the actual values provided in the dataset.

## Code 

To use the code in this repository, follow these steps:

1. **Download the Project Files:**

Click on the green "Code" button and select "Download ZIP." Extract the downloaded ZIP file to a location on your computer.

2. **Open Google Colab:**

   Open your web browser and navigate to [Google Colab](https://colab.research.google.com/).

3. **Upload the Jupyter Notebook:**

   In Google Colab, click on the "File" menu, then choose "Upload Notebook." Upload the `Bike-Rental-prediction/Bike Sharing.ipynb` file from the extracted project folder.

4. **Run the Code:**

   Once the notebook is uploaded, you can run the code cells sequentially by clicking the "Play" button (▶️) next to each cell. This will execute the code and display the output, including visualizations and analysis.

5. **Follow the Instructions:**

   The notebook contains step-by-step instructions and explanations. Read the markdown cells and comments within the code cells to understand the project's flow and purpose.
