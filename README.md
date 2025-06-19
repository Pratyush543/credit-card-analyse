# 📊 Credit Card Analysis Dashboard using Power BI

This repository contains a Power BI project developed for analyzing customer behavior and credit card performance using data from a fictional financial institution, **G7C Card Corp**. The goal of the project is to provide deep insights into revenue trends, customer segments, and card usage patterns through interactive dashboards.


## 🔍 Project Overview

This project demonstrates how to use Power BI in combination with PostgreSQL to clean, transform, and visualize real-world credit card and customer demographic data. The dashboard includes key performance indicators (KPIs), week-over-week comparisons, and segmentation analysis that can assist stakeholders in making data-driven decisions.


## 📁 Files Included

- `CreditCardDashboard.pbix` – The main Power BI report file
- `customer.csv` – Customer demographic and profile dataset
- `credit_card.csv` – Credit card usage and transaction dataset
- `README.md` – Project documentation


## 🧰 Technologies Used

- **Power BI Desktop**
- **PostgreSQL** for structured data storage
- **DAX** (Data Analysis Expressions) for custom metrics
- **Power Query** for data cleaning and transformation


## 🧪 Key Features

- Dynamic dashboards with real-time filtering
- Weekly and quarterly revenue and transaction trends
- Revenue segmentation by:
  - Age Group
  - Income Group
  - Job Role
  - Card Category
  - Education Level
- Delinquency and activation rate tracking
- Week-over-week growth comparisons
- Drill-through and slicer interactivity


## 🛠️ How to Use

1. Clone this repository or download the files.
2. Set up a **PostgreSQL** database and import the provided `.csv` files into tables (`cc_detail`, `cust_detail`).
3. Open the `.pbix` file in Power BI Desktop.
4. Update the data source connection if needed (to match your local PostgreSQL settings).
5. Click **Refresh** to pull in the latest data and explore the dashboard.


## 🔄 Future Scope

- Real-time data streaming from SQL
- Integration with machine learning models for predictive analytics
- Enhanced segmentation and behavior-based personalization
- Mobile-optimized dashboard layout
- Role-based access via Power BI Service


## 📜 License

This project is for **educational and portfolio purposes only**. The datasets used are fictional and do not represent any real individuals or institutions.


## 🙌 Acknowledgements

- Microsoft Power BI Documentation
- PostgreSQL Guides
- DAX Guide (https://dax.guide/)
- BI community forums and dashboard design blogs for layout inspiration

