# hotel-data-analysis

### Project Overview

This Power BI project aims to provide a comprehensive analysis of hotel performance for a business with establishments in various cities across India. The primary objective is to equip stakeholders with actionable insights for informed decision-making.

### Dataset Overview

The dataset, sourced from codebasics.io, comprises five key files:

#### 1. dim_date:
- Contains date-related information for May, June, and July.
- Includes columns such as date, month-year (mmm yy), week number, and day type (Weekend or Weekday).

#### 2. dim_hotels:
- Provides details about hotels, including property_id, property_name, category (Luxury or Business), and city.

#### 3. dim_rooms:
- Describes various room types with columns like room_id and room_class (Standard, Elite, Premium, Presidential).

#### 4. fact_aggregated_bookings:
- Presents aggregated information on hotel bookings.
- Includes property_id, check-in date, room_category, successful_bookings, and capacity.

#### 5. fact_bookings:
- Offers detailed insights into individual customer bookings.
- Features columns such as booking_id, property_id, booking_date, check_in_date, check_out_date, no_guests, room_category, booking_platform, ratings_given, booking_status, revenue_generated, and revenue_realized.

### Dashboard

#### Main Dashboard

<p align="center" width="100%"><img width="556" alt="hotel 1" src="https://github.com/saraimdad/hotel-data-analysis/assets/157117492/bb973ef8-a169-4624-b1a1-5a20938922da"></p>


<p align="center" width="100%"><img width="576" alt="Screenshot 2024-02-14 003943" src="https://github.com/saraimdad/hotel-data-analysis/assets/157117492/407f160a-7f8a-43a5-a6c8-cb38418c7c73"></p>

1. Key Performance Indicators (KPIs)
The main dashboard features essential KPIs, including total revenue, RevPAR, DSRN, occupancy percentage, ADR, and realization percentage. Additionally, it provides insights into week-on-week changes in RevPAR, occupancy percentage, ADR, and realization for trend analysis. Tooltips have been incorporated to provide additional information for a more detailed understanding of the KPIs.

2. Charts
Visualizations include a dynamic Bar and Line Chart illustrating ADR and realization by platform, a Donut Chart displaying the percentage revenue by category (Business or Luxury), a Line Chart depicting trends by week number for RevPAR, ADR, and occupancy percentage, and a comprehensive Table detailing property-specific metrics.

3. Filters
User-friendly filters enable customization based on city, room class, month, and week number, allowing stakeholders to focus on specific segments of interest.

#### Drill-Through Property Dashboard

<p align="center" width="100%"><img width="557" alt="hotel1" src="https://github.com/saraimdad/hotel-data-analysis/assets/157117492/728db1db-02ae-4749-b791-b776bc3a66e8"></p>

1. Property Details
Drilling down provides property-specific insights, including property name, city, capacity, revenue, and rating. Visualizations feature a Donut Chart illustrating bookings by category, a Line Chart displaying booking trends, and metrics like average rating by room class.

2. Filters
Further filters based on month and week number facilitate a detailed analysis of individual property performance.

### Measures Description / Purpose:

1. Total Revenue Realized:
Description: Sum of revenue realized from all bookings.
Purpose: Provides an overview of the total income generated from successful bookings.
2. Total Number of Bookings:
Description: Total count of bookings made.
Purpose: Offers insights into overall booking activity during the specified time period.
3. Total Capacity of Rooms:
Description: Sum of room capacities across all hotels.
Purpose: Indicates the total number of rooms available in all hotels.
4. Total Successful Bookings:
Description: Count of bookings marked as successful checkouts.
Purpose: Measures the total number of bookings resulting in successful stays.
5. Occupancy:
Description: Occupancy percentage based on successful bookings and total room capacity.
Purpose: Provides a percentage indicating how well hotels are utilizing their available rooms.
6. Average Ratings:
Description: Average rating given by customers.
Purpose: Indicates customer satisfaction based on their ratings.
7. Total Number of Days:
Description: Count of total days in the data set.
Purpose: Offers a timeframe reference for data analysis.
8. Cancelled Bookings Percentage:
Description: Percentage of bookings that were cancelled.
Purpose: Evaluates the impact of cancellations on total booking activity.
9. Checked Out Bookings Percentage:
Description: Percentage of bookings that were successfully checked out.
Purpose: Measures the success rate of bookings resulting in customers checking out.
10. No Show Bookings Percentage:
Description: Percentage of bookings where customers neither cancelled nor attended.
Purpose: Measures the rate of customers who did not fulfill their booking.
11. Booking Platform Contribution:
Description: Percentage contribution of each booking platform to total bookings.
Purpose: Analyzes the distribution of bookings across different platforms.
12. Room Class Contribution:
Description: Percentage contribution of each room class to total rooms booked.
Purpose: Provides insights into the popularity of different room classes.
13. ADR (Average Daily Rate):
Description: Average rate paid for rooms sold.
Purpose: Measures the average amount customers pay for rooms in a given time period.
14. Realization Percentage:
Description: Percentage of successful checkouts over total bookings.
Purpose: Measures the success rate of bookings leading to checkouts.
15. RevPAR (Revenue Per Available Room):
Description: Revenue generated per available room, whether occupied or not.
Purpose: Evaluates the revenue-generating performance of hotels in pricing their rooms.
16. DBRN (Daily Booked Room Nights):
Description: Average number of rooms booked per day.
Purpose: Provides insights into daily booking trends over a specified time period.
17. DSRN (Daily Sellable Room Nights):
Description: Average number of rooms ready to sell per day.
Purpose: Provides insights into the daily availability of sellable rooms.
18. DURN (Daily Utilized Room Nights):
Description: Average number of rooms successfully utilized by customers per day.
Purpose: Measures the daily success rate of rooms being utilized by customers.
19. Week Over Week Changes:
Description: Percentage change in various metrics (Revenue, Occupancy, ADR, RevPAR, Realization, DSRN) from the current week to the previous week.
Purpose: Highlights the weekly performance changes for better trend analysis and decision-making.

### Conclusion

This Power BI project offers a dynamic and insightful analysis of hotel performance, empowering stakeholders to make informed decisions based on a wide array of crucial metrics. The inclusion of comprehensive measures and their descriptions enhances the interpretability and usability of the presented data. Users can effortlessly navigate through the dashboards and gain valuable insights into the trends and performance of hotels in different cities.
