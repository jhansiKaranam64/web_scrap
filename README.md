# WEB SCRAPPING

## Packages

## 1)News Catcher

***News Catcher is a simple Python web scraping library that can be used for scraping news articles from almost any news website. It also enables you to gather details related to a news website.***

***Methods***


While extracting just a few of the data points, you can get all of them for further processing:

- Title
- Link
- Authors
- Tags
- Date
- Summary
- Content
- Link for Comments
- Post_id

***References***

1)https://newscatcherapi.com/blog/python-web-scraping-libraries-to-mine-news-data

## 2)PyGoogle News

***PyGoogleNews, created by the NewsCatcher Team, acts like a Python wrapper for Google News or an unofficial Google News API. It is based on one simple trick: it exploits a lightweight Google News RSS feed.***

***Fetches Following Data***

- Top stories
- Topic-related news feeds
- Geolocation specific news feed
- An extensive query-based search feed

***Refernces***

1)https://newscatcherapi.com/blog/python-web-scraping-libraries-to-mine-news-data

## 3)Lxml

***requests library cannot parse the HTML retrieved from a web page. Therefore, we require lxml, a high performance, blazingly fast, production-quality HTML, and XML parsing Python library.***
***It combines the speed and power of Element trees with the simplicity of Python. It works well when we’re aiming to scrape large datasets. The combination of requests and lxml is very common in web scraping. It also allows you to extract data from HTML using XPath and CSS selectors.***

***Procedure for Extracting text***

- We will use requests.get to retrieve the web page with our data.
- We use html.fromstring to parse the content using the lxml parser.
- We create the correct XPath query and use the lxml xpath function to get the required element.

***Refernces***

1)https://www.codespeedy.com/web-scraping-using-lxml-in-python/

2)https://www.analyticsvidhya.com/blog/2020/04/5-popular-python-libraries-web-scraping/

## 4)Feed Parser

***The FeedParser Python library runs on Python3.6 or later and can be used to parse syndicated feeds. In short, it can parse RSS or Atom feeds and provide you with the information in the form of easy-to-understand data points. It acts as a news scraper and we can use it to mine news data from RSS feeds of different news websites.***

***Extracts:***
- Title
- Content
- Links

***References***


1)http://www.slideshare.net/LindseySmith1/feedparser

2)http://code.google.com/p/feedparser/

## 5)NewsPaper3k

***"Newspaper is an amazing python library for extracting & curating articles.***

***Extracts***
- Title
- Content
- Links
- Date
- etc

***Refernces***

1)https://github.com/codelucas/newspaper/

2)https://anaconda.org/conda-forge/newspaper3k

