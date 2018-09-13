# News Scraper

*Scrape news articles from MSNBC, CNN, and Fox News for future reference*

[About](#about)<br>
[Demo](#demo)

## About

### Scraping

* Article titles and links are scraped from three news websites (MSNBC, CNN, and Fox News) using [Phantom](https://www.npmjs.com/package/phantom) and [Cheerio](https://www.npmjs.com/package/cheerio).
* The category for scraped articles is determined from its associated link. However, for MSNBC, the category is assumed to be 'politics'.
* The scraping operation takes several seconds to complete, primarily because CNN's website uses a lot of javascript and thus requires phantom to load the javascript files before the scraper can continue.

### Data

* This app uses a MongoDB for storing data. Scraped articles can be saved for future reference, and each saved article allows for comments. 
* A record of every scrape is also saved to the database and can be used to assess whether the three news sites have changed, such that the scraper needs to be updated.

### API Endpoints

|Method|  | Cool |
|------|---|---|
|GET   |
|GET   |
|POST  |
|GET   |
|DELETE|
|POST  |
|DELETE|
|GET   | 

## Demo

* coming soon


