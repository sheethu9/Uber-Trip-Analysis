Uber Trip Analysis Dashboard - Power BI Project

📄 Project Overview

This Power BI project analyzes Uber trip data to extract insights related to booking trends, revenue, trip efficiency, and operational metrics. It consists of three dashboards: Overview Analysis, Time Analysis, and Details Tab, providing stakeholders with actionable intelligence to drive decision-making.

📈 Dashboard 1: Overview Analysis

🔢 KPI Metrics:

Total Bookings - Total trips booked in the selected time period.

Total Booking Value - Total revenue generated from bookings.

Average Booking Value - Average fare per trip.

Total Trip Distance - Sum of all trip distances.

Average Trip Distance - Average distance traveled per trip.

Average Trip Time - Mean duration of trips.

✅ Expected Outcomes:

Detect patterns in ride bookings and revenue generation.

Analyze trip efficiency by distance and duration.

Compare trip and revenue metrics across different periods.

Optimize pricing and improve service strategies.

📊 Charts & Features:

Measure Selector (Disconnected Table):

Total Bookings

Total Booking Value

Total Trip Distance

Breakdowns by:

Payment Type (Card, Cash, Wallet, etc.)

Trip Type (Day/Night)

Enhancements:

Dynamic Title (based on selected measure)

Slicers for Date, City, and other filters

Tooltips for additional info (avg values, etc.)

🛳 Vehicle Type Analysis:

Grid/Matrix view showing KPIs per vehicle type.

Conditional formatting for high/low value indicators.

Sort and filter capabilities for interactive insights.

🌍 Location Analysis:

Most Frequent Pickup Point

Most Frequent Drop-off Point (using USERELATIONSHIP)

Farthest Trip (based on maximum trip distance)

Top 5 Locations by Total Bookings

Most Preferred Vehicle by Location Pickup

✨ Additional Enhancements:

Bookmark: "Data Details"

Clear Slicer Button

Export Raw Data Button (via Power Automate or native export)

🗓 Dashboard 2: Time Analysis

Analyzes ride trends across different time periods for operational efficiency.

🌐 Global Dynamic Measure (affects all visuals):

Total Bookings

Total Booking Value

Total Trip Distance

📊 Visualizations:

Pickup Time (10-Min Intervals) - Area Chart

Day Name - Line Chart

Hour and Day - Heatmap (Matrix):

Rows: Hours (0–23)

Columns: Days (Mon–Sun)

Values: Dynamic Measure

🔍 Dashboard 3: Details Tab

Detailed view with support for drill-through analysis.

🔄 Drill-Through Features:

Right-click visuals to navigate to detailed data

Display trips by selected point (day/hour/location/etc.)

🔹 Grid/Table Visual:

Includes key trip fields (Trip ID, time, distance, fare, etc.)

🗂 Bookmark: Full Data View

Toggle between filtered drill-through and complete dataset.

🔗 Data Model Summary

Fact Table: Trip Details

Dimension Tables:

Location Table (for Pickup/Dropoff locations)

Calendar Table (for date-based slicing)

Vehicle Table, Payment Table, etc.

💡 Tools & Techniques

Power BI Desktop & Service

DAX for dynamic measures, filters, titles

USERELATIONSHIP for inactive relationships

Bookmarks, Tooltips, Slicers

🔧 How to Use This Repo

Clone the repo

Import the .pbix file into Power BI Desktop

Refresh data and configure slicers/bookmarks

✉ Contact & Contributions

If you have suggestions or would like to contribute to this project, feel free to raise an issue or submit a pull request!

