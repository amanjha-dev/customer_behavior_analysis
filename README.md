# Customer Trend Analysis

A comprehensive data analysis project that explores customer shopping behavior patterns using Python, SQL, and Power BI visualization.

## 📋 Project Overview

This project analyzes customer shopping behavior to identify trends, patterns, and insights that can drive business decisions. The analysis combines data processing with Python, data querying with SQL, and interactive visualization with Power BI.

## 🛠️ Technologies Used

- **Python 3.x** - Data processing, cleaning, and exploratory data analysis
- **Pandas & NumPy** - Data manipulation and numerical computations
- **SQL** - Database queries and data aggregation
- **Power BI** - Interactive dashboards and business intelligence visualization
- **Jupyter Notebook** - Interactive code execution and documentation
- **Anaconda** - Python environment management

## 📁 Project Structure

```
CustomerTrendAnalysis/
├── README.md
├── Customer_Shopping_Behavior_Analysis.ipynb    # Main analysis notebook
├── customer_shopping_behavior.csv                # Raw customer data
└── anaconda_projects/
    └── db/                                       # Database files
```

## 📊 Dataset

**File:** `customer_shopping_behavior.csv`

The dataset contains customer shopping transaction records with attributes including:
- Customer demographics (age, gender, location)
- Purchase behavior (amount spent, frequency, product category)
- Temporal data (purchase dates, seasonality)
- Transaction details and patterns

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Anaconda or Miniconda
- SQL Server / SQLite (as configured in the project)
- Power BI Desktop (for visualization)
- Jupyter Notebook

### Installation

1. **Clone or navigate to the project directory:**
   ```bash
   cd CustomerTrendAnalysis
   ```

2. **Set up the Anaconda environment:**
   ```bash
   conda env create -f environment.yml
   conda activate customer-analysis
   ```
   
   Or manually install required packages:
   ```bash
   pip install pandas numpy jupyter matplotlib seaborn plotly sqlalchemy
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb
   ```

## 📈 Analysis Workflow

1. **Data Loading & Cleaning**
   - Load customer data from CSV
   - Handle missing values and outliers
   - Data type conversion and validation

2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries and distributions
   - Customer segmentation analysis
   - Trend identification across time periods

3. **SQL Queries**
   - Import cleaned data into database (`anaconda_projects/db/`)
   - Execute aggregation queries for detailed insights
   - Generate summary statistics by customer segments

4. **Visualization & Reporting**
   - Create Power BI dashboards using SQL data sources
   - Interactive filters and drill-down capabilities
   - Key performance indicators (KPIs) and trend charts

## 🔍 Key Insights & Objectives

- Identify customer purchasing patterns and seasonality
- Segment customers based on behavior and demographics
- Analyze product category preferences
- Track spending trends over time
- Generate actionable business recommendations

## 📊 Power BI Integration

1. **Data Source:** Connect Power BI to the SQL database in `anaconda_projects/db/`
2. **Visualizations:** 
   - Customer segmentation scatter plots
   - Time series trends
   - Category-wise sales analysis
   - Demographic breakdowns
3. **Interactivity:** Filters by date range, customer segment, and product category
