# Financial Data Analysis - Python

## 📊 Financial Data Pipeline: Comparative Analysis of Tesla and GameStop

### 📋 Project Description

This project implements a robust data pipeline to extract, process, and visualize the relationship between corporate revenue and stock market performance. By leveraging both API integration and automated web scraping, the analysis provides a visual correlation between a company's fundamental financial health and its historical share price.

The study focuses on two distinct market cases:
- **Tesla (TSLA)**: Representing high-growth tech volatility
- **GameStop (GME)**: Illustrating retail-driven market dynamics

**Performance Achievement**: This project received a **90% "Legendary Performance"** rating by successfully synchronizing non-aligned time-series data and resolving data-type conflicts during the analysis phase.

---

### 🛠️ Technical Implementation

#### Data Acquisition
- Automated historical stock data retrieval using the **yfinance** library
- Direct access to Yahoo Finance API for real-time and historical stock prices

#### Web Scraping
- Developed a custom scraper with **BeautifulSoup** to parse quarterly revenue tables
- Extraction from dynamic HTML sources for reliable financial data

#### Data Wrangling
- **Currency symbol stripping** and numeric type-casting (String-to-Float conversion)
- **Handling of missing values** (NaN) to maintain dataset integrity
- Complex data cleaning protocols for alignment and standardization

#### Data Visualization
- Engineered a **dual-axis dashboard** for simultaneous tracking of:
  - Stock price trends over time
  - Revenue milestones and quarterly performance
  - Correlation analysis between revenue and stock performance

---

### 📦 Installation

#### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

#### Setup Instructions

1. **Clone the repository**:
```bash
git clone https://github.com/almustafaomer-debug/Financial-Data-Analysis-python.git
cd Financial-Data-Analysis-python
```

2. **Install required dependencies**:
```bash
pip install -r requirements.txt
```

Or install packages individually:
```bash
pip install yfinance beautifulsoup4 pandas matplotlib requests
```

---

### 🚀 Quick Start

1. **Open the Jupyter Notebook**:
```bash
jupyter notebook "Revenue Data and Building a Dashboard.ipynb"
```

2. **Run the analysis**: Execute the notebook cells to:
   - Fetch historical stock data for Tesla and GameStop
   - Scrape quarterly revenue data
   - Generate comparative visualizations

3. **View the dashboard**: The script will produce dual-axis charts showing stock price vs. revenue trends

---

### 📁 Project Structure

```
Financial-Data-Analysis-python/
├── README.md                                      # Project documentation
├── Revenue Data and Building a Dashboard.ipynb   # Main analysis notebook
└── requirements.txt                              # Python dependencies (optional)
```

---

### 📊 Key Features

✅ **Automated Data Pipeline**: Seamless extraction from multiple sources  
✅ **Advanced Data Cleaning**: Handles missing values and type conversions  
✅ **Comparative Analysis**: Side-by-side analysis of two market dynamics  
✅ **Professional Visualizations**: Dual-axis dashboard for correlation insights  
✅ **Scalable Design**: Can be extended to analyze additional stocks  

---

### 📈 Analysis Insights

This project demonstrates:
- How API integration and web scraping work together for comprehensive data collection
- Data cleaning best practices for financial datasets
- Visualization techniques for time-series correlation analysis
- The relationship between corporate fundamentals and market performance

---

### 🔧 Technologies Used

| Technology | Purpose |
|---|---|
| **yfinance** | Stock data retrieval |
| **BeautifulSoup** | Web scraping |
| **Pandas** | Data manipulation & analysis |
| **Matplotlib** | Data visualization |
| **Jupyter Notebook** | Interactive analysis environment |
| **Python 3** | Core programming language |

---

### 📝 License

This project is provided as-is for educational purposes.

### 👨‍💻 Author

**ELMUSTAFA OSMAN**

---

### 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

---

**Last Updated**: April 2026
