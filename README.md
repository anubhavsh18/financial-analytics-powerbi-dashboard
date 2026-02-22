# financial-analytics-powerbi-dashboard
End-to-end Financial Analytics project using Power BI, Power Query (M), Advanced DAX and Power Automate to automate email file handling, clean and combine multiple datasets, build a data model and generate business insights such as KPIs, customer segmentation and LTV analysis.

## About the Project
This project started from a very practical problem.  
Every day multiple financial data files were received through email. Someone had to manually download all attachments, combine them into one file, clean the data and quickly prepare a dashboard. The process was repetitive, time-consuming and small errors were very common.

Instead of only building a dashboard, I tried to improve the whole workflow.

The goal of this project was to automate data collection, prepare clean data, and then build a reporting dashboard that could actually help in decision making.

---

## What I Implemented

### 1. Automation (Power Automate)
I created an automated flow that:
- Filters incoming Outlook emails
- Moves the attachments to a dedicated folder
- Automatically stores the files in OneDrive

This removed the need to manually download files every day.

---

### 2. Data Preparation (Power Query - M Language)
After automation, the next challenge was messy data.

Using Power Query I:
- Combined multiple daily files automatically
- Cleaned inconsistent values
- Handled missing data
- Standardized columns and formats
- Created new useful fields

The aim was to make the dataset reliable before doing any analysis.

---

### 3. Data Modeling
- Built proper table relationships
- Designed a structured data model
- Ensured measures calculate correctly across tables

This step helped improve performance and accuracy of calculations.

---

### 4. Analysis & Calculations (Advanced DAX)
I created several calculated measures including:

- Average Annual Income
- Average Monthly Balance
- Average Delay in Payment
- Credit Utilisation
- Age group segmentation
- Customer LTV (Lifetime Value)

LTV was calculated using multiple business parameters like income, credit score, delay in payments and investment amounts.

---

### 5. Dashboard & Insights
The dashboard provides insights such as:
- Customer age distribution
- Credit score behaviour across age groups
- Payment behaviour patterns
- Loan distribution
- Potential customer groups for targeted offers

The idea was not just to display numbers but to make the data understandable for business decisions.

---

## Tools Used
- Power BI
- Power Query (M Language)
- DAX
- Power Automate
- OneDrive
- Excel (data source)

---

## Key Learnings
This project taught me an important lesson:

Most of the effort in analytics goes into preparing and structuring the data, not creating charts.

I also understood how automation can reduce manual work and make reporting faster and more reliable.

---

## Future Improvements
- Connect live data source instead of static files
- Add scheduled refresh
- Publish dashboard to Power BI Service

---

## Author
Anubhav Sharma 
