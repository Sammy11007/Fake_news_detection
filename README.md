# Fake_news_detection
The goal of this project is to use Selenium to scrape articles from a political news website, store them in a .csv file and apply machine learning algorithms to find the classifiers with highest accuracy.
Utilized Selenium to automatically harvest 5400 records from a news website and create a CSV file for storage.
Constructed a ML model to read the CSV file, cleaned the data frame using Pandas and applied MLPClassifier to train and test the data to obtain 70% accuracy.

The scrapping.ipynb file contains the code that is used to scrape the articles from "https://www.politifact.com/factchecks/list/?page=1&category=truth-o-meter".
This file also contains the code to hide all the google ads in that website which would prevent selenium from scraping data.

data.csv contains the Date, Platform, Text, Person and Truthfulness_Category of every article on that website.

the classification.ipynb file loads the data.csv, performs data cleaning and applys MLPClassifier algorithm to obtain 70% accuracy of the predicted values.
