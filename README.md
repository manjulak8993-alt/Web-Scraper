# Web Scraper for News Headlines
A simple Python web scraper that fetches top news headlines from a website using requests and BeautifulSoup, and saves them into a text file.

# Objective
The objective of this project is to scrape top headlines from a news website and save them into a text file. This helps in automating the process of collecting the latest news in a structured format.

# Tools Used
Python programming language
Requests library for fetching web pages
BeautifulSoup library for parsing HTML content

# Working Principle
The script sends a request to the news website and retrieves its HTML source code. The BeautifulSoup library is then used to parse this HTML and extract all the headline elements, usually contained within heading tags like <h2>. These headlines are cleaned and stored in a text file.

# Deliverables
A Python script that scrapes headlines from a chosen news site.
A text file containing the extracted headlines in a numbered list.

# Note
The default website used in this project is Deccan Herald News.

