#  Customer Shopping Behavior Analysis

##  Overview

This project focuses on analyzing customer shopping behavior using a combination of SQL, Python (NumPy), and Power BI. The objective is to extract meaningful insights from raw transactional data, perform data cleaning and analysis, and present the results through an interactive dashboard.

---

##  Dataset

* The dataset contains customer shopping data including:

  * Customer details
  * Purchase frequency
  * Transaction values
  * Product categories
* Data was initially stored in a relational database and processed for analysis.

---

##  Tools & Technologies

* **SQL (PostgreSQL / MySQL / SQL Server)** – Data extraction and querying
* **Python (NumPy)** – Data cleaning and numerical analysis
* **Power BI** – Dashboard creation and visualization
* **Jupyter Notebook** – Analysis workflow
* **Gamma (PPT tool)** – Presentation creation

---

##  Project Workflow

### 1. Data Loading

* Imported dataset into SQL database
* Structured tables for efficient querying

### 2. Data Cleaning (Python + NumPy)

* Removed missing/null values
* Standardized data formats
* Performed numerical transformations using NumPy

### 3. SQL Analysis

* Wrote queries to:

  * Segment customers (New, Returning, Loyal)
  * Analyze purchase frequency
  * Calculate revenue metrics
* Used aggregation, CASE statements, and joins

### 4. Data Visualization (Power BI)

* Built an interactive dashboard including:

  * Customer segmentation
  * Sales trends
  * Revenue distribution
  * Purchase behavior insights

### 5. Reporting

* Summarized insights into a structured report
* Created a presentation (PPT) using Gamma

---

##  Dashboard Highlights

* 📈 Sales trend over time
* 👥 Customer segmentation (New / Returning / Loyal)
* 💰 Revenue analysis
* 🛒 Purchase frequency insights

---

##  Key Results & Insights

* Identified high-value customer segments
* Observed patterns in repeat purchases
* Found key revenue-driving categories
* Provided actionable insights for business decision-making

---

##  How to Run

### Step 1: SQL Setup

* Open the `.sql` file
* Run queries in PostgreSQL/MySQL/SQL Server

### Step 2: Python Analysis

* Open the `.ipynb` notebook in Jupyter
* Install required libraries:

  ```bash
  pip install numpy pandas
  ```
* Run all cells for data cleaning and analysis

### Step 3: Power BI Dashboard

* Open `.pbix` file in Power BI Desktop
* Refresh data if needed

---

##  Project Files

* `customershoppingbehaviour.ipynb` → Python analysis
* `postgre sql code.sql` → SQL queries
* `Customer_Behavior_Dashboard.pbix` → Power BI dashboard

---

##  Conclusion

This project demonstrates end-to-end data analytics workflow — from raw data processing to business insights visualization. It highlights skills in SQL querying, numerical analysis using NumPy, and dashboard creation using Power BI.

---

##  Future Improvements

* Add machine learning models for prediction
* Automate data pipeline
* Integrate real-time data

---

