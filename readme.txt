# Sentiment Analysis Case Study

This repository contains the code and documentation for the under-resourced Roman Urdu Sentiment Analysis Case Study. 
The goal of this project is to automatically identify the sentiment (particularly Negative) expressed in the text data. 
The sentiment classes are Positive, Negative, and Neutral.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Setup](#setup)
- [Usage Notes](#usage)
- [Results](#results)
- [Contact](#contact)


## Project Overview

A large multinational corporation seeks to identify sentiment expressed by their customers on social media and other sources. The project involves training a sentiment classifier to categorize text data into one of three categories: Positive, Negative, or Neutral. The primary focus is on accurately detecting negative sentiment.


## Data

The dataset used for this project can be accessed through the following link:
[Download Data](http://archive.ics.uci.edu/ml/datasets/Roman+Urdu+Data+Set)


## Setup

To run this project, you will need Python and the following libraries:


- numpy
- pandas
- matplotlib
- scipy.sparse
- scikit-learn
- lightgbm
- openai [OpenAI GPT-3 API](https://beta.openai.com/account/api-keys) (for text classification)


To install the required libraries, you can use pip:
pip install numpy pandas matplotlib scipy scikit-learn lightgbm openai


## Usage Notes

1. Download the dataset from the provided link and place it in the project directory.
	git clone https://github.com/JosephGirsch/Urdu_sentiment_repo.git

2. Open and run the Jupyter Notebook or Python script to perform sentiment analysis on the dataset.

Note that the dominant language identification portion of this script requires a paid account 
or paid credits and may take 90 minutes to run.


## Results

See "Roman Urdu Sentiment Identification.ppt" for full results and steps forward.  


## Contact

Joseph Girsch
LinkedIn: https://www.linkedin.com/in/joseph-girsch-6b664876/
Portfolio: https://josephgirsch.github.io/portfolio/