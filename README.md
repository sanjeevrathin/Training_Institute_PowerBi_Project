# 📊 Student Training Institute Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive Power BI dashboard developed for analyzing the operations of a student training institute. It provides valuable insights into student enrollment, course management, fee collection, payment tracking, certificates, and overall revenue.

The project demonstrates an end-to-end Business Intelligence workflow, including data extraction, data modeling, DAX calculations, and interactive dashboard creation.

---

## 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- CSV Files
- Data Modeling

---

## 📂 Project Structure

```
Student-Training-Institute-PowerBI
│
├── 01_Data_Extraction
│   ├── students.csv
│   ├── courses.csv
│   └── payments.csv
│
├── 02_Data_Modeling
│   └── Data_Model.png
│
├── 03_Data_Visualization
│   └── Sanjeev_Training_Institute.pbix
│
├── Screenshots
│   └── Dashboard.png
│
└── README.md
```

---

## 📥 Data Extraction

The dashboard is built using three CSV datasets.

| Dataset | Description |
|----------|-------------|
| students.csv | Student details |
| courses.csv | Course information and fees |
| payments.csv | Student payment records |

---

## 🔗 Data Modeling

The data model is designed using relationships between multiple tables to enable efficient reporting and analysis.

### Relationships

- Students (1) → Payments (*)
- Courses (1) → Payments (*)
- Students (1) → Certificates (1)

The model follows a clean relational structure to improve dashboard performance and simplify analysis.

### Data Model Preview

![Data Model](02_Data_Modeling/Data_Model.png)

---

## 📊 Dashboard Features

The dashboard includes:

- Total Students
- Total Revenue
- Total Payments
- Course-wise Revenue Analysis
- Student Payment Details
- Certificate Status
- Interactive Filters & Slicers
- Dynamic KPI Cards
- DAX-based Business Metrics

---

## 📌 Key Performance Indicators (KPIs)

- Total Students
- Total Revenue
- Total Payments
- Total Certificates Issued
- Average Course Fee

---

## 📈 DAX Measures Used

Some of the measures created in this project include:

- Total Income
- Total Tax
- Paid Amount
- Student Count
- Certificate Count

---

## 📷 Dashboard Preview

> Add your dashboard screenshot to the **Screenshots** folder.

![Dashboard](Screenshots/Dashboard.png)

---

## 🚀 Skills Demonstrated

- Data Extraction
- Data Cleaning
- Power Query (ETL)
- Data Modeling
- Relationship Management
- DAX Calculations
- KPI Development
- Interactive Dashboard Design
- Business Intelligence Reporting

---

## 💡 Business Insights

This dashboard helps stakeholders to:

- Monitor student enrollments
- Track payment collections
- Analyze course performance
- Measure institute revenue
- Monitor certificate completion
- Make data-driven decisions

---

## 👨‍💻 Author

**Sanjeev**

**Aspiring Data Analyst | Power BI Developer**

### Connect with Me

- LinkedIn: *(https://www.linkedin.com/in/sanjeev-rathin/)*
- Email: *(sanjeevrathinr@gmail.com)*

---

⭐ If you found this project useful, feel free to star this repository.
