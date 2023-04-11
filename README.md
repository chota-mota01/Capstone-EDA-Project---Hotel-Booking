# Capstone-EDA-Project---Hotel-Booking

# Introduction

We are provided with a hotel booking dataset. The main objective is to perform EDA on given dataset and provide actionable insights to enhance hotel business.

# Problem Statement

*Hotel Booking Data Analysis*

The hotel industry generates a vast amount of data, including customer information, room types, prices, and booking patterns. However, analyzing this data can be challenging and time-consuming, but it is crucial for hotel management to make informed decisions and improve their business operations. Analyzing the dataset can help the customers to know the best time of year to book a hotel room and optimal length of stay to get the best daily rate. The following dataset can help to explore various questions.

The hotel booking dataset contains booking information for a city hotel and a resort hotel,includes information such as when the booking was made, length of stay, number of adults,children & babies, and the number of available parking spaces, country, customer types, market segment, distribution channels and many more factors. The data will help us understand the factors to optimize occupancy rates, increase revenue, and improve customer satisfaction.

# Dataset Information

The dataset given contains booking information for a city hotel and a resort hotel. The dataset has 119390 rows and 32 columns. The dataset includes information such as when the booking was made, length of stay, number of adults,children & babies, and the number of available parking spaces, country, customer types, market segment, distribution channels and many more factors. 

The variables are described as follows:

**Hotel**       **:**  Resort Hotel , City Hotel

**is_cancelled**       **:**  Cancelled Booking (1,0)

**lead_time**       **:**  Number of days between booking and check-in date

**arrival_year**       **:**  Year of arrival 

**arrival_month**       **:**  Month of arrival

**arrival_week_no**       **:**  Week number for arrival

**arrival_day** **:**  Day of arrival

**weekend_nights**       **:**  Hotel booked for number of weekend nights 

**week_nights**       **:**  Hotel booked for number of week nights 

**adults**       **:**  Number of adults stayed at the hotel

**children**       **:**  Number of children stayed at the hotel

**babies**       **:**  Number of babies stayed at the hotel

**meal**       **:**  Different kind of meal opted by the guest/customer

**country**       **:**  Country code

**market_segment**       **:**  Segment to which customer belongs

**Distribution_channel**       **:**  Stay accessed (corporate booking/Direct/TA) 

**is_repeated_guest**       **:**  Repeated customers (0,1) 

**previous_cancellation**       **:**  Prior Cancellation check

**previous_bookings**       **:**  Bookings done previously

**reserved_room**       **:**  Type of reserved room

**assigned_room**       **:** Type of assigned room

**booking_changes**       **:** Changes made in booking

**deposit_type**       **:** Type of deposit

**agent**       **:** Booking done through agent

**company**       **:** Booked through company

**days_in_waiting**       **:** Days in waiting list

**customer_type**       **:** Customer Type

**adr**       **:** Average Daily Rate

**req_car_parking**       **:** Requirement of car parking spaces

**special_requests**       **:** Additional special requirements

**reservation_status**       **:** Booking status

**reservation_status_date**       **:** Date of reservation status

**total_nights**       **:** Total stays in night

**total_guests**       **:** Total number of guests arrived

# Data Cleaning and Manipulation 

1.Handling Null & Duplicate Values

* All duplicate rows were removed.
* Null values in children,agent & company columns were replaced by 0.
* Null values in country were replaced by not specified.

2.Converting Datatypes

* Converted column children,agent & company to int type.
* Converted column reservation_status_date to datetime data type.

3.Creating New columns

* Created new column total_nights by combining weekend_nights and week_nights.
* Created new column total_guests by combining adults, children and babies columns.

# EDA 

The data visualization is performed using mainly seaborn & matplotlib library. For visualization, the following charts are used:

Pie Chart

Bar plot

Count plot

Displot

Line plot

Scatter plot

Box plot

Correlation Heatmap

Pair plot

# The following questions were tried to solve by performing EDA :

1. What is the percentage of repeated guests?
 
2. Which type of hotel is mostly prefered by the guests?

3. Which meal type is the most preffered meal of customers ?

4. How long do people spend night at the hotels(stay)?

5. Which customer type made maximum number of bookings?

6. Which room type is mostly preferred by the customers?

7. Which age group made more number of booking? 

8. How is adr related to monthwise arrival of the customers?

9. In which of the month most of the customers arrived? Which is the least favourable month for customers to visit hotel?
 
10. From which country most of the bookings were done?
 
11. Which agent made maximum Bookings?

# Conclusion

The conclusion derived from hotel booking analysis are as follows:

1. The guest retention rate is very low as the repeated guest are less and non repeated guest are excessive. 

2. City Hotel were more preferable than Resort Hotel with 61.07% bookings in city hotel and 38.93% bookings in resort hotel.

3. The favourite meal of the customers is 'BB'. 

4. The guests arriving the hotel tends to stay as long as 4 nights in both the hotels and less preference is given to the stays more than 4 nights in each hotel.

5. The maximum type of customers are of transient type.

6. Most of the reserved room was A, so need to increase type A room also need to work on other type of room as well.

7. Most arriving customers are pair of adults so need to work on other age group as well like children.

8. The length of total nights increases, adr decreases.

9. Most of the bookings were done in month of July-August, means this months are the businest or profitable months for hotel business.

10. Booking were made from different country, but most of the booking were made by Portugal country.

11. Maximum number of the bookings are done by Agent 9.

12. ADR tends to increase with number of customers arrived per month, also it is seen that ADR increases at end of month.



















