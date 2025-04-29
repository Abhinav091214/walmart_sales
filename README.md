# 🛒 Walmart Sales Analysis

This project analyzes a synthetic dataset of Walmart sales to uncover key business insights, including high-performing product categories, branch performance, peak transaction times, and customer preferences. The dataset is provided as a part of the repository or can be obtained from the kaggle link shown below.

## 📁 Dataset

**Source:** [Kaggle - Walmart 10K Sales Dataset](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets) 

The dataset includes the following columns:
- `Invoice ID`
- `Branch` (A, B, C)
- `City`
- `Customer type`
- `Gender`
- `Product line` (Category)
- `Unit price`
- `Quantity`
- `Tax 5%`
- `Total`
- `Date`
- `Time`
- `Payment` (Cash, Credit card, Ewallet)
- `COGS`
- `Gross margin percentage`
- `Gross income`
- `Rating`

## 📊 Objectives

1. Identify the **highest-rated category** in each branch.
2. Determine the **busiest day** (most transactions) per branch.
3. Analyze the **most common payment method** used in each branch.
4. Visualize customer behavior and sales trends.
5. Store data in a **MySQL database** and perform SQL queries for analysis.

## 🧰 Technologies Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL** (MySQL, MySQL Workbench)
- **SQLAlchemy & PyMySQL** (for Python-MySQL integration)
- **Jupyter Notebook / VS Code**
- **Kaggle CLI** (for dataset download)

## ⚙️ Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Abhinav091214/walmart_sales/.git
   cd walmart_sales

2. ** Install dependencies (also given in requirements.txt)

   ```bash
   pip install pandas matplotlib seaborn pymysql sqlalchemy

  OR
  
  ```bash
   pip install -r requirements.txt

