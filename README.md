<div align="right">
בס"ד
</div>

# IMDB Movie Analysis: Aa to AL
**Data Mining & Enrichment Project**

## Project Overview
This project focuses on the extraction, cleaning, and enrichment of a movie dataset starting with titles from **Aa** to **AL**. It integrates foundational data from **IMDB** with real-time web scraping from **Wikipedia** and metadata retrieval via the **OMDB API** to create a unified database for analysis.

## Authors
* **Kfir Ziso** (ID: 322883091)
* **Reuven Waldman** (ID: 318344231)
* **GitHub Repository:** [imdb-movie-analysis](https://github.com/KfirZiso/imdb-movie-analysis)

---

## Key Features
* **Data Integration:** Merges IMDB's `title.basics`, `title.principals`, and `title.ratings` datasets.
* **Web Scraping:** A custom engine built with `BeautifulSoup` to extract:
    * Country & Language
    * Financial data (Budget & Box Office)
    * Wikipedia-sourced plot summaries
* **API Enrichment:** Automated fallback to **OMDB API** for missing plot summaries.
* **Financial Normalization:** Regex-based cleaning that converts various currency strings into numeric values (represented in Millions).
* **Quality Control:** Automated missing value analysis and random sampling for manual verification.

---

## Tech Stack
* **Language:** Python 3.11
* **Data Handling:** `pandas`, `numpy`
* **Scraping & Requests:** `BeautifulSoup4`, `requests`
* **Text Processing:** `re` (Regular Expressions)

---

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/KfirZiso/imdb-movie-analysis.git](https://github.com/KfirZiso/imdb-movie-analysis.git)