# Prediction-on-NBA-MVP


This project uses Python to scrape data from website www.basketball-reference.com to feed machine learning model for the purpose of predicting the MVP (Most Valuable Player) of the NBA (National Basketball Association) by determining the more significant factors when it comes to MVP voting, based on three categories:

   - MVP votings from 1991 to 2022;
   - Team records each year (Division standings);
   - Player's per-game stats. 
    
The whole process is separated into three parts.

1. Preparation: Download and parse data, then convert Pandas DataFrames to readable CSV files ready for cleaning, further evaluation and prediction using Python, Selenium, Beautiful Soup, Pandas and Requests library. 

2. Data Cleaning: Clear NaN values, merge datasets and duplicate rows, extract helpful stats using the Pandas library. In addition, this part of the project includes data exploration/visualization with Matplotlib.

3. Machine Learning Model: In process


This README file is an overview, specific comments can be found in the .ipynb files under this repo including explanations of NBA terminologies and abbreviations, explanation of machine learning algorithms and error metrics.


Reference:
https://github.com/dataquestio/project-walkthroughs/tree/master/mvp
