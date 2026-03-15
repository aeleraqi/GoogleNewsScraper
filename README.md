# Google News Scraper 📰

[![Language](https://img.shields.io/badge/Language-Python%20%7C%20Jupyter-blue)](https://github.com/aeleraqi/GoogleNewsScraper)
[![Stars](https://img.shields.io/github/stars/aeleraqi/GoogleNewsScraper?style=social)](https://github.com/aeleraqi/GoogleNewsScraper/stargazers)

A Python notebook for extracting news articles from **Google News** — built for journalists, researchers, and data scientists.

## 📖 About

**GoogleNewsScraper** automates the retrieval of news articles from Google News based on custom queries, date ranges, and topics. It outputs structured data ready for analysis, NLP processing, or journalism workflows.

## ✨ Features

- Search Google News by keyword, topic, or category
- Filter results by date range and language
- Extract headlines, URLs, source names, and publication dates
- Export to CSV/JSON for downstream analysis
- Configurable delays to respect rate limits

## 🚀 Getting Started

```bash
git clone https://github.com/aeleraqi/GoogleNewsScraper.git
cd GoogleNewsScraper
pip install -r requirements.txt
jupyter notebook GoogleNewsScraper.ipynb
```

## 💡 Example

```python
query = "artificial intelligence"
articles = scrape_google_news(query, max_results=50, language="en")
# Returns DataFrame with title, url, source, date
```

## 🧰 Requirements

- Python 3.8+
- requests, BeautifulSoup4, pandas

---
**Author:** [Amr Eleraqi](https://github.com/aeleraqi) — Data Analyst | NLP Specialist | Machine Learning Expert | Educator  
**Affiliation:** Toronto Metropolitan University, Ontario, Canada  
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0935--0026-brightgreen)](https://orcid.org/0000-0003-0935-0026) [![GitHub](https://img.shields.io/github/followers/aeleraqi?label=Follow&style=social)](https://github.com/aeleraqi)
