# DSND-Capstone-Starbucks

## Table of Contents
1)    [Installation](#installation)
2)    [Project Motivation](#Project-Motivation)
3)    [Description](#Description)
4)    [File Descriptions](#File-Descriptions)
5)    [Results](#Results)
6)    [Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)

## Installation
Some packaged are needed to install this project,
 *sklearn*
 *numpy*
 *pandas.*
## Project Motivation
This is a capstone project to graduate from Data Science nano degree from Udacity, the project may help starbucks to know there customer base and to get some business insight from it.

## Description
This project is part of my data science nano degree program  by Udacity in collaboration with
figure eight. The dataset contains labeled data and tweets, messages from real-life disasters.
the aim of this project is to build a tool that categorize messages using NLP (Natural Language Processing)

The project is divided in three different sections:
1. Data Processing, ETL pipeline to extract data from sources and to clean it finally save it in sqlite database
2. Machine Learning Pipeline to train model to be able to classify messages in categories
3. Web App to show model results also to predict new messages in real-time


### Dependencies
1. Python libraries needed
   - Python version used 3.7
   - Machine Learning libraries Scikit-learn, Numpy, Pandas, SciPy
   - SQLAlchemy
   - Flask, Plotly

### Installing:
Clone this GIT repository:

`
    https://github.com/amrhwanis22/DisasterResponse.git
`

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
        - If a database is previously created then you should delete it first.

    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`
2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://localhost:3001/


### License:
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



### Motivation:

1. This project was made to help people in disasters situation to send there messages and easily to be classified by the meant organization.

### Acknowledgement:

[Udacity](https://www.udacity.com/) For great course materials

[Figure Eight](https://www.figure-eight.com/) For the effort made to collect the dataset
