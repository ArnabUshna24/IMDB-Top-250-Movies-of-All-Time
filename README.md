# IMDB - Top 250 Movies of All Time

## About
This is a Capstone Project under the flagship cohort of MasterCourse, called MasterCourse - Dokkho Data Science Cohort 6. In this project, IMDB website was scraped to retrieve data on top 250 movies of all time and interesting findings were presented on Tableau.

## Goal
This project will build a web scraper for a dynamic website and create meaningful and interesting visualizations in Tableau dashboard.

## Objectives
* To scrape a dynamic website and retrieve the data.
* To find and handle missing data properly.
* To build interesting visualizations, trends, or patterns from the data by creating visualization in Tableau.

## Data Source
[IMDb Top 250 Movies](https://www.imdb.com/chart/top/?ref_=nv_mv_250)

## Dynamic Web Scraping
I used Selenium to build a web scraper to retrieve data on top 250 movies of all time from IMDB website. Since the columns do not have same number of entries, I decided to scrape data separately (making 3 separate scrapers) considering the uneven number of column entries.

## Data Processing, Transformation and Manipulation
After generating .csv files from VS Code, I manually adjusted the column entries in MS Excel as every column does not have same number of entries. Then, I handled the missing values in Google Colab using Python.

## Interesting Findings
* Among the 250 movies, the most number of movies (8) were released in 1995.
* The highest average rating for the released movie(s) in a calendar year (9.2) was in 1972.
* Most of the movies (101) are R-rated, having an average rating of approximately 8.33.
* The Shawshank Redemption, Star Wars: Episode V - The Empire Strikes Back, and The Dark Knight are the highest ranked movies in R, PG and PG-13 categories, respectively.

## [Dashboard Preview](https://public.tableau.com/app/profile/arnab.naha.ushna/viz/Top250IMDBMovies_17382266796240/Top250IMDBMovies)
![Tableau Visualization](https://github.com/ArnabUshna24/IMDB-Top-250-Movies-of-All-Time/blob/main/Dashboard.jpg)

## Build from Source
1. Clone repository
   ```python
   git clone https://github.com/ArnabUshna24/IMDB-Top-250-Movies-of-All-Time.git
2. Initialize virtual environment
   ```python
   virtualenv venv
3. Activate virtual environment
   ```python
   source ./venv/bin/activate
4. Run scraper.py, scraper_2.py, and scraper_3.py files to scrape the data and generate the .csv files.


For any queries, contact me: arnabnushna24@gmail.com
