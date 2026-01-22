# 🎮 Instacart Data Analysis - Customers purchases patterns

Comprehensive analysis of customer purchases of Instacart business to identify patterns about shopping habits of Instacart users.

## 🎯 Project Objectives

**Business Problem:** Identify the shopping habits of Instacart users.

**Key Questions Answered:**
-What are the temporal patterns related to the sales data in the dataset?
-Which products are the most popular?
-What are the repurchase behaviors?

## 🛠️ Technologies Used

- **Python 3.8+**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical calculations
- **matplotlib & seaborn** - Data visualization
- **scipy** - Statistical tests and hypothesis testing
- **Jupyter Notebook** - Development and documentation

📊 Dataset
Source: Instacart Market Basket Analysis (Kaggle 2017)
Records: 3+ million grocery orders from 200,000+ users
Time Period: Historical data with order sequences

Data Tables:
- instacart_orders.csv - Order-level information
- products.csv - Product catalog
- order_products.csv - Items in each order
- aisles.csv - Store aisle categories
- departments.csv - Store departments

🔍 Analysis Methodology
### 1. Data Preparation
- Multi-table data loading and inspection
- Data type validation and conversion
- Missing value identification and treatment
- Duplicate record detection and removal
- Data quality assessment across all tables

### 2. Exploratory Data Analysis
- Temporal Patterns:
  - Peak ordering hours analysis
  - Day-of-week shopping preferences
  - Time between orders distribution
  - Product Analysis:
    - Top 20 most frequently ordered products
    - Reorder rate analysis by product
    - First-item-to-cart patterns
  - Customer Behavior:
    - Order frequency distribution
    - Shopping cart size analysis
    - Customer reorder propensity

### 3. Data Visualization
- Histograms for temporal patterns
- Bar charts for product rankings
- Distribution plots for customer metrics
- Comparative analysis charts

📈 Key Findings

### 🕐 Shopping Patterns
- Peak Hours: 10 AM - 4 PM (highest activity)
- Popular Days: Saturday and Sunday (weekend shopping)
- Reorder Frequency: Average 30 days between orders

### 🥕 Product Insights
- Top Products: Bananas, Bag of Organic Bananas, Organic Strawberries
- High Reorder Rate: Fresh produce and dairy products (80%+ reorder rate)
- Popular Aisles: Fresh fruits, fresh vegetables, packaged vegetables/fruits

### 🛍️ Customer Behavior
- Average Cart Size: 10-11 items per order
- Order Frequency: Most customers place 4-6 orders in dataset period
- Reorder Tendency: 60% of items in orders are reorders

### 📊 Department Performance
1. Produce: Highest volume and reorder rates
2. Dairy Eggs: Strong consistent demand
3. Snacks: Popular but lower reorder rates

📁 Project Structure

```
├── data/
│   ├── extract the datasets from the following link: https://drive.google.com/drive/folders/1E1Gq3XBXiDMBTMe-8FhkjGmHUTIEnNuf?usp=sharing
├── notebooks/
│   └── Ventas_clientes_Instacart.ipynb
├── requirements/
│   └── requirements.txt
├── images/
│   └── visualizations/
└── README.md

🚀 Instalation & how it works?

  1. Clone the repository
  2. Download the datasets and save them at the same position where Jupyter Notebook is located, but inside a folder named "Datsets"
  3. Install dependencies: `pip install -r requirements.txt`
  4. Open the notebook: `Ventas_clientes_Instacart.ipynb`

📧 Contact

  - LinkedIn: https://www.linkedin.com/in/luis-andres-aponte-san-roman/
  - Email: andres_laasr20@outlook.com
