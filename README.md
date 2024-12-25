# US Domestic Flights 2013 Analysis

This project analyzes a dataset containing observations of US domestic flights in 2013. The dataset consists of the following fields:

- **Year**: The year of the flight (all records are from 2013)
- **Month**: The month of the flight
- **DayofMonth**: The day of the month on which the flight departed
- **DayOfWeek**: The day of the week on which the flight departed - from 1 (Monday) to 7 (Sunday)
- **Carrier**: The two-letter abbreviation for the airline
- **OriginAirportID**: A unique numeric identifier for the departure airport
- **OriginAirportName**: The full name of the departure airport
- **OriginCity**: The departure airport city
- **OriginState**: The departure airport state
- **DestAirportID**: A unique numeric identifier for the destination airport
- **DestAirportName**: The full name of the destination airport
- **DestCity**: The destination airport city
- **DestState**: The destination airport state
- **CRSDepTime**: The scheduled departure time
- **DepDelay**: The number of minutes departure was delayed (flights that left ahead of schedule have a negative value)
- **DepDelay15**: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late")
- **CRSArrTime**: The scheduled arrival time
- **ArrDelay**: The number of minutes arrival was delayed (flights that arrived ahead of schedule have a negative value)
- **ArrDelay15**: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late")
- **Cancelled**: A binary indicator that the flight was cancelled

## Objectives

The goal of this project is to explore the flight data to analyze possible factors that affect delays in departure or arrival of a flight. The analysis includes:

1. **Data Cleaning**:
   - Identify any null or missing data, and impute appropriate replacement values.
   - Identify and eliminate any outliers in the **DepDelay** and **ArrDelay** columns.

2. **Data Exploration**:
   - View summary statistics for the numeric fields in the dataset.
   - Determine the distribution of the **DepDelay** and **ArrDelay** columns.
   - Use statistics, aggregate functions, and visualizations to answer the following questions:
     - What are the average (mean) departure and arrival delays?
     - How do the carriers compare in terms of arrival delay performance?
     - Is there a noticeable difference in arrival delays for different days of the week?
     - Which departure airport has the highest average departure delay?
     - Do late departures tend to result in longer arrival delays than on-time departures?
     - Which route (from origin airport to destination airport) has the most late arrivals?
     - Which route has the highest average arrival delay?

## Getting Started

To get started with the analysis, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone <https://github.com/Dawood-Imran/flights-dataset-challenge.git>