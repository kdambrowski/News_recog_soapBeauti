# Fake News Detection from URL

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)

## General Information
This project is divided into two modules: `Fake_news_detection_from_url_preprocessing` and `Fake_news_detection_from_url_modeling`.

### Fake_news_detection_from_url_preprocessing
This module contains the following steps:
1. Exploratory Data Analysis (EDA) for FakeNewsNet.
2. Checking URL connection to extract articles.
3. Creating a CSV file from 'active' URL addresses.
4. Text preprocessing.
5. Extracting files to the second module for modeling.

### Fake_news_detection_from_url_modeling
This module includes the following steps:
1. Modeling.
2. Tuning results.
3. Visualizations.

The goal of this project is to prepare a deep learning model to predict whether an article is fake or real news.

Suggestions:
1. The code in this project is time-consuming due to URL check code. To save time, it is recommended to use the prepared files available [here](https://drive.google.com/drive/folders/12F3tfmnvzquZBHipzskBXitFookz5AnO?usp=share_link).

## Technologies Used
- matplotlib - version 3.4.3: A plotting library for creating visualizations and graphs.
- numpy - version 1.21.0: A library for numerical computations and mathematical operations.
- seaborn - version 0.11.1: A data visualization library built on top of matplotlib for creating attractive statistical graphics.
- pandas - version 1.3.0: A powerful library for data manipulation and analysis.
- tqdm - version 4.61.2: A library for creating progress bars to monitor the progress of loops and processes.
- csv: A built-in module in Python for reading and writing CSV files.
- spacy - version 3.1.1: A library for natural language processing, including text preprocessing and entity recognition.
- sklearn - version 0.24.2: A comprehensive machine learning library with various algorithms and evaluation metrics.
- BeautifulSoup - version 4.9.3: A library for web scraping and parsing HTML and XML documents.
- contractions - version 0.0.52: A library for expanding contractions in text, such as converting "don't" to "do not".
- os: A built-in module in Python for interacting with the operating system, used for file and directory operations.
- imblearn - version 0.8.0: A library for dealing with imbalanced datasets, including oversampling and undersampling techniques.
- requests - version 2.26.0: A library for making HTTP requests to retrieve web content.
- urllib - version 3.9.1: A library for handling URLs, used for downloading files from the web.
- scipy - version 1.7.0: A library for scientific and technical computing, including statistical functions.
- concurrent.futures: A built-in module in Python for asynchronous execution of tasks.
- neattext - version 0.1.2: A library for text cleaning and preprocessing tasks, such as removing stopwords and normalizing text.

These technologies and libraries are used in the project for tasks such as data visualization, data manipulation, text preprocessing, machine learning modeling, web scraping, statistical analysis, and more.

## Features
List of ready features:
- EDA for FakeNewsNet
- URL connection check and article extraction
- CSV file creation from 'active' URL addresses

- Text preprocessing
- Modeling
- Tuning results
- Visualizations

## Setup
To run this project, make sure you have the following requirements/dependencies installed. 

To set up your local environment and get started with the project, follow these steps:
1. Clone this repository.
2. Install the required dependencies.
3. Proceed with the specific setup instructions mentioned in each module.

## Usage
1. Download the trained model 'NLP_Net.pkl'.
2. Load the model to your environment by code "joblib.load('log_reg_model.pkl')".
3. Predict result.
    
## Project Status
This project is completed.
