# 📚 Web Scraping, EDA & Visualization Project

An end-to-end data analytics project demonstrating public web scraping, exploratory data analysis (EDA), and publication-grade visualization dashboards.

---

## 📌 Project Overview
* **Task 1: Web Scraping:** Extracted catalog data (titles, prices, star ratings, stock availability) across multiple pages from [Books to Scrape](http://books.toscrape.com) using `requests` and `BeautifulSoup`.
* **Task 2: Exploratory Data Analysis:** Checked missing values, handled character encodings (UTF-8), evaluated distributions, and verified price-to-rating relationships using `pandas`.
* **Task 3: Data Visualization:** Built a 4-panel executive dashboard in `matplotlib` and `seaborn` applying core layout and visual design principles (CRAP).

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.10+
* **Libraries:** `requests`, `beautifulsoup4`, `pandas`, `matplotlib`, `seaborn`

---

## 📈 Executive Insights & Dashboard
![Executive Dashboard]([images/internship_visualization_portfolio](https://github.com/Hafiz-Rehman123/Web-Scraping-EDA-Visualization-Project/blob/main/executive_dashboard.png).png)

1. **Price Distribution:** Book prices are uniformly distributed across the catalog range (£10–£60).
2. **Rating Parity:** Stock volume is balanced evenly across all star rating tiers (1 to 5 stars).
3. **Strategic Insight:** Star ratings do not correlate with price point; 1-star books held the highest average price (£40.09).
