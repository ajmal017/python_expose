# python_expose

# I've created this repository for the purpose of showing some of my better work written in python

## GUIDE

- Crypto Analysis
  this folder contains my research from my spring semester of development and cryptocurrency research, and is better documented in the readme found in that folder. One *NOTE: the final_report/ directory contains the final typed up report that I used when presenting my ideas.*
  
- Renko Trading Strategy
  This folder contains a class and a test suite that I developed for a freelance client. It is an implementation of a renko trading strategy. The renko class may be used to make sense of historical data as well as process real-time ticker data. It may be used with preselected candlestick sizes, or use Average True Range calculations to dynamically determine renko candlestick size
- Sbir scraper
  This was a web scraper I developed using selenium for my friend at a company I was interviewing with at the time. The government comes out with small business and innovation contracts quarterly and this script scrapes the data from all of the topics and saves them in a csv file. Later on we started wondering if we could make it any faster at which point extends threading.Thread to try scraping different topics in parallel. I only achieved a 15% speedup, but it was a fun excercise. If I were to try and make the process scrape even faster I would attempt parellelizing on different processes instead of using multithreading. 
