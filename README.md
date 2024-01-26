# PGATour-Data-Project

## About

This repository contains my PGATour Data Analysis Project. After completing various courses in the IBM Data Science Professional Certificate offered by Coursera and IBM, I felt I had the knowledge to complete a small project about something I am quite passionate about: the world of golf. I wanted to find out what statistics made professional golfers so great so that I could hone in on these aspects to possibly improve my amateur game. 

## What I Did

First, in looking at the PGATour.com website, I found a comprehensive list of statistics pages dating back to the 2004 season. I knew that the tables on the web pages were built dynamically, so I was given the chance to learn about GraphQL, an API for data and statistics on web pages. I conducted an initial Exploratory Data Analysis (EDA) for the 2022-23 season using downloadable .csv files from the website. The EDA is available in the PGATourEDA_2022-2023.ipynb notebook, which can be downloaded and executed along with the 2022-2023 folder.

I quickly found this to be cumbersome, especially for analyses of multiple years. So, I created a web scraper to glean statistics information from the past 10 years. This procedure is outlined in the PGATourWebScraper.ipynb notebook. To use this scraper, simply download the notebook and create a .env file in the same directory with your API key. The scraper allows users to input specific stats they want to see in the data frame. I will soon update it to reflect the statistics used in my second EDA, focusing on data from 2013-2023.

## In the Future

Looking ahead, my plans include publishing an EDA that analyzes data spanning 2013 to 2023, aiming to uncover more long-term trends in the PGA Tour. Additionally, I am considering exploring the statistics page on the LIVGolf website—a recently controversial alternative to the PGA Tour that many tour players are moving to.

Feel free to explore, contribute, or provide feedback!

-- Vincent Etherton
