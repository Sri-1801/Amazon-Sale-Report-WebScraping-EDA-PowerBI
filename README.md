🛒 Amazon Sale Report (Web Scraping + EDA + Power BI Dashboard)
📊 Overview

This project is an end-to-end data analysis of Amazon product sales.
It includes web scraping, data cleaning, exploratory data analysis (EDA), and a Power BI dashboard to visualize key insights such as discounts, ratings, and pricing trends.

🚀 Project Workflow

Web Scraping (Python)

Collected Amazon product data (product name, price, rating, etc.) using BeautifulSoup and requests.

Saved the scraped data into a structured CSV file for further processing.

Data Cleaning (Python + Pandas)

Removed missing, duplicate, and inconsistent values.

Converted data types (e.g., prices and ratings into numeric form).

Created additional features such as discount_percentage.

Exploratory Data Analysis (EDA)

Analyzed product ratings, discounts, and price variations.

Identified top discounted and top-rated products.

Visualized key metrics using Matplotlib and Seaborn.

Power BI Dashboard

Imported the cleaned dataset into Power BI.

Created interactive visuals:

Bar Chart: Top discounted products

Pie Chart: Discount distribution by product

Card Visuals: Key metrics (Total Products, Avg Rating, Avg Discount)

Matrix/Table: Product-wise detailed breakdown

Designed a professional, clean dashboard layout.

📁 Files in Repository
File Name	Description
amazon_scraper.py	Python script used for web scraping
amazon_cleaned_data.csv	Cleaned dataset after preprocessing
Amazon_Sale_Report.pbix	Power BI dashboard file
Amazon_Sale_Report.pdf	Exported version of the dashboard
README.md	Project documentation
🧠 Insights from the Dashboard

Products with higher discounts attract significantly more ratings.

Average discount across all products is around 60%.

Certain product categories maintain high prices but low ratings, showing market imbalance.

Top-performing products are those with balanced pricing and high user ratings.

🧰 Tools & Technologies

Python: Web Scraping, Data Cleaning, and EDA

Libraries: BeautifulSoup, requests, pandas, matplotlib, seaborn

Power BI: Dashboard design and visualization

Excel/CSV: Data verification and storage

📸 Dashboard Preview

(Attach a screenshot of your Power BI dashboard here after upload)
Example:

![Amazon Sale Dashboard](dashboard_preview.png)

📌 Key Learning Outcomes

Gained hands-on experience in data extraction from real websites.

Improved data cleaning and transformation skills using Python.

Built a business-ready dashboard using Power BI for visual storytelling.

💡 Future Improvements

Automate data refresh from live Amazon data sources.

Add category-level analysis (e.g., electronics, fashion, etc.).

Deploy dashboard online via Power BI Service or Streamlit.

👩‍💻 Author

Dhanujasri Sagadevan
Data Analyst | Python • Power BI • SQL • Machine Learning
🔗 LinkedIn
 • GitHub
