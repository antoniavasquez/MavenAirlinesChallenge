# MavenAirlinesChallenge
Challenge Objective: Customer Satisfaction Analysis for Maven Airlines
# Overview
For this challenge, you'll be assuming the role of Senior Data Analyst for Maven Airlines, a US-based airline headquartered in Boston, Massachusetts. The latest passenger survey results just came in and it looks like the satisfaction rate dipped under 50% for the first time ever. The leadership team needs to take action fast, so they've brought you in to analyze the data and find the key areas to focus on for getting back on track.

Your task is to recommend a data-driven strategy for increasing Maven Airlines' satisfaction rate, and present it in the form of a single page report or dashboard.

The objective is to prepare the data, analyze and visualize it. Following these steps, insights that will help increase Maven Airlines' satisfaction rate will be outlined to create a data-driven strategy.

The major questions we will attempt to answer are: r
1. Who are the passengers and what are their demographics? Demographics (age, gender, type of travel) and their distribution.
2. What is the general satisfaction level among passengers?
3. Overall satisfaction scores and how they vary by customer type, travel class, and purpose.
4. Which factors influence passenger satisfaction the most?
5. Analysis of different satisfaction metrics (seat comfort, online booking, in-flight service) and their impact on overall satisfaction.
6. Are there significant correlations between different aspects of the passenger experience?
7. Correlation between satisfaction scores in various services and overall satisfaction.
8. What are the areas of improvement to enhance passenger satisfaction?
9. Identification of weak points in services and recommendations for improvement.

# Data Collection
The dataset used in this project originates from the Maven Airlines Challenge: [Maven Airlines Challenge](url)

We are given one table in CSV format which contains the following fields: 
1.  ID - Unique passenger identifier
2.  Gender - Gender of the passenger (Female/Male)
3.  Age - Age of the passenger
4.  Customer Type - Type of airline customer (First-time/Returning)
5.  Type of Travel - Purpose of the flight (Business/Personal)
6.  Class - Travel class in the airplane for the passenger seat
7.  Flight Distance - Flight distance in miles
8.  Departure Delay - Flight departure delay in minutes
9.  Arrival Delay - Flight arrival delay in minutes
10.  Departure and Arrival Time Convenience - Satisfaction level with the convenience of the flight departure and arrival times from 1 (lowest) to 5 (highest) - 0 means "not applicable"
11.  Ease of Online Booking - Satisfaction level with the online booking experience from 1 (lowest) to 5 (highest) - 0 means "not applicable"
12.  Check-in Service - Satisfaction level with the check-in service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
13.  Online Boarding - Satisfaction level with the online boarding experience from 1 (lowest) to 5 (highest) - 0 means "not applicable"
14.  Gate Location - Satisfaction level with the gate location in the airport from 1 (lowest) to 5 (highest) - 0 means "not applicable"
15.  On-board Service - Satisfaction level with the on-boarding service in the airport from 1 (lowest) to 5 (highest) - 0 means "not applicable"
16.  Seat Comfort - Satisfaction level with the comfort of the airplane seat from 1 (lowest) to 5 (highest) - 0 means "not applicable"
17.  Leg Room Service - Satisfaction level with the leg room of the airplane seat from 1 (lowest) to 5 (highest) - 0 means "not applicable"
18.  Cleanliness - Satisfaction level with the cleanliness of the airplane from 1 (lowest) to 5 (highest) - 0 means "not applicable"
19.  Food and Drink - Satisfaction level with the food and drinks on the airplane from 1 (lowest) to 5 (highest) - 0 means "not applicable"
20.  In-flight Service - Satisfaction level with the in-flight service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
21.  In-flight Wifi Service - Satisfaction level with the in-flight Wifi service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
22.  In-flight Entertainment - Satisfaction level with the in-flight entertainment from 1 (lowest) to 5 (highest) - 0 means "not applicable"
23.  Baggage Handling - Satisfaction level with the baggage handling from the airline from 1 (lowest) to 5 (highest) - 0 means "not applicable"
24.  Satisfaction - Overall satisfaction level with the airline (Satisfied/Neutral or unsatisfied)

The dataset was separated into three different tables as follows. This is because we can analyze the data on a modular level, improves Power BI's efficiency, allows for simpler relationships and a simpler/cleaner data model.
1. Passenger Demographics - ID, Gender, Age, Customer Type, Type of Travel, Class
2. Flight Details - ID, Fllght Distance, Departure Delay, Arrival Delay
3. Satisfation Metrics - ID. All Satisfaction-related fields: ease of online booking, check-in service etc.
