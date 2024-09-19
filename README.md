Hospitality Revenue Insights Analysis

 Overview

This project provides a comprehensive analysis of revenue insights in the hospitality domain using Power BI. It involves analyzing booking and revenue data from multiple CSV files to generate actionable insights for hotel management.

 Project Structure

The project includes the following CSV files:

1. dim_date.csv - Contains date-related information.
   - date: The actual date.
   - mmm_yy: Date in the format "Month Year".
   - week_no: Unique week number for the date.
   - day_type: Indicates if the day is a Weekend or Weekday.

2. dim_hotels.csv - Contains information about hotels.
   - property_id: Unique ID for each hotel.
   - property_name: Name of the hotel.
   - category: Class of the hotel (Luxury or Business).
   - city: Location of the hotel.

3. dim_rooms.csv - Contains details about room types.
   - room_id: Type of room (e.g., RT1, RT2).
   - room_class: Class of the room (e.g., Standard, Elite).

4. fact_aggregated_bookings.csv - Contains aggregated booking data.
   - property_id: Unique ID for each hotel.
   - check_in_date: Customer check-in dates.
   - room_category: Type of room.
   - successful_bookings: Count of successful bookings.
   - capacity: Maximum number of rooms available.

5. fact_bookings.csv - Contains detailed booking data.
   - booking_id: Unique booking ID.
   - property_id: Unique ID for each hotel.
   - booking_date: Date of booking.
   - check_in_date: Check-in date.
   - check_out_date: Check-out date.
   - no_guests: Number of guests.
   - room_category: Type of room.
   - booking_platform: Booking method.
   - ratings_given: Customer ratings.
   - booking_status: Status of the booking (Cancelled, Checked Out, No Show).
   - revenue_generated: Revenue generated.
   - revenue_realized: Final revenue realized based on booking status.

 Key Features

- Key Performance Measures: Developed metrics to track booking trends, room occupancy, and revenue.
- Filters and Slicers: Implemented dynamic filters for detailed analysis based on various criteria such as hotel category and booking status.
- Visualizations: Created insightful graphs and charts to visualize trends in bookings, revenue, and customer satisfaction.

 Getting Started

1. Clone the repository:
   bash
   git clone https://github.com/your-username/hospitality-revenue-insights.git
   
2. Open the Power BI file (Hospitality_Insights.pbix) to explore the interactive dashboards and reports.

 How to Contribute

Feel free to open issues or submit pull requests if you have suggestions or improvements.
