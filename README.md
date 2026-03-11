HR Presence Dashboard — Power BI Report

📋 Overview
HR_presence.pbix is a Power BI report designed to track and analyze employee attendance and work patterns across an organization. It provides HR teams and managers with a centralized view of presence rates, work-from-home (WFH) trends, and sick leave (SL) metrics — broken down by employee, date, and day of the week.

📊 Report Structure
Pages
PageDescriptionPresence OverviewSingle-page dashboard summarizing all key HR attendance KPIs

🔢 Key Metrics (Measures)
The report uses a dedicated Measure Tables table with the following calculated metrics:
MeasureDescriptionPresence %Percentage of days employees were physically present in the officeWFH %Percentage of days employees worked from homeSL %Percentage of days employees were on sick leave

📁 Data Model
Tables
TableKey FieldsFinal DataName (employee), Date, Day of week, Month, ValueMeasure TablesPresence %, WFH %, SL %

🖼️ Visuals on the Dashboard
Visual TypePurposeCards (×3)At-a-glance KPI display for overall Presence %, WFH %, and SL %Area Charts (×3)Trend lines over time for each metric (Presence %, WFH %, SL %) plotted against DateTable — Employee SummaryPer-employee breakdown of Presence %, WFH %, and SL % by NamePivot TableEmployee attendance matrix with dates as columnsTables — Day of Week (×3)Aggregated presence, WFH, and SL percentages broken down by day of weekSlicerFilter the entire report by MonthAction ButtonNavigation or reset interaction controlText BoxReport title / label element

🔍 How to Use

Open HR_presence.pbix in Power BI Desktop (version 2026.02 or later recommended).
Connect your data source — replace or refresh the Final Data table with your organization's attendance data.
Use the Month slicer on the dashboard to filter metrics for a specific time period.
Review KPI cards at the top for a quick snapshot of attendance health.
Scroll through area charts to spot trends over time.
Use the employee table to identify individuals with low presence or high sick leave.
Use the day-of-week tables to uncover attendance patterns (e.g., higher WFH on Fridays).


🗂️ File Details
PropertyValueFile NameHR_presence.pbixCreated FromPower BI CloudReport Version2026.02Pages1Data Tables2 (Final Data, Measure Tables)

⚙️ Requirements

Power BI Desktop — February 2026 release or newer
Access to the underlying attendance data source for refresh


📌 Notes

The measure table is named Meaasure tables (note the double 'a') — keep this consistent when editing DAX or building new measures.
The Value field in Final Data stores attendance status values used to calculate the three key percentages.
This report was created from Power BI Cloud and can be published back to the Power BI Service for shared access.
