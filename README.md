# Youtube-GFG-Scraper

This project involves scraping video metadata from YouTube using Python libraries like Selenium and BeautifulSoup. The goal is to extract details such as video titles, view counts, upload dates, video/thumbnail links, likes, and descriptions. The workflow includes:

Using Selenium to automate browser navigation for dynamic page content.

Parsing HTML with BeautifulSoup to extract structured data.

Storing results in a CSV file and analyzing them with pandas.

# Key Features:

Automated scraping of multiple YouTube video pages.

Error handling for missing data fields.

Integration with pandas for data manipulation and analysis.

# Challenges Faced:

WebDriver instability (e.g., WebDriverException due to browser crashes).

Dynamic page elements requiring explicit waits and retries.

# Tools Used:
  Python, Selenium, BeautifulSoup, pandas, Chromedriver.
# Outcome: 
  A dataset of video metadata for further analysis or insights into YouTube content trends.
