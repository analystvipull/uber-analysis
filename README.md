# Uber Ride Analytics Dashboard
## Recommended Structure and Order
### 1.	Project Title / Headline
A dynamic and interactive Power BI dashboard designed to analyze Uber ride booking performance, revenue generation, vehicle utilization, cancellation trends, and customer-driver ratings. The dashboard provides actionable insights into ride operations, helping stakeholders optimize business performance and customer experience.


### 2.	Short Description / Purpose
The Uber Ride Analytics Dashboard is a comprehensive Power BI solution built to monitor and evaluate ride-booking operations across multiple business dimensions. It enables users to analyze booking trends, revenue performance, vehicle-wise demand, cancellation behavior, and customer satisfaction metrics through interactive visualizations and KPI tracking.


### 3.	Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Primary platform used for creating interactive reports and visualizations.
📂 Power Query – Used for data extraction, cleaning, transformation, and preparation.
🧠 DAX (Data Analysis Expressions) – Created calculated measures, KPIs, aggregations, and dynamic insights.
🔗 Data Modeling – Established relationships between ride booking, customer, payment, and rating datasets to enable efficient filtering and analysis.
📈 Data Visualization – Utilized KPI cards, line charts, pie charts, bar charts, tables, and slicers for interactive reporting.
📁 File Formats – .pbix for development and .png screenshots for project documentation and GitHub presentation.


### 4.	Data Source
Source: Kaggle

The dataset contains detailed ride-booking records, including:

Booking IDs and ride statuses
Vehicle categories (Auto, Bike, eBike, Go Mini, Go Sedan, Premier Sedan, Uber XL)
Ride distances and trip volumes
Booking values and revenue information
Payment methods
Customer and driver ratings
Cancellation reasons from both customers and drivers
Booking timestamps and ride completion records

The dataset is structured to support operational, financial, and customer experience analysis.


### 5.	Features / Highlights
Business Problem - Ride-hailing platforms generate massive amounts of operational data daily. However, understanding booking performance, cancellation behavior, revenue generation, vehicle demand, and customer satisfaction can be challenging without a centralized analytical solution.

Key business questions include:

What is the overall booking success rate?
Which vehicle categories generate the highest revenue?
How do ride volumes fluctuate over time?
What are the major causes of ride cancellations?
Which payment methods are most frequently used?
How satisfied are customers and drivers across vehicle categories?


• Goal of the Dashboard

To provide an interactive analytical platform that:
Monitors ride-booking performance in real time.
Tracks revenue generation across vehicle categories and payment methods.
Identifies operational bottlenecks through cancellation analysis.
Evaluates customer and driver satisfaction levels.
Supports strategic decisions for improving service quality and operational efficiency.


• Walkthrough of Key Visuals

#### 📌 Overview Dashboard (Demographics)

Key KPIs

Total Bookings: 148.77K

Completed Bookings: 93K

Driver Cancelled Bookings: 27K

Customer Cancelled Bookings: 10.5K

No Driver Found Cases: 10.5K

Incomplete Rides: 9K

Booking Status Breakdown (Pie Chart) :
Displays the distribution of ride outcomes, helping stakeholders understand completion and cancellation proportions.

Ride Volume Over Time (Line Chart) :
Tracks monthly booking trends and highlights demand fluctuations throughout the year.

Date Slicer :
Allows users to dynamically filter all dashboard visuals by selected date ranges.


#### 	Screenshots / Demos
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/analystvipull/uber-analysis/blob/main/Demographics%20Dashboard.png)


#### 🚗 Vehicle Type Analysis

Vehicle Performance Table

Compares all vehicle categories based on:

Total Booking Value

Successful Booking Value

Average Ride Distance

Total Distance Travelled.

Vehicle categories analyzed include:

Auto

Bike

eBike

Go Mini

Go Sedan

Premier Sedan

Uber XL.


This helps identify the most profitable and frequently used ride categories.

#### 	Screenshots / Demos
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/analystvipull/uber-analysis/blob/main/Vehicle%20type%20analysis%20Dashboard%20%20(1).png)


#### 💰 Revenue Dashboard

Revenue by Payment Method (Bar Chart)

Analyzes revenue contribution from payment channels:

UPI

Cash

Uber Wallet

Credit Card

Debit Card

Ride Distance Distribution (Monthly Analysis) : Shows monthly ride-distance patterns and overall travel demand.

Top Customer Revenue Table: Identifies customers contributing the highest booking values, enabling customer segmentation and loyalty analysis.

#### 	Screenshots / Demos
Show what the dashboard looks like.
Example: ![(https://github.com/analystvipull/uber-analysis/blob/main/Revenue%20Dashboard.png)


#### ❌ Cancellation Dashboard

Customer Cancellation Analysis (Pie Chart)

Visualizes major customer-side cancellation reasons, such as:

Wrong Address

Change of Plans

Driver Delays

Driver Requested Cancellation

AC Not Working

Driver Cancellation Analysis (Pie Chart)

Tracks driver-side cancellation reasons, including:

Customer-related issues

Personal reasons

Vehicle-related issues

Operational constraints

Cancellation KPIs:

Total Bookings: 148.77K

Successful Bookings: 92.55K

Cancelled Bookings: 37.43K

Cancellation Rate: 25%

These insights help improve operational reliability and reduce ride abandonment.

#### 	Screenshots / Demos
Show what the dashboard looks like.
Example: ![(https://github.com/analystvipull/uber-analysis/blob/main/Cancellations%20Dashboard.png)



#### ⭐ Ratings Dashboard

Customer Ratings by Vehicle Type: Compares average customer ratings across all vehicle categories, highlighting service quality performance.

Driver Ratings by Vehicle Type: Evaluates average driver ratings to identify consistency in driver experience and performance.

The dashboard enables management to monitor satisfaction trends and maintain service standards across vehicle segments.

#### 	Screenshots / Demos
Show what the dashboard looks like.
Example: ![(https://github.com/analystvipull/uber-analysis/blob/main/Rating%20Dashboard.png)



#### • Business Impact & Insights
🚀 Operational Efficiency

Management can identify cancellation patterns and operational challenges to improve ride completion rates and driver allocation strategies.

💰 Revenue Optimization

Revenue analysis reveals the most profitable vehicle categories and preferred payment methods, supporting pricing and promotional decisions.

🚗 Fleet Utilization

Vehicle-wise booking and distance metrics help optimize fleet deployment based on customer demand.

😊 Customer Experience Enhancement

Customer and driver rating analysis provides actionable insights for improving service quality and user satisfaction.

📊 Data-Driven Decision Making

The dashboard consolidates operational, financial, and customer metrics into a single reporting solution, enabling faster and more informed business decisions.
