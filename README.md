# PowerBI-practice-1

📊 Power BI Reimbursement Practice Dashboard

This repository contains a beginner-level Power BI practice dashboard created to understand data cleaning, transformation, basic DAX measures, and visual analysis using an Excel dataset.

🎯 Objective

Practice Power Query transformations

Understand currency normalization

Create basic DAX measures

Build simple, meaningful visuals in Power BI

🛠 Tools Used

Power BI Desktop

Excel (source dataset)

Power Query

DAX

🔄 Data Preparation (Power Query)

Imported Excel file into Power BI

Fixed punctuation errors in text fields

Standardized inconsistent employee and project names

Created a custom column to identify currency type:

Amount ≥ 1000 → INR

Amount < 1000 → USD

Else → EUR

Converted all amounts to INR using approximate exchange rates:

USD → 80

EUR → 90

📐 DAX Measures Created

Total Reimbursement Amount (INR)

Total Reimbursement for Project B using CALCULATE()

Count of Declined Reimbursement Requests

📊 Visualizations

Slicers for:

Project

Employee

Column Chart:

Employee-wise reimbursement amount

Pie Chart:

Project-wise reimbursement distribution

Card visuals for key metrics

📌 Key Learnings

How Power Query helps in cleaning and standardizing data

Importance of currency normalization before analysis

Difference between columns and measures

Using DAX for filtered calculations

Building interactive dashboards with slicers

⚠️ Notes

Exchange rates used are approximate, for learning purposes only

This dashboard is a practice exercise, not a production-level solution

📁 File Included

Reimbursement_Practice_Dashboard.pbix

🚀 Next Steps

Improve DAX efficiency

Handle dynamic exchange rates

Add more insights using additional visuals
