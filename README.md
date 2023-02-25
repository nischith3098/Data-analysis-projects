# Data-analysis-projects
This repo contains the projects related to data analysis

**1. Time-Series-Analysis**

The file demonstrates how to perform time series analysis on stock price data using Python and the yfinance and Plotly libraries.

The first part of the code collects the latest stock price data for Apple using the yfinance API. The data is downloaded and stored in a Pandas dataframe with the date index.

The second part of the code demonstrates how to visualize the trends in the stock prices using different types of plots. The first plot is a line plot created using Plotly Express. It shows the trends in the close prices of Apple over time. The cursor on the line plot displays the close price on the exact date of the data point under it.

The second plot is a candlestick chart created using Plotly Graph Objects. It shows the trends in the open, high, low, and close prices of Apple over time. The red lines indicate a fall in prices, and the green lines indicate an increase in prices. The cursor on the candlestick chart displays all the prices (open, high, low, and close) of Apple on the date where the cursor is placed.

The third plot is a bar plot created using Plotly Express. It shows the trends in the close prices of Apple over time. It is useful to visualize price increase and decrease in the long term scenario.

The fourth plot is a line plot created using Plotly Express. It shows the trends in the close prices of Apple between two specific dates.

The final part of the code demonstrates how to create an interactive candlestick chart using Plotly Graph Objects. The chart allows the user to select a specific time interval by using a slider and buttons to control the time interval. The rangeslider_visible parameter is set to True to enable the slider, and the rangeselector parameter is set to display the buttons for selecting the time interval. The available time intervals are specified using the list of dictionary objects, where each object contains the count of the time interval, the label to display on the button, and the step to move back or forward in time.

**2. Covid-19 Impact analysis**

This project is a Covid-19 impact analysis case study that explores the adverse effects of the pandemic on various countries. The project uses a dataset that contains information on human development index, daily Covid-19 cases and deaths, stringency index, population, and GDP per capita of different countries.

The project starts with data cleaning by removing unwanted columns, identifying missing values, and changing the datatype of the column. After data cleaning, the project aggregates the data from both datasets and creates a new dataset by combining the necessary columns. The aggregated data contains information on total cases, total deaths, stringency index, population, and GDP during and before Covid-19.

The project then visualizes the data to analyze the spread of Covid-19 in different countries. It uses bar charts to display the countries with the highest Covid-19 cases and deaths, and line charts to show the daily new cases and daily new deaths in the top countries. It also explores the correlation between the stringency index and the total cases in different countries.

Overall, this project provides a comprehensive analysis of the impact of Covid-19 on different countries and demonstrates the importance of data analysis in understanding global events.

**3. Supermarket Sales**
This case study mainly focuses on Exploratory Data Analysis.
This case study presents a real-world scenario where data-driven insights influence important decisions. This case study explores a supermarket chain's transaction-level sales data and derive useful business insights.
The flow of the case study involves Data wrangling, Univariate analysis, Bivariate/Multivariate analysis and Final Insights.
