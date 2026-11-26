# powerbi-complaints-resolution-dashboard
Power BI dashboard analyzing 1200 bank complaints - Resolution rate, ART, CSAT by type, channet &amp; month 
# Complaints Resolution Performance Dashboard - Power BI

## What is this project?
This dashboard analyzes 1200 customer complaints for a bank.
It shows which complaint type is highest, how fast complaints are resolved, and customer satisfaction.

## Dashboard Preview
![Dashboard](Screenshots/Dashboard.png)

## Key Insights
- **Total Complaints:** 1200
- **Resolution Rate:** 65.25%
- **Avg Resolution Time:** 27.70 Hours
- **Avg Customer Rating:** 3.22 / 5

### Top Complaint Types
1. Fraud Investigation - 165 complaints
2. Card Problem - 161 complaints
3. Service Delay - 152 complaints

### Best vs Worst Performance
- **Best:** Transaction Issue - Only 6.95 hours to resolve, Rating 4.45
- **Worst:** Fraud Investigation - Takes 60.86 hours, Rating only 2.13

### Resolution Status
- Resolved - 65.25%
- In Progress - 14.67%
- Pending - 20.08%

### Rating By Channel
- Call Center - 3.5 (Highest)
- Mobile App - 3.3
- Branch - 3.1
- Email - 3.1
- Website - 3.1

## Files in this Project
- Complaints-Dashboard.pbit - Main Power BI file
- Data/Complaints-Data.xlsx - Data used
- Screenshots/Dashboard-1.png - Dashboard screenshot

## How to Open This Project?
1. Download this repository
2. Double click on `Complaints-Dashboard.pbit`
3. It will open in Power BI Desktop
4. When it asks for data, select `Data/Complaints-Data.xlsx`

## Dashboard Pages / Visuals Used
1. Complaint Type Count - Bar Chart
2. Resolution Status - Donut Chart
3. Average Rating By Channel - Bar Chart
4. Monthly Complaint Trend - Line Chart
5. Complaint Type Performance Table - ART vs CSAT

## Filters Available
- Complaint Type - Account Access, ATM Issue, Card Problem, etc.
- Channel - Branch, Call Center, Email, Mobile App, Website
- Resolution Status - Resolved, Pending, In Progress

## DAX Measures Used
- Total Complaints = COUNTROWS(Complaints)
- Resolution % = Resolved / Total Complaints
- Avg Resolution Hours = AVERAGE(Resolution Hours)
- Avg Rating = AVERAGE(Rating)
- CSAT % and SLA Under 24h %

## Tools Used
- Power BI Desktop
- Power Query for Data Cleaning
- DAX
- Excel

## What I Learned
- How to make KPI Cards
- How to use Slicers for filtering
- How to compare ART vs CSAT in one table
- How to show trend over 12 months

## Author
ASWATHI T V
