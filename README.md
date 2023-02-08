# When-was-the-Golden-Age-of-Video-Games

This aim of this project is to analyze a Video games dataset and discover the Golden Age of the Video games. The Golden Age is the year when games were in high demand and User ratings and Critic scores for the games where also very high which makes them very pleasing to the Video game players

The Analysis was done using SQL. I got to perform Exploratory Data Analysis with SQL and this project really tested my knowledge on Joins in SQL as well as my understanding of Subqueries. 

# Analysis & Results

Included in the Jupyter notebook is the Schema for the datasets used to solve this problem. I first studied the datasets then I discovered that the timeframe for the data covers from the year 1970 to 2020.

I approached this task by filtering out for years that had more than 4 distinct games sold per year. Then I grouped by the years to find out the top 10 years with a very high Average critic score per game. I also queried the data to find out the top 10 years with the highest Average User score. 
I used my knowledge of Subqueries to find the years similar to both queries with high critic and user scores. I was then left with three years which are 2008, 1998 and 2002.

Finally, to pick the golden year I checked the total Quantity of Games sold in millions in the three years and sorted them in descending order. 

After following the afrementioned steps, the Golden age was discovered to be 2008
