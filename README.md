# simple_scraper

Note: for findlinks.py
Replace "url" >> website we want to scrape in findlinks.py 

```
$ python findlinks.py
```
Limitation - 
- Only grabs the url from the base url - index.html (does not follow same domain links to extract the urls from those pages)




Note: for link_spider.py 
Replace "url" >> website we want to scrape in link_spider.py 
```
$ pip install scrapy

$ scrapy crawl crawltest
``` 
Limitations - 
- Does not output the links from other domains like google.com, facebook.com OR CDN domain
- Does not iterate and stores the links grabbed from the current page
