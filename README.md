# Mission_to_Mars
Create an app to scrape websites for information about the Mission to Mars, then create an HTML page to display the results.

## Overview
In her spare time, Robin works as a freelance astronomer. She spends a lot of time checking websites with news on space exploration, particularly about Mission to Mars, because one day she hopes to work for NASA. Instead of using her free time to manually collect the data and share it with others, Robin decides to build a script that will compile all the information she seeks into one handy central area.

## Summary 
To quickly scrape the additional data, a webpage application was developed. In order to create a Python script that can explore web pages and gather the necessary data, Robin had to become familiar with how web pages function. After gathering all the information, she had to put it in a No SQL database like MongoDB because data obtained from the internet can be in a variety of formats and is not necessarily organized into the tidy tables required by SQL. She combined everything into a web application using Flask and bootstrap for further polish.

## Challenge Overview
Although Robin's online application looks fine and works well, she wanted to give it additional gloss. She discovered the website's scraping friendliness while browsing viewing pictures of Mars' hemispheres.

She wanted to add all four hemisphere photos to the present online application. To accomplish this, we had to scrape headlines and full-resolution photographs of Mars' hemispheres using BeautifulSoup and Splinter, store the data in a Mongo database, display the data using a web application, and modify the web application's design to fit the images.
