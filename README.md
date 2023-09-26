Calculating Uber Driver's Lifetime Value Using Python

Data Model Explanation:

driver_ids.csv:

driver_id: Unique identifier for a driver.
driver_onboard_date: Date when the driver joined Uber.
ride_ids.csv:

driver_id: Unique identifier for a driver.
ride_id: Unique identifier for a completed ride.
ride_distance: Distance of the ride in meters.
ride_duration: Duration of the ride in seconds.
ride_prime_time: Prime Time applied to the ride.
ride_timestamps.csv:

ride_id: Unique identifier for a ride event.
event: Type of event (e.g., requested, accepted, arrived, picked up, dropped off).
timestamp: Time of the event.
Objective:
Recommend the lifetime value of an Uber driver, which represents the driver's total value to Uber throughout their projected career. Answer key questions related to driver retention, segmentation, and business recommendations.

Assumptions:
We assume the following Uber rate card:

Base Fare: $2.00
Cost per Mile: $1.15
Cost per Minute: $0.22
Service Fee: $1.75
Minimum Fare: $5.00
Maximum Fare: $40.00



Key Questions to Address:

What factors influence a driver's lifetime value?
What is the average projected driver lifetime?
Do all drivers exhibit similar behaviors?
Are there driver segments that contribute more value than others?
What actionable insights can be derived for the business?
Recommendation:
After thorough analysis and modeling, we will provide insights into the expected lifetime value of Uber drivers, considering factors such as ride data and driver retention patterns. We will also identify segments of drivers who generate higher-than-average value for Uber and propose actionable recommendations for the business to enhance driver retention and profitability.

This analysis aims to provide a comprehensive understanding of driver lifetime value, contributing factors, and strategic directions for Uber's driver management.
