# Coffee Chain Sales Analysis ☕📊

This project presents an end-to-end exploratory data analysis (EDA) of a coffee retail chain sales dataset.
The analysis focuses on sales patterns across time, stores, and product hierarchies, with particular attention to pricing behavior and seasonality.

## 📁 Project Structure

```
coffee-chain-sales-analysis/
├── data/
│   ├── Coffee Shop Sales.csv
│   └── Coffee Shop Sales.xlsx
├── notebooks/
│   ├── 01_exploratory_analysis.ipynb
│   └── 02_structured_nb.ipynb
├── Coffee_Retail_Analysis.pdf
├── .gitignore
├── LICENSE
└── README.md
```

## 🔍 Objective

- Understand overall sales behavior across time, stores, and products
- Identify key revenue drivers at category and product levels
- Explore pricing structure and anomalies in transaction data
- Examine potential seasonal patterns in beverage sales

📄 **Project Report**  
A concise summary of key findings is available in  
`Coffee_Retail_Analysis.pdf`.

## 🛠 Tools & Technologies

- Python: pandas, numpy
- Visualization: matplotlib, seaborn, plotly
- Environment: Jupyter Notebook (VS Code)
- Version Control: Git/GitHub

## 🧪 Key Analytical Questions

The analysis is structured around the following questions:
1.	When do sales peak during the day?
Hourly sales patterns and peak transaction windows.
2.	Which stores perform best?
Revenue and volume comparison across store locations.
3.	Which product categories and types drive revenue?
Hierarchical analysis from category → product type → individual items.
4.	What are the best-selling products?
Identification of top products by revenue and quantity sold.
5.	How does price relate to quantity sold?
Exploration of the relationship between unit price and sales volume.
6.	Are there seasonal trends in monthly sales?
Monthly aggregation to detect seasonality, especially for hot beverages.

## 🧹 Data Preparation Highlights

Key data engineering steps include:
- Parsing and standardizing transaction timestamps
- Deriving time-based features (hour, date, month)
- Cleaning numeric fields such as unit price and quantity
- Constructing revenue metrics from transactional data

## 💡 Key Findings (Summary)
- Sales show clear time-of-day patterns, with identifiable peak hours.
- Revenue distribution varies significantly across stores.
- A small number of product categories account for a large share of total revenue.
- Individual products can appear under multiple price points, indicating pricing complexity.
- The correlation between unit price and quantity sold is weak, suggesting demand is not strongly price-driven.
- Certain beverage categories exhibit early signs of seasonality at the monthly level.

Detailed figures and supporting visualizations are available in the notebook.

## 📌 Project Status

- [x] Data cleaning & feature engineering
- [x] Exploratory data analysis (EDA)
- [x] Insight generation
- [ ] Report formating

## 🚀 Possible Extensions
- Interactive dashboard (Tableau / Power BI)
- Deeper pricing strategy analysis
- Store-level performance benchmarking
- Demand forecasting models

## ✍️ Author

Yunying Liang  
[LinkedIn](https://www.linkedin.com/in/yunying-liang//) • Portfolio (in progress)