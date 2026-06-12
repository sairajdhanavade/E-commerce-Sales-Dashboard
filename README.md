# E-commerce Sales Dashboard (Power BI & Excel)

An interactive, end-to-end E-commerce Sales Dashboard built to track business performance, analyze categorical trends, and monitor Month-to-Date (MTD) KPIs against organizational goals.

Imgae&video/Screenshot 2026-06-12 185241.png *(Replace with your actual image path or URL)*

## 📌 Project Overview
This project transforms raw transactional e-commerce data into actionable business insights. By executing data cleaning steps in Excel and building dynamic data models in Power BI, this dashboard empowers stakeholders to identify top-performing product categories, track regional sales, and monitor profitability trends over time.

## 🛠️ Tech Stack & Tools
* **Excel**: Data cleaning, handling missing values, structural preprocessing.
* **Power BI Desktop**: Data modeling, DAX engineering, dashboard design.
* **Power Query**: ETL processes (Extract, Transform, Load).

## 📈 Key Features & Insights
* **Core KPI Metrics**: Real-time tracking of Total Amount (\$438K), Total Profit (\$37K), Total Quantity (5,615 units), and Total Orders (500).
* **Category Breakdown**: Granular view of orders and revenue across **Clothing**, **Electronics**, and **Furniture**. Clothing drives the highest transaction volume (949 orders), while Electronics leads in total revenue (\$166K).
* **Geographic Distribution**: Top 5 states analyzed by Order ID, highlighted by an interactive map visual and a breakdown showing Madhya Pradesh (31.42%) and Maharashtra (31.76%) as primary revenue drivers.
* **Profitability Timeline**: A line chart tracking *Profit by Month* that isolates seasonal spikes (January peak at 9.6K) and critical dips (July loss of -2.1K).
* **Advanced MTD Performance**: An integrated Month-to-Date (MTD) KPI tracker evaluating current sales (37,579) directly against target benchmarks (Goal: 48,469).

## 🧹 Data Cleaning Process (Excel)
Before visualization, the dataset underwent rigorous preprocessing steps to guarantee data integrity:
1. Removed duplicate transactions and irrelevant empty columns.
2. Standardized text formatting across columns (Categories, States, and Cities).
3. Validated data types to ensure numerical values (Amounts, Quantities) correctly register for arithmetic metrics.
4. Handled missing entries using conditional logic and mean imputation where appropriate.

## 📂 Repository Structure
```text
├── data/
│   ├── Detail.csv     
│   └── order(1).csv
├── dashboard/
│   └── E-commerce Sales Dashboard.pbix     # Power BI project file
├── images&video/
│   └── dashboard_screenshot & MP4    # Screenshot for documentation
└── README.md                        # Project documentation
```

## 🚀 How to Run the Project
1. Clone this repository to your local machine.
2. Download and install [Power BI Desktop](https://microsoft.com).
3. Open the file located in `dashboard/ecommerce_dashboard.pbix`.
4. If prompted to refresh data sources, point the directory connection to the file inside `data/cleaned_ecommerce_data.xlsx`.
