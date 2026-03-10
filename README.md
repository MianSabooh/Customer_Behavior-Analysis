
# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using a complete **data analytics workflow**. The goal is to extract meaningful insights from customer purchasing data and present them through a **professional Power BI dashboard**.

The project demonstrates the full analytics pipeline:

* Data loading and exploration in **Python**
* **Data cleaning and preprocessing**
* Querying the data using **PostgreSQL**
* Creating interactive visualizations in **Power BI**
* Presenting insights using **Gamma-generated slides**

This project highlights skills in **data analysis, SQL, visualization, and storytelling with data**.

---

## Dataset

The dataset used in this project contains information about customer shopping behavior including:

* Customer ID
* Age group
* Gender
* Category of purchased items
* Purchase amount
* Subscription status
* Shipping type
* Review ratings
* Previous purchases

The dataset helps analyze patterns such as:

* Revenue by product category
* Customer purchasing trends
* Sales by age group
* Subscription behavior
* Average purchase amount and customer ratings

---

## Tools & Technologies

| Tool                            | Purpose                                               |
| ------------------------------- | ----------------------------------------------------- |
| **Python**                      | Data loading, cleaning, and exploratory data analysis |
| **Pandas & Matplotlib/Seaborn** | Data manipulation and visualization                   |
| **PostgreSQL**                  | Running analytical SQL queries                        |
| **Power BI**                    | Interactive dashboard creation                        |
| **Gamma**                       | Creating presentation slides                          |
| **Jupyter Notebook**            | Running and documenting analysis                      |

---

## Project Workflow

### 1. Data Loading

The dataset was loaded into Python using **Pandas**.

Key tasks:

* Import dataset
* Inspect structure and columns
* Identify missing or inconsistent values

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns in the data.

Examples:

* Distribution of customers by gender
* Purchase behavior across categories
* Customer review ratings
* Age group purchasing patterns

Visualization tools were used to identify trends and anomalies.

---

### 3. Data Cleaning

Data preprocessing steps included:

* Handling missing values
* Standardizing column formats
* Removing duplicates
* Correcting inconsistent category values
* Preparing the dataset for database storage

Clean data ensures **accurate analysis and reliable dashboard insights**.

---

### 4. SQL Analysis (PostgreSQL)

The cleaned dataset was imported into **PostgreSQL** for analytical queries.

Example analysis:

* Top selling product categories
* Customer segmentation
* Revenue analysis
* Most purchased items per category
* Purchase frequency trends

Advanced SQL techniques used:

* **CTEs (Common Table Expressions)**
* **Window Functions**
* **Aggregations and Grouping**

---

### 5. Power BI Dashboard

An interactive **Customer Behavior Dashboard** was created to visualize insights.

Main dashboard features include:

**Key Metrics**

* Total Customers
* Average Purchase Amount
* Average Customer Rating

**Visualizations**

* Customer subscription percentage
* Revenue by category
* Sales by category
* Revenue by age group
* Sales by age group

**Interactive Filters**

* Subscription status
* Gender
* Product category
* Shipping type

This dashboard helps stakeholders quickly understand **customer trends and business performance**.

---

## Dashboard Insights

Key findings from the analysis:

* **Clothing category generated the highest sales.**
* **Young adults contribute the highest revenue.**
* The majority of customers **do not have subscriptions.**
* Average purchase amount is approximately **$59.76**.
* Customer satisfaction ratings average around **3.75**.

These insights can help businesses improve **marketing strategies, inventory planning, and customer targeting**.

---

## Presentation

Project insights were summarized into **professional slides using Gamma**.

The presentation includes:

* Project objectives
* Data analysis process
* Key findings
* Dashboard demonstration
* Business recommendations

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/customer-shopping-analysis.git
```

### 2. Install Python dependencies

```bash
pip install pandas matplotlib seaborn psycopg2
```

### 3. Run the Jupyter Notebook

Open and run:

```
DataCleaning.ipynb
```

This notebook performs:

* Data loading
* EDA
* Data cleaning

### 4. Load Data into PostgreSQL

Import the cleaned dataset into PostgreSQL and run the SQL queries included in the project.

### 5. Open Power BI Dashboard

Open the Power BI file to explore the **interactive customer behavior dashboard**.

---

## Project Structure

```
Customer-Shopping-Analysis
│
├── data
│   └── customer_shopping_behavior.csv
│
├── notebooks
│   └── DataCleaning.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── presentation
│   └── project_slides.pptx
│
└── README.md
```

---

## Skills Demonstrated

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* SQL Query Optimization
* Data Visualization
* Business Insight Generation
* Dashboard Development
* Data Storytelling



