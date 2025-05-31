# Namma Yatri

End-to-end data analysis and visualization of ride-sharing data using MySQL and Power BI, focusing on trip metrics, user conversions, and driver performance for the Namma Yatri platform.

---

## 🧰 Tools Used

- **MySQL**: Database creation, data insertion, and SQL-based data analysis
- **Power BI**: Interactive dashboard creation and DAX-based metric calculations
- **Excel**: Data source for Power BI (exported from MySQL)

---

## 📂 Folder Structure

namma-yatri/
│
├── mysql/
│   ├── create_and_insert_tables.docx       # Your MySQL table creation and data insert scripts
│   ├── data_exploration_queries.docx       # Your MySQL queries for data analysis
│
├── powerbi/
│   ├── trips_dashboard.pbix                 # Your Power BI dashboard file
│   ├── dashboard_screenshot.png             # Optional but recommended — screenshot of dashboard
│
├── data/
│   └── namma_yatri_data.xlsx                # Excel data source file for Power BI
│
├── .gitignore                               # To ignore temp/system files
└── README.md                                # Main project overview and explanation


---

## 📊 Power BI Dashboard Overview

The dashboard includes:

- Completed Trips
- Total Searches, Estimates, and Quotes
- Driver Earnings
- Conversion Rates
- Visuals by Duration: Trips, Fare, and Distance
- Top Assemblies by Trip ID
- Interactive Dropdown Filters

> 📸 A screenshot is available in `powerbi/dashboard_screenshot.png`.

---

## 🗂️ Data Source

The file `data/namma_yatri_data.xlsx` is used in Power BI and contains tables exported or simulated from MySQL:
- `trips`
- `trip details`
- `duration`
- `loc`
- `payment`

---

## 🧮 SQL Analysis Highlights

Key metrics were explored using SQL, including:

- Total Trips, Drivers, and Earnings
- Cancellations and OTP Completion
- Most Popular Payment Methods and Routes
- Driver-Customer Pair Frequency
- Area- and Duration-wise Performance Breakdown

All queries are available in:
- `mysql/create_and_insert_tables.docx`
- `mysql/data_exploration_queries.docx`

---

## ✅ How to Use

1. Review the SQL scripts in `/mysql` to understand the data structure and analysis.
2. Open `namma_yatri_data.xlsx` from `/data` to see the dataset.
3. Load `trips_dashboard.pbix` in Power BI Desktop to explore the visuals.

---

## 📌 Notes

- Data was inserted manually via MySQL and exported to Excel for Power BI.
- All logic, joins, and KPIs are implemented using SQL and DAX.

---



