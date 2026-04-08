# 🕸️ Web Scraping

This repository contains automated web scraping scripts and data extraction pipelines. I built this toolkit to efficiently gather, parse, and structure raw data from websites, which is the critical first step for building custom datasets for machine learning and data analysis.

### **What I Built **
* **Automated Data Collectors:** Python scripts that automatically visit web pages, read the HTML, and extract the exact information I need (like text, links, or tables).
* **Multiple Frameworks:** The project isn't just one script; it includes different approaches. I used **BeautifulSoup** for quick HTML parsing and **Scrapy** for handling larger, more complex data extraction tasks.
* **Structured Export:** The tools take messy web data and clean it up, organizing it into structured formats (like CSVs or DataFrames) so it is immediately ready for data science analysis.

---

## 🛠️ Technical Stack

| Category | Technology |
| :--- | :--- |
| **Language** | **Python** |
| **HTML Parsing** | **BeautifulSoup (bs4)** |
| **Advanced Scraping** | **Scrapy** |
| **Environment** | **Jupyter Notebooks** for interactive testing and data visualization |

---

## 📂 Repository Structure

```text
Python-Web-Scraping-Toolkit/
├── Data Scraper.ipynb                 # Interactive notebook for testing extraction logic and data cleaning
├── Web_Scrapping_BeautifulSoup/       # Scripts dedicated to parsing static HTML pages using bs4
├── Scrapy/                            # Spiders and pipelines built for large-scale web crawling
└── Web_Scraping_Scripts/              # General utility scripts for data gathering tasks
```

---

## 🚀 Key Technical Highlights

* **Scalability:** By including both BeautifulSoup and Scrapy, this repository demonstrates an understanding of when to use a lightweight parser versus a heavy-duty crawling framework.
* **Data Preparation:** The interactive Jupyter Notebook allows for immediate inspection and cleaning of the scraped data, ensuring the output is high-quality and ready for downstream NLP or ML tasks.

---
