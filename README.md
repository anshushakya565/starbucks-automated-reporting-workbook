# Starbucks Customer Ordering Performance Dashboard

## Overview

This project presents an automated Excel reporting workbook designed to analyze Starbucks customer ordering patterns, sales performance, customer satisfaction, and operational metrics. The workbook leverages Power Query, Pivot Tables, Pivot Charts, Slicers, and Timeline controls to create a dynamic dashboard that updates automatically when new data is added.

---

## Business Objective

The goal of this project is to provide interactive and automated reporting capabilities to monitor:

- Revenue performance across regions
- Popular drink categories
- Customer ordering channels
- Customer satisfaction levels
- Rewards membership participation
- Peak ordering hours

The dashboard enables business users to explore performance trends and derive actionable insights through filters and time-based analysis.

---

## Dataset Information

The dataset contains customer ordering information with the following features:

- Customer Information
  - Customer ID
  - Gender
  - Age Group
  - Rewards Membership

- Order Information
  - Order ID
  - Order Date
  - Order Time
  - Day of Week
  - Order Channel

- Store Information
  - Store ID
  - Store Location Type
  - Region

- Order Metrics
  - Cart Size
  - Number of Customizations
  - Total Spend
  - Fulfillment Time

- Product Information
  - Drink Category
  - Food Item Availability

- Customer Experience
  - Order Ahead
  - Customer Satisfaction

---

## Project Workflow

### 1. Data Cleaning and Preparation

- Checked for missing values
- Checked for duplicate records
- Validated data types
- Imported data into Power Query
- Created derived columns for reporting

---

### 2. Automated Reporting Pipeline

```
Raw_Data
    ↓
Power Query
    ↓
Cleaned_Data
    ↓
Pivot Tables
    ↓
Dashboard
    ↓
Business Insights
```

The dashboard updates automatically through the **Refresh All** functionality.

---

### 3. Dashboard Features

#### KPI Cards

- Total Revenue
- Total Orders
- Average Order Value
- Average Satisfaction
- Rewards Member Percentage
- Average Fulfillment Time

#### Visualizations

- Revenue by Region
- Revenue by Drink Category
- Orders by Channel
- Average Satisfaction by Channel
- Peak Ordering Hours

#### Interactive Filters

- Region
- Order Channel
- Rewards Member
- Day of Week
- Order Date Timeline

---

## Key Insights

### Regional Performance

Revenue varies significantly across regions, highlighting opportunities for targeted business strategies.

### Drink Categories

Certain beverage categories contribute a larger share of total revenue.

### Ordering Channels

Customer ordering behavior differs across Mobile App, Drive-Thru, Kiosk, and In-Store channels.

### Customer Satisfaction

Customer satisfaction levels vary across ordering channels, providing insights into service quality.

### Peak Hours

Ordering activity peaks during specific hours of the day, enabling better operational planning.

### Rewards Program

Rewards members represent a significant portion of customers and influence spending patterns.

---

## Automation Process

1. Add new records to the `Raw_Data` sheet.
2. Save the workbook.
3. Go to:

```
Data → Refresh All
```

4. Power Query updates the cleaned dataset.
5. Pivot Tables refresh automatically.
6. Charts and dashboard visuals update instantly.

---

## Tools and Technologies

- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Slicers
- Timeline
- Data Cleaning
- Dashboard Design

---

## Skills Demonstrated

- Excel Automation
- Data Cleaning
- Power Query
- Pivot Table Analysis
- Interactive Dashboard Development
- Business Reporting
- KPI Design
- Data Visualization
- Analytical Thinking
- Storytelling with Data

---

## Files Included

```
Starbucks_Customer_Ordering_Performance_Dashboard.xlsx
README.md
```

---

## Future Enhancements

- Forecasting of sales trends
- Customer segmentation analysis
- Regional performance benchmarking
- Advanced KPI tracking
- Power BI version of the dashboard

---

## Author

**Anshu Shakya**

Aspiring Data Analyst

Skills:
- Excel
- Power BI
- SQL
- Python
- Pandas
- Power Query
- Data Visualization

---

### If you found this project useful, feel free to star the repository.
