# Data Analysis Project using Python

## Project Overview

This project focuses on analyzing a sales dataset to identify patterns, trends, distributions, and business insights using Python. The analysis was performed as part of a Data Analytics internship task and demonstrates the use of descriptive statistics, trend analysis, and outlier detection techniques.

---

## Objectives

The main objectives of this project were:

* Analyze a dataset to understand patterns and trends.
* Calculate descriptive statistics such as mean, median, minimum, maximum, and count.
* Identify trends in sales performance over time.
* Detect outliers using statistical methods.
* Summarize key business observations and insights.

---

## Tools and Libraries Used

* Python
* Visual Studio Code (VS Code)
* Pandas
* Matplotlib
* OpenPyXL

---

## Dataset Information

The dataset contains customer order information including:

* Date
* Product Name
* Quantity
* Unit Price
* Total Price
* Payment Method
* Customer Information
* Coupon Code

After cleaning, the dataset contained:

* 1200 Rows
* 14 Columns

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Verified column names and data types.
* Inspected the dataset structure.

### 2. Descriptive Statistics

Calculated:

* Mean
* Median
* Count
* Minimum
* Maximum

For the following numerical columns:

* Quantity
* UnitPrice
* ItemsInCart
* TotalPrice

### 3. Trend Analysis

* Converted the Date column to datetime format.
* Extracted month information.
* Grouped sales by month.
* Identified the highest-performing month based on revenue.

### 4. Product Performance Analysis

* Grouped products by total revenue.
* Ranked products from highest to lowest revenue.
* Identified top-performing products.

### 5. Outlier Detection

Used the Interquartile Range (IQR) method:

* Calculated Q1 and Q3.
* Calculated IQR.
* Determined the upper outlier limit.
* Identified unusually high-value orders.


## Key Findings

* The average customer purchased approximately 3 items per order.
* The average order value was approximately 1054.
* Revenue was concentrated among a few top-performing products.
* June 2024 generated the highest monthly sales.
* Several high-value orders were identified as outliers using the IQR method.
* Product sales and customer spending showed clear variations across the dataset.

---

## Skills Demonstrated

* Data Cleaning
* Data Analysis
* Descriptive Statistics
* Python Programming
* Pandas Data Manipulation
* Analytical Thinking
* Business Insight Generation

---

## How to Run the Project

1. Clone or download this repository.
2. Install required libraries:

```bash
pip install pandas matplotlib openpyxl
```

3. Place the dataset file in the project folder.
4. Run:

```bash
python analysis.py
```

5. Review the generated outputs and visualizations.

---

## Project Outcome

This project demonstrates the ability to perform end-to-end exploratory data analysis using Python, transform raw data into meaningful insights, and communicate findings through statistical analysis and visualization.
