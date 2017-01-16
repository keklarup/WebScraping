# WebScraping
Tutorial and worked example for webscraping in python using urlopen from urllib.request, beautifulsoup, and pandas

# 1 Paragraph on Web Scraping
If there's information on a webpage, you can gather it. If you only want information from a few pages, you can just copy/paste into an excel file and be on your way. 

<img src="./WS_images/CopyPaste1.png" height="350px" />     <img src="./WS_images/CopyPaste2.png" height="350px"  />

But if there are many pages, that's just not practicle. Either you need a lot of people to help you, or you need to have your computer do it for you. This webscraper will be written in a Jupyter Python notebook, but in essense it is doing exactly what a human would do: open a webpage, copy the desired information, save it in a table, and repeat for many, many pages.

## Keys to Web Scraping:
The keys to web scraping are patterns. The webpages you want the program to visit can't be random, there needs to be some pattern the program can follow to go from one to the next. The desired data on each webpage must be in some recognizable pattern, so the web scraper can reliably collect it. Finding these patterns is the tricky, time consuming process that is at the very beginning. But after they're discovered, writing the code of the web scraper is easy.

# Outline


## Python Packages

1) urlopen from urllib.request : to download page contents from a given valid url

2) BeautifulSoup from bs4 : to navigate the HTML of the downloaded page

3) pandas : to store our scraped data

For those knew to python, packages and modules are ready made bits of code to make your project go faster. Sure, you could write a script to interact the HTML of a webpage, but someone has already done that. Don't reinvent the wheel. Give thanks and move on.
