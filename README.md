# Web-Scraping

import requests

from bs4 import BeautifulSoup

req = requests.gat("https://pypi.org/project/beautifulsoup4/")

soup = BeautifulSoup(req.content, "html.parser")

print(soup.prettify())
