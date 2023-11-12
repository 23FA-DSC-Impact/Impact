# Project Impact
## Table of contents
[Objective](#project-objectives)

[Dataset](#dataset)

[Approach](#apporach)

[Authors](#authors)

[ReadMe History](#history-of-readMe-file)

## Project Objectives
### Mission statement
Given that the stock market is a huge indicator of economic circumstances and situations, and has the power to drastically change an individual’s financial assets, our dataset and models will serve to help understand which types of data analysis/machine learning processes best predict stock market trends. Assuming accuracy, the model will help forecast economic events and allow companies to protect themselves in case of an oncoming financial risk. Furthermore, by using multiple types of models, we will understand which machine learning techniques are best suited for economic prediction, and dive deep into the framework of each model to analyze each model’s methodology.

### In a nutshell...
We aims to analyze performance of different forecast AI models using S&P 500 index over a decade.

## Dataset
Our data can be found at [Nasdaq.com](https://www.nasdaq.com/market-activity/index/spx/historical?page=1&rows_per_page=10&timeline=y10).
This is a publicly available dataset that is updated on a daily basis. Since this dataset is not yet complete, we can divide it up for training and test accuracy on more recent dates.

We have also utilized an additional economic indicies to reflect US and global economic situation, as these indicies are likely presumed to impact stock market directly.
* [Daily Effective Federal Funds Rate from Federal Reserve Economic Data](https://fred.stlouisfed.org/series/EFFR)
* [Quarterly US GDP from Federal Reserve Economic Data](https://fred.stlouisfed.org/series/GDP)
* [Daily MSCI ACWI ETF from Yahoo! finance](https://finance.yahoo.com/quote/ACWI/history?period1=1383868800&period2=1699401600&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true&guccounter=1)

## Approach
We will implement multiple Machine Learning and Deep Learning models to predict/forecast a S&P 500 index at arbitrary point of future.

Then, we will analyze the models statistically and numerically by their performance(accuracy) depending on hyperparameters, resulting in the best prediction model.

## Authors
Hello! We are team impact from 23FA Illinois Data Science Club at University of Illinois.
* Aaliyah Ali
* Khushi Gandhi
* Nicole Gromski
* Donghyun Lee
* Sara Wheeler
* Sihun Wang

## History of ReadMe file
* Initially generated on Oct. 23rd, 2023.
* Dataset and their sources are modified on Nov. 11th, 2023.
