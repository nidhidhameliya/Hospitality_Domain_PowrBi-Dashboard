# Hospitality_Domain_PowrBi-Dashboard

This project is focused on analyzing and visualizing hotel booking data to gain insights into booking patterns, customer preferences, and revenue trends in the hospitality industry. Utilizing Power BI, the project leverages multiple datasets to create an interactive and informative dashboard for better decision-making within the hotel management domain.

## Files Used
Below are the primary datasets used in this project:

- **dim_hotels**: Contains information about different hotels, including hotel names, locations, and other hotel-specific attributes.
- **dim_date**: Provides a date dimension table with detailed information about dates, months, quarters, and years to support time-based analysis.
- **dim_rooms**: Includes details on various room types available in the hotels, such as room size, amenities, and room categories.
- **fact_aggregated_bookings**: An aggregated data file summarizing booking counts, revenue, and other metrics for analysis.
- **fact_bookings**: Contains individual booking records with detailed data on each booking, including dates, hotel details, room types, and customer information.

## Key Metrics
The following metrics were analyzed in this project:
- **Total Bookings**: Number of hotel bookings over a selected period.
- **Occupancy Rate**: Ratio of booked rooms to total available rooms.
- **Revenue**: Total revenue generated from bookings.
- **Booking Trends**: Insights into peak booking periods, seasonality, and trends over time.
- **Customer Preferences**: Analysis of preferred room types and popular booking periods.

## Dashboard Features
The Power BI dashboard created in this project includes:
1. **Interactive Visuals**: Allows filtering by date, hotel, and room type to get a detailed view of booking metrics.
2. **Time-Based Analysis**: Visualizations for monthly and quarterly trends, helping identify peak periods.
3. **Revenue Insights**: Breakdown of revenue by hotel, room type, and booking dates for financial analysis.
4. **Customer Patterns**: Insights into customer preferences, room choices, and booking behaviors.

### **Screenshots**
![Screenshot 2024-11-18 141309](https://github.com/user-attachments/assets/8fa04464-f0d2-4aa2-b54e-62b68f72ef86)

![Screenshot 2024-11-18 141343](https://github.com/user-attachments/assets/ba474f6b-d81a-4a0d-bd3b-d41275312561)


### **Relationships in Data Model**
-  **relationships between tables** in the data model should be added here. Highlight the connections between `dim_hotels`, `dim_date`, `dim_rooms`, `fact_aggregated_bookings`, and `fact_bookings`.
-  ![Screenshot 2024-11-18 141758](https://github.com/user-attachments/assets/c507e2f2-85ed-4883-9368-e2189ee03d44)

## Tools Used
- **Power BI**: For creating interactive dashboards and visualizations.
- **Excel**: For data cleaning and pre-processing before importing data into Power BI.
- **DAX** (Data Analysis Expressions): For creating calculated fields and custom metrics.
- **Power Query**: For data transformation and manipulation within Power BI.

## How to Use
1. Download the datasets: `dim_hotels.xlsx`, `dim_date.xlsx`, `dim_rooms.xlsx`, `fact_aggregated_bookings.xlsx`, and `fact_bookings.xlsx`.
2. Open the Power BI file (`Hospitality_Domain_PowerBI_Dashboard.pbix`) using Power BI Desktop.
3. Interact with the visuals by using the slicers and filters to explore different data insights.

## Insights & Recommendations
- Peak booking periods were identified during specific months, suggesting promotional activities during off-peak times.
- High revenue-generating hotels and room types were highlighted, aiding strategic focus on preferred offerings.
- Recommendations include adjusting room prices during high-demand periods and exploring underperforming segments for improvement.

## Conclusion
This project demonstrates the effective use of Power BI for data visualization and analytics in the hospitality domain. The insights generated provide valuable information for enhancing revenue strategies, understanding customer preferences, and improving booking experiences.
