# Web-Scrapper-Selenium
The Repo aims to scrape the data from the from the plants data from [source](https://plants.usda.gov/adv_search.html).

Two main pages are scraped [1](https://plants.usda.gov/adv_search.html) and [2](https://plants.usda.gov/about_adv_search.html)

Scrapping of first is automated using selenium for filling checkboxes and redirecting to the next page after submit to go to the data source.
Only some of the important blocks(10) were selected to get scraped.

Selenium was prefered over BeautifulSoup as we need to interact with a web-page: submit forms, click buttons, scroll etc.

# Requirements

`Selenium` for automated scrapping

`Pandas` to save data into DataFrame

`ChromeDriver` webdriver needed to use selenium



