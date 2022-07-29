# Capstone-Project-Hotel-Booking-Analysis
# Objective
We are provided with a hotel bookings dataset.
Out main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.
# Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel & The dataset has total of 32 columns and 119390 rows & 
the Dataset spans over 3 years that is 2015, 2016 & 2017. 
# Data Cleaning and Feature Engineering
# (1) Removing Duplicate rows
All duplicate rows were dropped.

# (2) Handling null values
Null values in columns company and agent were replaced by 0.
Null values in column country were replaced by 'others'.
Null values in column children were replaced by the mean of the column.
# (3) Converting columns to appropriate data types
Changed data type of children, company, agent to int type.
Changed data type of reservation_status_date to date type.
# (4) Removing outliers
One outlier was found in the adr column. Simply dropped it.
# (5) Creating new columns
Created new column total_stay by adding stays_in_weekend_nights+stays_in_week_nights.
Created new column total_people by adding adults+children+babies.

# Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

Bar Plot.

Histogram.

Scatter Plot.

Pie Chart.

Line Plot.

Heatmap.

Box Plot.

# COCLUSIONS

(1) The majority of the reservations are for city hotel than resort hotel and most in the year 2016.

(2) The majority of the reservations are in the masoon and summer seasons.

(3)The guests are correlated with the adr which increases the revenue of the hotel.

(4) Most of the guests come from Portugal and other European countries.

(5) Most of the Hotel Booking is done by online TA market segment and ofline TA/TO market segment.

(6) Resort hotel prices are higher than the city hotel and most expensive in August and July.

(7) Posibity of cancellation of booking increases with increase in lead time.

(8) Most of guests prefer to stay in the hotel less than 5 nights.

# CHALLENGES

Understand the columns of the dataset.

Analyze and visualization of questions.

Find the right chart to show the chart.

Difficulties in analysing and visualization.
