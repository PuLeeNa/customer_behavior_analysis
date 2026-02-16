# Customer Behavior Analysis

A comprehensive data analytics project that analyzes customer shopping behavior using Python, SQL, and Power BI to derive actionable insights for business decision-making.

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Analysis Components](#analysis-components)
- [Key Insights](#key-insights)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## 🎯 Overview

This project demonstrates end-to-end data analysis of customer shopping behavior, including:
- Data exploration and cleaning using Python
- Advanced SQL queries for business intelligence
- Interactive Power BI dashboard for visualization
- Insights into customer segments, purchasing patterns, and revenue drivers

## 📊 Dataset

The dataset (`customer_shopping_behavior.csv`) contains customer shopping data with the following attributes:

| Column | Description |
|--------|-------------|
| Customer ID | Unique identifier for each customer |
| Age | Customer's age |
| Gender | Customer's gender (Male/Female) |
| Item Purchased | Name of the purchased item |
| Category | Product category (Clothing, Footwear, Accessories, Outerwear) |
| Purchase Amount (USD) | Purchase amount in USD |
| Location | Customer's location (US states) |
| Size | Product size (S, M, L, XL) |
| Color | Product color |
| Season | Season of purchase (Winter, Spring, Summer, Fall) |
| Review Rating | Product review rating (1-5) |
| Subscription Status | Whether customer has a subscription (Yes/No) |
| Shipping Type | Type of shipping selected |
| Discount Applied | Whether discount was applied (Yes/No) |
| Promo Code Used | Whether promo code was used (Yes/No) |
| Previous Purchases | Number of previous purchases |
| Payment Method | Payment method used |
| Frequency of Purchases | How often customer makes purchases |

## 🛠️ Technologies Used

- **Python**: Data analysis and manipulation
  - pandas: Data processing and analysis
  - Jupyter Notebook: Interactive analysis environment
- **SQL (PostgreSQL)**: Advanced querying and data aggregation
- **Power BI**: Interactive dashboard and visualizations
- **CSV**: Data storage format

## 📁 Project Structure

```
customer_behavior_analysis/
│
├── customer_shopping_behavior.csv          # Main dataset
├── custmer_shopping_behaviour.ipynb       # Python analysis notebook
├── SQL qureries for analysis.sql          # SQL queries for business insights
├── customer dashboard.pbix                 # Power BI dashboard file
└── README.md                               # Project documentation
```

## 🔍 Analysis Components

### 1. Python Analysis (Jupyter Notebook)
The `custmer_shopping_behaviour.ipynb` notebook includes:
- Data loading and exploration
- Data cleaning and preprocessing
- Statistical analysis
- Data visualization
- Pattern identification

### 2. SQL Analysis
The `SQL qureries for analysis.sql` file contains 10 business-critical queries:

1. **Revenue by Gender**: Total revenue comparison between male and female customers
2. **Discount Impact**: Customers who used discounts but spent above average
3. **Top-Rated Products**: Top 5 products with highest review ratings
4. **Shipping Analysis**: Average purchase amounts by shipping type
5. **Subscription Value**: Revenue and spend comparison for subscribed vs non-subscribed customers
6. **Discount Distribution**: Products with highest discount usage percentage
7. **Customer Segmentation**: Categorization into New, Returning, and Loyal customers
8. **Category Insights**: Top 3 products per category
9. **Repeat Buyer Behavior**: Subscription status of repeat buyers
10. **Age Group Revenue**: Revenue contribution by age group

### 3. Power BI Dashboard
The `customer dashboard.pbix` provides:
- Interactive visualizations
- KPI metrics
- Customer segmentation analysis
- Revenue trends and patterns
- Filtering capabilities for deep-dive analysis

## 💡 Key Insights

This analysis helps answer critical business questions:
- Which customer segments generate the most revenue?
- How do subscriptions affect customer spending?
- What products and categories perform best?
- How effective are discounts and promotions?
- What are the characteristics of loyal customers?
- Which shipping options are preferred by high-value customers?

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- PostgreSQL (for SQL queries)
- Power BI Desktop (for dashboard)
- Jupyter Notebook

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/PuLeeNa/customer_behavior_analysis.git
   cd customer_behavior_analysis
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas jupyter matplotlib seaborn
   ```

3. **Set up PostgreSQL (optional)**
   - Import the CSV data into your PostgreSQL database
   - Run the queries from `SQL qureries for analysis.sql`

## 📖 Usage

### Running Python Analysis
```bash
jupyter notebook custmer_shopping_behaviour.ipynb
```

### Running SQL Queries
1. Import `customer_shopping_behavior.csv` into your PostgreSQL database
2. Execute queries from `SQL qureries for analysis.sql`

### Viewing Power BI Dashboard
1. Open `customer dashboard.pbix` in Power BI Desktop
2. Update data source connection if needed
3. Explore interactive visualizations

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📧 Contact

For questions or feedback, please open an issue in this repository.

---

**Note**: This project is for educational and portfolio purposes, demonstrating data analysis capabilities using multiple tools and technologies.
