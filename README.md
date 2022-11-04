# web_scraping_onthisday.com
This is a web scraping python script that runs in concurrent mode to send multiple requests to extract information for all dates of the year on https://www.onthisday.com/ website.
I used aiohttp client module to extract html structure from website and i used BeautifulSoup to parse html.
Script works by creating a date object dor each day of the year and by translating that date into text to query the url to get all the data for that day.

