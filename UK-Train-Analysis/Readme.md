# UK Train Rides Data Analysis

This repository demonstrates the process of generating and analyzing train ticket data for the National Rail in the UK, covering journeys from January to April 2024. The dataset includes details about each journey, such as ticket type, departure and arrival stations, ticket prices, and journey status.

## Data Generation

The dataset consists of the following fields:

- **Transaction ID**: Unique identifier for each ticket purchase.
- **Date of Purchase**: The date the ticket was bought.
- **Time of Purchase**: The exact time the ticket was purchased.
- **Purchase Type**: Whether the ticket was bought online or at the station.
- **Payment Method**: Method used for payment (e.g., Credit Card, Contactless).
- **Railcard**: Type of railcard used (e.g., Adult, Senior, Disabled).
- **Ticket Class**: Class of the ticket (e.g., Standard, First Class).
- **Ticket Type**: Type of the ticket (e.g., Advance, Anytime).
- **Price**: The price of the ticket.
- **Departure Station**: The station where the journey starts.
- **Arrival Station**: The station where the journey ends.
- **Date of Journey**: The date of the journey.
- **Departure Time**: The scheduled departure time.
- **Arrival Time**: The scheduled arrival time.
- **Actual Arrival Time**: The actual arrival time (used to calculate delays).
- **Journey Status**: Journey status (e.g., On Time, Delayed).
- **Reason for Delay**: If the journey was delayed, this field describes the reason (e.g., Signal Failure, Weather).
- **Refund Request**: Whether a refund was requested (Yes/No).

## Analysis

The following analyses are performed on the dataset:

1. **Most Popular Routes**: Grouping by departure and arrival stations, and counting the occurrences of each route to identify the most frequently traveled routes.
2. **Peak Travel Times**: Analyzing the `Departure Time` to identify peak hours for train travel.
3. **Revenue Variation by Ticket Types and Classes**: Calculating the total revenue by grouping the data by `Ticket Type` and `Ticket Class` and summing the `Price` for each category.
4. **On-Time Performance (OTP)**: Calculating the percentage of journeys marked as "On Time" and the average delay time for delayed journeys, grouped by the reason for delay.

## Insights

The dataset provides insights into the operational performance of train journeys, including:

- Ticket sales performance
- Most popular routes
- Peak travel times
- Delay reasons and their impact on On-Time Performance
- Revenue variations by ticket types and classes

