# Multi-Service-Booking-Data-Analysis-Project

***🔍 Project Overview:***
This project analyzes booking data, a multi-service business that offers:

✔️ Class Bookings (e.g., Art, Dance, Gymnastics)

✔️ Facility Rentals (e.g., Play Area, Party Room)

✔️ Subscriptions

✔️ Birthday Party Reservations

The dataset reflects real-world booking data, which contains inconsistencies, missing values, and duplicate records. The goal is to clean, analyze, and visualize the data to derive valuable business insights.



***🎯 Objectives:***

✔️ Data Cleaning & Preprocessing – Handling missing values, inconsistencies, and duplicates

✔️ Exploratory Data Analysis (EDA) – Identifying trends in bookings, revenue, and cancellations

✔️ Business Insights & Recommendations – Providing insights for improving operations

✔️ Interactive Dashboard (Excel) – Creating a user-friendly visualization of key findings

✔️ Final Report & Documentation – Summarizing methodology, observations, and insights



***🗂 Dataset Information:***

Booking ID:	Unique identifier for each booking

Service Name:	Name of the booked service (e.g., Gymnastics, Play Area)

Service Type:	Category of the service (e.g., Class, Facility, Subscription)

Status:	Booking status (Confirmed, Canceled, Pending)

Booking Date:	Date when the booking was made

Time Slot:	Time of the booking (if applicable)

Duration (mins):	Duration of the booking

Instructor:	Name of the instructor (if applicable)

Facility:	Facility name (if applicable)

Price:	Amount paid for the booking

Customer Email:	Contact details of the customer

Customer Phone:	Contact details of the customer

Month Name: Name of the Month

Day Name: Name of the Day



***📌 Data Cleaning Steps:***

1.Handled Missing Values:

Filled missing Instructor values with "Unknown"

Replaced missing Time Slot & Duration with "Not Provided"

Filled missing Facility & Theme with "Not Applicable"

Kept missing Customer Email & Phone blank to flag incomplete records

2.Removed Duplicate Entries:

Checked for duplicates based on Booking ID and removed identical rows

3.Standardized Data Formats:

Extracted Month Name & Day Name : Added new columns for Month Name (e.g., January, February, etc.) and Day Name (e.g., Monday, Tuesday, etc.) to analyze booking trends by time



***📊 Exploratory Data Analysis (EDA) & Insights:***

📌 Most Popular Services: Play Area is the most booked service (36% of total bookings).

📌 Booking Trends Over Time: Bookings are highest during weekends and peak between 12 PM – 2 PM.

📌 Revenue Trends: Birthday Party services contribute the most revenue, despite fewer bookings.

📌 Cancellation Rate: Facility rentals have the highest cancellation rate, indicating possible scheduling issues.

📌 Customer Insights: Many customer records lack email/phone details, making customer follow-ups difficult.



***📈 Interactive Dashboard (Excel):***

📌 Key Performance Indicators (KPIs) Used:

✔️ Total Bookings – Number of bookings made

✔️ Total Revenue – Total earnings from bookings

✔️ Most Popular Service – The service with the highest number of bookings

✔️ Successful Booking Rate – Percentage of bookings that were Successful




***🛠 Filters Used in the Dashboard:***

🎯 Service Type – Filter bookings by Class, Facility, Subscription, or Party

🎯 Status – Filter bookings based on Confirmed, Pending, or Canceled

🎯 Month Name – Filter bookings for specific months

🎯 Facility – Filter bookings by Play Area, Party Room, or Not Applicable




***📊 Visualizations in the Dashboard:***

📌 Total Orders & Revenue Metrics – High-level business performance overview

📌 Booking Status by Service Type – Bar chart showing confirmed, pending, and canceled bookings

📌 Bookings & Revenue by Day – Line and bar chart comparing daily trends

📌 Booking Trend Over Time – Line chart tracking bookings per time slot

📌 Most Popular Service – Pie chart showing the percentage distribution of services booked

📌 Successful Booking Rate by Service Type – Stacked bar chart highlighting Successful Bookings




***🛠 Technologies Used:***

Python (pandas, numpy, matplotlib, seaborn) → Data Cleaning & EDA

Excel (PivotTables, Power Pivot, Charts, Slicers) → Dashboard

GitHub → Project Documentation




***📌 Business Impact:***

✅ Better Resource Allocation – Identifying peak booking times allows better staff & facility management.

✅ Revenue Optimization – Understanding the most profitable services helps in marketing efforts.

✅ Reducing Cancellations – Analyzing cancellation rates helps implement policies to improve customer retention.

✅ Improving Customer Data – Flagging missing customer details ensures better customer communication.



![Screenshot (1606)](https://github.com/user-attachments/assets/c98137be-d3b0-40ed-8b52-d4e0ae264b88)



