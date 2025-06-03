# Google Maps Scraper
![Python Version](https://img.shields.io/badge/python-3.13%2B-blue.svg)
![License](https://img.shields.io/github/license/decodo/Google-News-scraper)

<p align="center">
<a href="https://dashboard.decodo.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://github.com/user-attachments/assets/60bb48bd-8dcc-48b2-82c9-a218e1e4449c"></a>
</p>


[![](https://dcbadge.vercel.app/api/server/Ja8dqKgvbZ)](https://discord.gg/Ja8dqKgvbZ)

## What is a Google Maps scraper?
Google Maps Scraper is a Python script that lets you scrape Google Maps and extract business details like names, ratings, reviews, and service options. It’s built for developers and data teams who need scalable local data collection with proxy rotation support to bypass rate limits and avoid blocks.

## Features
- **Rotating proxy support**. Bypass IP bans and rate limits with residential proxies.

- **Business data extraction**. Extract names, ratings, reviews, and service options.

- **Location targeting**. Scrape Google Maps results for any city or region.

- **Dynamic content handling**. Use Selenium to load JavaScript-rendered pages.

- **HTML parsing**. Clean and structure scraped data with [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/).

- **CSV export**. Save extracted business data to a local CSV file.

## Installation
1. **Clone the repository**. Run the following command in your terminal to install and navigate to the project folder:
```
git clone https://github.com/Decodo/google-maps-scraper.git
cd google-maps-scraper
```
2. **Install dependencies**. Make sure you have [Python 3.8+](https://www.python.org/downloads/) installed, then run:
```
pip install selenium selenium-wire webdriver-manager beautifulsoup4
```

## Usage examples
1. **Run the scraper with proxy rotation**. This script is ready to run out of the box. Just plug in your [proxy credentials](https://dashboard.decodo.com/) and update file paths:
```
python google-maps-scraper.py
```
By default, it will:

- Visit Google Maps with the query "falafel in London"
- Accept cookies
- Scroll to load more results
- Parse the page
- Save business data to a local CSV file
2. **Customize the search query**. Run your own query by updating this line in the script:
```
url = "https://www.google.com/maps/search/falafel+in+london/"
```

## Sample output
![image](https://github.com/user-attachments/assets/a4214763-34f8-4008-83e3-ec18a8db824c)

## Proxies
This script required proxies to run and overcome limitations that appear when making frequent requests. You can get reliable residential proxies from Decodo and access 115M+ residential IPs with fast response times and high success rates.

[Start your free 3-day trial](https://dashboard.decodo.com/register?page=residential-proxies/pricing)

## Read more
A detailed guide on how the script works can be found on [our website](https://decodo.com/blog/google-maps-scraping).

## Related repositories
[Google news scraper](https://github.com/Decodo/Google-News-scraper)

[Google images scraper](https://github.com/Decodo/google-images-scraper)

[Selenium integration](https://github.com/Decodo/Selenium)
