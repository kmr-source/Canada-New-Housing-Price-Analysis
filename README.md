# Canada Housing Data Explorer Dashboard

A dashboard providing insights into Canada's housing market trends using the National Housing Index (NHI). This project visualizes housing price dynamics across provinces, regions, and cities, helping analysts, policymakers, and homebuyers understand affordability, growth, and market shifts.

🔗 Dashboard Link: https://kmr-source.github.io/Portfolio/dashboard.html
---

## 📊 Features

- **National & Provincial Indices:** Track the latest housing price indices and growth trends.  
- **Top & Bottom Performing Regions:** Identify fastest-growing and most affordable areas.  
- **Year-over-Year Growth:** Monitor short- and long-term changes in the housing market.  
- **City-Level Analysis & Heatmaps:** Visualize regional disparities and affordability trends.  
- **Interactive KPI Cards:** Quickly highlight key metrics like latest national index, fastest-growing provinces, and coverage period.  
- **Responsive Dashboard Layout:** Designed with clean HTML/CSS grid for smooth navigation and readability.

---

## 🛠 Technology Stack

- **Database & SQL:** Extract and aggregate housing price index data.  
- **Python:** Data manipulation and analysis using Pandas; plotting with Matplotlib & Seaborn.  
- **HTML/CSS:** Responsive dashboard with KPI cards, chart cards, and hover effects.  
- **Visualization:** Line charts, bar charts, heatmaps for clear data storytelling.

## Dependencies:
- Python 3.10+
- pandas
- numpy
- SQLAlchemy (or relevant DB connector)
- matplotlib / seaborn
---

## 📂 Project Structure
project-root/
│
├─ data/              # Raw and cleaned CSV files
├─ notebook/           # Python scripts for cleaning, loading, and analysis
├─ sql/# SQL scripts (insert statements, queries)
├─ requirements.txt   # Python dependencies
└─ README.md
└─ Dashboard.html # dashboard interface, live on github porfolio 


## Project Workflow

1. **Data Cleaning**
   - Raw CSV files from Statistics Canada are cleaned using Python.
   - Missing values and inconsistencies are handled to ensure data integrity.

2. **Database Operations**
   - Cleaned CSV data is loaded into local database tables using SQL `INSERT` statements.
   - SQL queries are executed to manipulate and prepare the data for analysis.

3. **Data Analysis & Visualization**
   - Python scripts query the database to retrieve data for analysis.
   - Data is analyzed and visualized using Python plotting libraries (e.g., Matplotlib, Seaborn).

---

## Environment setup Local 

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt



---

💡 Optional Extras You Can Add:
- Badges for Python version, build status, or coverage.
- Screenshots of plots for quick visualization reference.
- Examples of SQL queries or graphs in a `docs/` folder.  

---


