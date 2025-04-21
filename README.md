# ecommerce-data-joins-analysis
Joining and manipulating ecommerce order and supply chain data using python

# 🛍️ Ecommerce Order & Supply Chain Data Analysis

This project demonstrates how to join and manipulate datasets using pandas in Python. The data simulates an ecommerce platform, including customer information, order details, payments, and product information. The goal is to explore how SQL-style joins, filtering, pivoting, and aggregation can be used to gain meaningful insights into the order fulfillment process.

---

## 📁 Datasets Used

- **Customers**: Basic details of the customers
- **Orders**: Order metadata including timestamps
- **Order Items**: Information on products per order
- **Payments**: Payment methods and amounts per order
- **Products**: Product-level information

---

## 🧰 Tools & Libraries

- Python (pandas, matplotlib, seaborn, calender)
- Data sourced from Kaggle: [Ecommerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📊 Key Analyses

- SQL-style joins between multiple tables
- Monthly order volume and revenue trend analysis
- Top performing product categories
- Customer-level order aggregation
- Handling missing data and date parsing
- Pivot tables for summarizing multiple metrics

---

## 📈 Visualizations

- Line plots of monthly sales trends
- Line plots of yearly sales trend

---

## 💡 Insights

- Seasonal fluctuations in sales volume
- Trends in customer purchasing behavior

---

## 🗃️ Folder Structure

```bash
ecommerce-data-joins-analysis/
│
├── ecommerce_joins.ipynb      # Main notebook
├── README.md                  # Project overview
└── data/
    └── customers.csv
    └── orders.csv
    └── order_items.csv
    └── payments.csv
    └── products.csv
