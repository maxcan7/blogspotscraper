# Blogspotscraper
A Python 3 script for scraping a Blogspot blog recursively. Saves each post as a new html file, which cleaned to remove most of the html code.

### Requirements
This script uses BeautifulSoup. Install with:

    pip3 install beautifulsoup4

### Usage
1. Change the `url` variable to the URL of the latest blog post in the blog. Save.
2. Run with `python3 blogspotscraper.py`
3. Abort scraping by pressing CTLC-C. Or the script will continue until there are no more posts left (or you get banned for over-using bandwidth)

### Limitations
This script does NOT work with the official Google blogs hosted on blogspot. It has only been tested from a Swedish IP-number, so it might not work if some URL redirection happens.

This is just a quick and dirty script that could work as a scaffold for writing more precise scraping features.

### Warning!
By repeatedly downloading web pages, you might get temporarily banned from the service. Use on your own risk.
