# 📚 ETL Book Data Scrape Project

An end-to-end **ETL (Extract → Transform → Load)** project that scrapes book data from the **Books to Scrape** website, transforms it into an analytics-ready format, stores it in multiple formats, and visualizes key insights through an interactive dashboard.

This project demonstrates a real-world data engineering workflow using Python and showcases skills in web scraping, data transformation, database management, and dashboard development.

---

## 🚀 Project Features

- 🌐 Scrape book data using **Requests** and **BeautifulSoup**
- 🔄 Clean and transform data with **Pandas**
- 💾 Store processed data in **SQLite** and **Parquet**
- 📊 Build an interactive dashboard using **Streamlit** and **Plotly**
- 📁 Well-structured ETL project following best practices
- 🔧 Version controlled with **Git & GitHub**

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python 3.10+ |
| Web Scraping | Requests, BeautifulSoup4, lxml |
| Data Processing | Pandas |
| Database | SQLite |
| Data Storage | Parquet, SQLAlchemy, PyArrow |
| Visualization | Streamlit, Plotly, Altair |
| Version Control | Git, GitHub |

---

## 🔄 ETL Workflow

### 📥 Extract (`scrape.py`)

- Scrapes book details from multiple pages of the **Books to Scrape** website.
- Extracts:
  - Book Title
  - Price
  - Rating
  - Stock Availability
  - Category
- Saves the raw dataset as **CSV** and **JSON**.

---

### 🔄 Transform & Load (`transform_and_load.py`)

- Cleans and standardizes the extracted data.
- Converts prices into numeric values.
- Maps book ratings into numerical format.
- Creates an analytics-ready dataset.
- Loads the processed data into:
  - SQLite Database
  - Parquet Files

---

### 📊 Dashboard (`dashboard.py`)

The Streamlit dashboard provides interactive visualizations including:

- 📚 Books by Category
- 💰 Top 10 Most Expensive Books
- 📦 Stock Availability Analysis
- 📈 Interactive Charts and Filters

---

## 📂 Project Structure

```text
ETL_Book_Data_Scrape_Project/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── books.db
│
├── src/
│   ├── scrape.py
│   ├── transform_and_load.py
│   └── dashboard.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Rudresh99/ETL_Book_Data_Scrape_Project.git

cd ETL_Book_Data_Scrape_Project
```

### 2. Create a Virtual Environment

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the ETL Pipeline

Extract data:

```bash
python src/scrape.py
```

Transform and load data:

```bash
python src/transform_and_load.py
```

Launch the dashboard:

```bash
streamlit run src/dashboard.py
```

---

## 📊 Dashboard Preview

The dashboard enables users to:

- Analyze book categories
- Compare book prices
- Identify the most expensive books
- Explore stock availability
- Interact with visual reports using filters

---

## 🎯 Skills Demonstrated

- Web Scraping
- ETL Pipeline Development
- Data Cleaning & Transformation
- SQL & SQLite
- Parquet Data Storage
- Data Visualization
- Streamlit Dashboard Development
- Python Programming
- Git & GitHub

---

## 📌 Data Source

This project uses data from the public practice website:

**Books to Scrape**  
http://books.toscrape.com

The website is intended for learning and practicing web scraping techniques.

---

## 👨‍💻 Author

**Rudresh Joshi**

**Data Engineer | Python | SQL | ETL | Data Analytics**

📧 rudreshjoshi99@gmail.com

🔗 GitHub: https://github.com/Rudresh99

---

⭐ If you found this project useful, consider giving the repository a **Star**.
