# PSL Cricket Analytics Dashboard

## Project Overview
This project analyzes Pakistan Super League (PSL) cricket data from 2016–2023 using Power BI.

The dashboard implements:
- Descriptive Analytics
- Predictive Analytics
- Prescriptive Analytics

The goal is to transform raw cricket statistics into actionable insights for team management, player evaluation, and strategic decision-making.

---

## Dataset Information

The project uses:
- Batting dataset
- Bowling dataset
- Match dataset
- Team reference table

Coverage:
- 2016–2023 PSL seasons
- 340+ players
- 242 matches

---

## Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning
- Sports Analytics

---

## Data Cleaning & Transformation

Performed using Power Query:
- Removed redundant columns
- Standardized column names
- Fixed date conversion issues
- Handled null values
- Split span years
- Extracted bowling metrics
- Created match identifiers

---

## Data Model

Star schema implemented:
- Players Table
- Matches Table
- Teams Dimension Table

---

## DAX Measures Created

### Core Measures
- Batting Average
- Avg Strike Rate
- Avg Economy
- Total Fours
- Total Sixes
- Match Count

### Advanced Measures
- Win Rate %
- Batting Consistency
- SR Gap to Target
- Economy Gap to Target

---

## Analytics Performed

### Descriptive Analytics
- Team performance analysis
- Strike rate distribution
- Wicket analysis
- Historical trends

### Predictive Analytics
- Performance forecasting
- Trend projections
- Team strength estimation

### Prescriptive Analytics
- Team selection optimization
- Benchmark analysis
- Strategic recommendations

---

## Key Insights

- Economy rate strongly impacts close match outcomes
- Chasing teams have slightly higher win percentages
- Versatile players improve team consistency
- Benchmark-based analysis identified high-impact players

---

## Dashboard Screenshots

### Descriptive Analytics
![Descriptive](Screenshots/descriptive.png)

### Predictive Analytics
![Predictive](Screenshots/predictive.png)

### Prescriptive Analytics
![Prescriptive](Screenshots/prescriptive.png)

---

## Conclusion

This dashboard transforms PSL cricket data into a complete analytics and decision-support system using Power BI.
