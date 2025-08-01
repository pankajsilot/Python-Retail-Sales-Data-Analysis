# 🛒 Retail Sales Data Analysis Project (Python)

This project demonstrates a complete **retail data analysis workflow** using Python. The dataset, based on Indian festive sales, includes detailed customer and transaction data. The aim is to uncover meaningful insights about consumer behavior, regional sales patterns, and product trends to inform business decisions — as a real-world **Data Analyst** would.

## 📌 Project Objectives

* Clean and preprocess sales data
* Perform Exploratory Data Analysis (EDA)
* Visualize demographic, geographic, and transactional trends
* Generate actionable business insights

## 🛠️ Tools & Technologies Used

* **Programming Language:** Python 3.x
* **Libraries:** pandas, numpy, matplotlib, seaborn
* **Platform:** Jupyter Notebook / Google Colab

## 🧾 Dataset Overview

The dataset contains structured sales data, including the following columns:

| Column Name       | Description                         |
| ----------------- | ----------------------------------- |
| User\_ID          | Unique ID of the customer           |
| Cust\_name        | Name of the customer                |
| Product\_ID       | Unique product identifier           |
| Gender            | Gender of the customer              |
| Age Group & Age   | Customer's age range and actual age |
| Marital\_Status   | 0 = Single, 1 = Married             |
| State             | Customer's state                    |
| Zone              | Geographic zone of the customer     |
| Occupation        | Customer's job sector               |
| Product\_Category | Product category                    |
| Orders            | Number of products ordered          |
| Amount            | Total purchase amount in INR        |

## 🔍 Key Steps Performed

### 1. Data Cleaning

* Removed null and irrelevant columns (`Status`, `unnamed1`)
* Fixed encoding issues in CSV import
* Handled missing values and type conversion

### 2. Exploratory Data Analysis (EDA)

* Analyzed:

  * Gender and age-wise buying patterns
  * Marital status vs spending behavior
  * State-wise and zone-wise revenue generation
  * Top performing product categories
* Created visualizations:

  * Bar charts, pie charts, histograms
  * Grouped summaries and insights

### 3. Insights & Recommendations

* **Target Audience:** Married females aged 26–35 contribute most to sales
* **Top Revenue States:** Uttar Pradesh, Maharashtra, Karnataka
* **Best-Selling Categories:** Food, Clothing, Electronics
* Suggest personalized marketing campaigns and inventory planning based on demographics and regional demand

## 📁 Project Files

* `Retail_Sales_Data.csv` – Original dataset
* `Retail_Data_Analysis.ipynb` – Python analysis notebook
* `README.md` – Project documentation

## 📊 Sample Visuals Used

```python
# Example: Gender distribution
sns.countplot(x='Gender', data=df)

# Example: Total sales by state
df.groupby('State')['Amount'].sum().sort_values(ascending=False).plot(kind='bar')
```

## 🎯 Outcome

This portfolio project replicates a real-life analytics problem in the retail/e-commerce space. It demonstrates end-to-end proficiency in:

* Data cleaning & wrangling
* Exploratory data analysis
* Business thinking & interpretation
* Data storytelling using visualizations

## 📎 Author

**Pankaj Silot**
[LinkedIn](https://www.linkedin.com/in/pankaj-silot/) | [GitHub](https://github.com/pankajsilot)
