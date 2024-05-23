# E-commerce Analytics and Forecasting Project

## Overview
This project was developed as part of an exercise to optimize operations for the South American branch of YASA-1, a large e-commerce platform. The goal is to implement advanced data analytics and demand forecasting solutions to improve decision-making processes. The project is divided into three main tasks:

### Task 1: Demand Forecasting
A demand forecasting system was developed to predict sales for a short-term period (14 days) starting 7 days from the last date in the data. The system includes two approaches:

<b>Machine Learning-based Forecasting:</b> Utilizes advanced regression techniques (two random tree models) to predict demand. <br>
<b>Classical Time Series Forecasting:</b> Employs traditional method (ARIMA) to forecast future sales. <br> <br>
The solutions are implemented in a notebook, with detailed comments on the choice and appropriateness of each method.

### Task 2: Seller and Product Analysis
An analytical report was generated based on provided data about sellers and products. The report includes:

<li>Sellers with the highest and lowest turnover.</li>
<li>Sales leaders and laggards in each category.</li>
<li>Turnover analytics by product category.</li>
<li>Analysis of the relationship between product weight, turnover, and price.</li>
<li>Segmentation of sellers and products with business insights.</li>
<br>
The results are presented through visualizations in a Jupyter Notebook, along with the underlying code.

### Task 3: Product Review Analysis
I've implemented a functionality to analyze product reviews, focusing on:

<li>Classifying comments as positive, negative, or neutral using sentiment analysis.</li>
<li>Correlating text comments with numerical ratings (1-5).</li>
<li>Identifying products with the best and worst reviews.</li>
<li>Highlighting sellers with predominantly negative feedback.</li>
<li>Extracting mentions of prices from comments for competitor analysis.</li> <br>
The results are visualized in a Jupyter Notebook. Additionally, I've provided code to classify the sentiment of individual comments.

## Installation

### Requirements
<li>Python 3.8+</li>
<li>Pandas</li>
<li>NumPy</li>
<li>scikit-learn</li>
<li>pmdarima</li>
<li>matplotlib</li>
<li>seaborn</li>

## Conclusion
This project demonstrates the application of data analytics, demand forecasting, and sentiment analysis to improve operational efficiency and strategic decision-making in an e-commerce context.
