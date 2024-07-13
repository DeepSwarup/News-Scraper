# News Scraper

## Overview

This Python script automates the process of scraping news articles from an RSS feed using the `newspaper3k` and `feedparser` libraries. It provides a convenient way to gather and parse up-to-date news content from various sources programmatically.

The script fetches each article linked in the RSS feed, downloads its content, and extracts key information such as the article title, author(s), publish date, and main text content. This structured data can be used for various purposes including news aggregation, sentiment analysis, content summarization, and more.

By using this script, users can streamline the retrieval and processing of news articles without manual intervention, making it ideal for applications needing timely and reliable news data.


## Requirements

- Python 3.8+
- Dependencies:
  - `newspaper3k`
  - `feedparser`
  - `lxml` with `html_clean` extras or `lxml_html_clean`

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>

   
