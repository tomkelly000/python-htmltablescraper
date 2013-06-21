python-htmltablescraper
=======================

A python script with methods for scraping tables from web pages

htmltablescraper contains some helpful methods for retrieving table data on 
webpages, using BeautifulSoup.  Most importantly 
url2csvs(url [, dname[, bytitle]]) puts all the tables on a given web page
in csv format into a folder specified by dname or by the title of the web
page if bytitle=True
