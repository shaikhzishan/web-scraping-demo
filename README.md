# Web Scraping Demo

A simple demonstration comparing **BeautifulSoup** and **Selenium** for web scraping tasks in Python — including login‑based scraping examples.

---

##  Overview

This repository contains example Jupyter notebooks that showcase how to perform web scraping using two popular Python tools:

- **BeautifulSoup** — for parsing and extracting static HTML content  
- **Selenium** — for browser‑based automation (useful for dynamic pages or login workflows)

These examples are useful if you want to learn basic scraping techniques or see how the two approaches differ. :contentReference[oaicite:0]{index=0}

---

## 📁 Contents

| File | Description |
|------|-------------|
| `bs4_sel_demo.ipynb` | A demo combining BeautifulSoup and Selenium for scraping |
| `wikipedia_selenium_bs4.ipynb` | Example of scraping data from Wikipedia using Selenium + BeautifulSoup |

---


This demo illustrates:

- How to fetch a webpage and parse its HTML with BeautifulSoup
- How to automate a browser session using Selenium
- Basic navigation and scraping of dynamic content
- Differences between static scraping vs. automated browser scraping :contentReference[oaicite:1]{index=1}

---

## 🛠️ Prerequisites

To run the notebooks locally, you should have Python installed along with:

- `beautifulsoup4`
- `selenium`
- `pandas` (optional, for data handling)
- A webdriver (e.g., ChromeDriver or GeckoDriver)

You can install the required libraries with:

```bash
pip install beautifulsoup4 selenium pandas
