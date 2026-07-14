🍽️ **FoodConnect ETL Pipeline**

An end-to-end Food Waste Analytics project that transforms raw food waste data into meaningful business insights using **Python, PostgreSQL, SQL, and Power BI**. The project demonstrates the complete ETL (Extract, Transform, Load) workflow, followed by SQL-based analysis and interactive dashboards for decision-making.

---

**📌 Problem Statement**

Food waste is a major challenge in restaurants, catering services, and event management. Large amounts of food are wasted due to poor planning, inaccurate demand forecasting, improper storage, and inefficient food preparation.

Without proper analysis, organizations struggle to answer questions such as:

- Which food categories generate the most waste?
- Which event types produce the highest food wastage?
- How much revenue is lost due to wasted food?
- Which storage conditions minimize waste?
- Can surplus food be donated instead of discarded?

---

**💡 Solution**

This project builds a complete analytics pipeline that extracts raw food waste data, cleans and transforms it using Python, stores it in PostgreSQL, performs SQL-based business analysis, and visualizes insights through interactive Power BI dashboards.

The solution helps identify waste patterns, estimate financial losses, and support data-driven decisions for reducing food waste.

---

**🎯 Project Objectives**

- Analyze food waste across different event types.
- Identify the most wasteful food categories.
- Calculate revenue loss caused by food waste.
- Study the impact of storage conditions and preparation methods.
- Perform SQL-based business analysis.
- Build interactive Power BI dashboards for decision-making.

---

**🛠 Tech Stack**

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

**🔄 ETL Pipeline**

```text
Raw Dataset
      │
      ▼
Python
(Data Cleaning & Feature Engineering)
      │
      ▼
PostgreSQL Database
      │
      ▼
SQL Analysis
      │
      ▼
Power BI Dashboards
      │
      ▼
Business Insights
```

---

**📂 Project Structure**

```text
FoodConnect-ETL-Pipeline
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── notebook/
│   └── FoodWaste_ETL.ipynb
│
├── data/
│   ├── food_wastage_data.csv
│   └── food_waste_final.csv
│
├── sql/
│   └── foodconnect.sql
│
├── powerbi/
│   └── FoodConnect.pbix
│
└── dashboard_screenshots/
    ├── Dashboard1.png
    ├── Dashboard2.png
    └── Dashboard3.png
```

---

**📊 Dataset**

The dataset contains food waste records collected from various events and includes information such as:

- Food Type
- Number of Guests
- Event Type
- Quantity of Food Prepared
- Storage Conditions
- Purchase History
- Season
- Preparation Method
- Location
- Pricing Category
- Food Wastage Amount

---

**🧹 Data Cleaning & Feature Engineering**

The dataset was cleaned and transformed using Python.

Tasks performed:

- Removed duplicate records
- Handled missing values
- Standardized column names
- Created calculated business metrics
- Exported the cleaned dataset

Additional features created:

- Food Consumed
- Waste Percentage
- Price per Kg
- Revenue Loss
- Donation Possible
- Waste Category
- Event Size

---

**🗄 PostgreSQL**

The cleaned dataset was imported into PostgreSQL to enable SQL-based analysis and reporting.

---

**📝 SQL Analysis**

Business analysis was performed using PostgreSQL with queries covering:

- Aggregate Functions
- GROUP BY
- ORDER BY
- HAVING
- CASE Statements
- Subqueries
- Common Table Expressions (CTEs)
- Views
- Window Functions
- Ranking Functions

---

**📈 Power BI Dashboard**

The project includes interactive dashboards that provide insights into:

- Total Food Waste
- Revenue Loss
- Food Waste by Food Type
- Food Waste by Event Type
- Seasonal Trends
- Waste by Location
- Storage Condition Analysis
- Donation Analysis
- Executive Summary

---

**📷 Dashboard Preview**

**Dashboard 1 – Executive Overview**

<img width="797" height="383" alt="DASHBOARD 1" src="https://github.com/user-attachments/assets/7f3cd3ce-84d0-433f-81f1-42ee4839eb0f" />


---

**Dashboard 2 – Operational Analysis**

<img width="797" height="384" alt="DASHBOARD 2" src="https://github.com/user-attachments/assets/d18bf0f5-5e46-40e8-bec7-eefab15e6359" />


---

**Dashboard 3 – Executive Summary**

<img width="801" height="380" alt="DASHBOARD 3" src="https://github.com/user-attachments/assets/ad3be50f-359d-44ef-8cd8-5bc36dd67e00" />


---

**🔍 Key Insights**

- Identified the food categories contributing the highest waste.
- Measured revenue loss associated with food wastage.
- Compared waste across event types and seasons.
- Analyzed the impact of storage conditions on food waste.
- Evaluated donation opportunities for surplus food.

---

**💼 Business Recommendations**

- Improve demand forecasting before large events.
- Optimize food preparation based on expected attendance.
- Enhance storage practices for perishable food items.
- Donate surplus edible food whenever possible.
- Monitor high-cost food items to reduce financial losses.

---

**🚀 Future Improvements**

- Build a real-time analytics dashboard.
- Integrate live restaurant data.
- Predict food waste using Machine Learning.
- Automate ETL using Apache Airflow.

---

**👩‍💻 Author**

**Jayasree Chakraborty**

B.Tech Computer Science & Engineering

Passionate about Data Analytics, Business Intelligence, and AI-driven solutions.

---

⭐ **If you found this project useful, consider giving it a star!**
