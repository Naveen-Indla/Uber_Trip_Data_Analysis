# Uber_Trip_Data_Analysis
## Uber Trip Analysis using Power BI
This project analyzes Uber trip data using Power BI to extract actionable insights. The goal is to understand booking trends, revenue generation, and trip efficiency, enabling stakeholders to make data-driven decisions.

## Dashboards Overview
The analysis is presented across four interactive dashboards:
## 1. Overview Analysis Dashboard 
This dashboard provides a high-level summary of Uber's performance.
Objective: To analyze key performance indicators, vehicle performance, daily booking trends, and location-based patterns.

### Key Visualizations & Analyses:
KPIs: Tracks core metrics such as Total Bookings, Total and Average Booking Value, and Total and Average Trip Distance.
Vehicle Type Analysis: A grid view analyzes KPIs across different vehicle types.
Bookings by Day: Identifies peak booking days and daily trip volume fluctuations.
Location Analysis: Determines most frequent pickup and drop-off points, the farthest trip, top 5 booking locations, and preferred vehicles by location.
Dynamic Charts: Visuals can be dynamically updated by Payment Type and Trip Type (Day/Night).

## 2. Time Analysis Dashboard 

This dashboard focuses on understanding trip patterns based on different time intervals to optimize operations, pricing, and driver availability.

### Key Visualizations & Analyses:
Area Chart: Displays trip bookings grouped into 10-minute intervals to identify peak demand periods throughout the day.
Line Chart: Shows booking trends from Monday to Sunday, analyzing weekday versus weekend demand.
Heatmap: A matrix grid that highlights peak booking hours across different days of the week.

## 3. Sales Analysis Dashboard 
This dashboard offers an in-depth look at sales and revenue.
Objective: To provide insights into sales performance and total revenue for each month.

### Key Visualizations & Analyses:
KPIs: Displays Fare Amount, Surge Pricing, and Total Fare by Day.
Sales Breakdowns: Shows total sales by city, bookings by time of day (Day/Night), and total bookings and sales by pickup time.
Drill-Through: This functionality is enabled to allow users to access detailed records from other dashboards.

## 4. Details Tab 
This dashboard provides a granular view of the data, allowing users to explore individual trip records.
Features:
Grid Table: Displays essential trip details in a tabular format.
Drill-Through: Allows users to right-click a data point on another visual and navigate to this grid to see the detailed records related to that selection.

## Bookmark: A "View Full Data" bookmark lets users toggle between the filtered drill-through data and the complete dataset.

Key Features & Functionality
The Power BI report is enhanced with several interactive features for a user-friendly experience:


 ## " Measure Selector: A global filter that dynamically updates all visuals based on a user's selection of metrics like Total Bookings, Total Booking Value, or Total Trip Distance."

Dynamic Titles: Chart titles automatically update based on the selected measure.
Slicers & Filters: Interactive filters for Date and City are available for deeper analysis.
Bookmarks: Used to show pop-up data details and to toggle between filtered and full data views.
Clear Slicer Button: A single-click button to reset all filters and selections on the dashboard.
Download Raw Data: A button is included to allow users to export the raw data for external analysis.
Tooltips: Hovering over visuals reveals additional details like Average Booking Value or Trip Distance.

### Key Performance Indicators (KPIs) Tracked
Total Bookings: The total number of trips booked over a given period.
Total Booking Value: The total revenue generated from all bookings.
Average Booking Value: The average revenue per booking.
Total Trip Distance: The total distance covered by all trips.
Average Trip Distance: The average distance customers travel per trip.
Average Trip Time: The average duration of a trip

## Files in this Repository
Uber Trip Analysis using powerbi.pbix: The Power BI source file containing the data model, dashboards, and all analyses.
UBER TRIP ANALYSIS DOCUMENTATION1.pdf: The project documentation outlining the business requirements, dashboard layouts, and implementation details.







