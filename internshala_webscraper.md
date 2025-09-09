# Internshala Job Web Scraper

This project is a **Python web scraper** built with [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) and [Requests](https://docs.python-requests.org/) to extract **fresher Data Science job listings in Gurgaon** from [Internshala](https://internshala.com/).

## 📌 Features
- Scrapes **company names**, **job titles**, **stipends**, **skills required**, and **locations**.
- Organizes data into a **Pandas DataFrame** for easy analysis.
- Handles missing values gracefully using Python exception handling.
- Can be adapted to scrape **any website** with similar structured data.

## 🛠️ Technologies Used
- **Python 3**
- **BeautifulSoup4** for parsing HTML
- **Requests** for fetching web pages
- **Pandas** for data storage and manipulation

## 🚀 Installation
1. Clone this repository or download the notebook:
   ```bash
   git clone https://github.com/yourusername/internshala-webscraper.git
   cd internshala-webscraper
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
   **requirements.txt**:
   ```
   beautifulsoup4
   requests
   pandas
   lxml
   ```

## 📂 Usage
Run the Jupyter Notebook:
```bash
jupyter notebook Internshala_webscrape.ipynb
```

## 📊 Output
The scraper produces a structured DataFrame:

| Company Name | Job Title | Stipend | Skills | Location |
|--------------|-----------|---------|--------|----------|
| ABC Pvt Ltd  | Data Analyst | ₹25,000 | Python, SQL | Gurgaon |
| XYZ Ltd      | ML Engineer | ₹30,000 | ML, TensorFlow | Gurgaon |

You can save the results to CSV:
```python
df.to_csv("internshala_jobs.csv", index=False)
```

## ⚠️ Disclaimer
- This project is for **educational purposes only**.
- Internshala’s content is their intellectual property; please check their **robots.txt** and **terms of service** before large-scale scraping.

---
👨‍💻 Developed by: *Your Name*

