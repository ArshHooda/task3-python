# News Headline Scraper  
**Description**: Python script to scrape news headlines using BeautifulSoup and requests.  
**Requirements**: Python 3.x, BeautifulSoup4, requests  
**Installation**: `pip install beautifulsoup4 requests`  
**Usage**: `python scraper.py`  
**Configuration**: Modify in `scraper.py`:  
```python
target_url = "https://www.bbc.com/news"  
headline_tag = "h2"  
headline_attrs = {'data-testid':'card-headline', 'class':'sc-9d830f2a-3 fWzToZ'}  
