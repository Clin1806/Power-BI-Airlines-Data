# Airline Data Analysis and Visualization with Power BI
## Project Overview
This project involves analyzing airline data stored in CSV files, which include information on airlines, cancellations, airports, and flights. The analysis aims to uncover insights into flight operations, cancellation trends, and airport performance using Power BI visualizations.

### Data Sources
The analysis is based on CSV files containing the following datasets:

- Airlines: Information about different airlines, including names and codes.
- Cancellations: Data on flight cancellations, including reasons and frequencies.
- Airports: Details about airports, such as codes, names, and locations.
- Flights: Comprehensive data on flights, including departure/arrival times, delays, and status (on-time, delayed, cancelled).

### Data Preparation
Before visualizing the data in Power BI, the following steps were performed:

- Data Cleaning:
- Removed duplicates and unnecessary fields.
- Handled missing values (e.g., imputing averages for delays).
- Standardized date formats for consistency.

### Data Transformation:

- Categorized flights into "On-Time," "Delayed," and "Cancelled."
- Aggregated data by airline and airport for comparative analysis.

### Filters Applied:

Excluded incorrect or irrelevant records (e.g., flights with incomplete information).

## Visualization in Power BI
The following visuals were created to analyze the airline data:

1. Flight Performance Dashboard

- Bar Charts:

- Analyzed cancellation rates by airline.

- Compared on-time performance across airlines.

2. Cancellation Analysis
- Donut Charts:
-Showed reasons for cancellations (e.g., weather, mechanical issues).

- Column Charts:

Visualized cancellation frequencies by month/week.

3. Airport Performance

- Line Charts:

- Tracked trends in airport traffic over time.

4. Airline Comparison
- Created bar charts to compare airlines based on metrics such as:

- Cancellation rates

- On-time performance

- Average delay times

### Key Insights
Flight Performance:

- Identified airlines with the best on-time performance.

- Highlighted routes with frequent cancellations.

Cancellation Trends:

- Determined peak months for cancellations.

- Identified common reasons for cancellations (e.g., weather conditions).


Airline Comparison:

- Ranked airlines by cancellation rates and on-time performance.

- Highlighted airlines with consistent operational efficiency.

## Project Structure
text
├── data/
│   ├── airlines.csv
│   ├── cancellations.csv
│   ├── airports.csv
│   └── flights.csv
├── powerbi/
│   ├── flight_performance.pbix
│   ├── cancellation_analysis.pbix
│   └── airport_insights.pbix
└── insights/
    ├── airline_comparison.md
    ├── cancellation_trends.md
    └── airport_performance.md
## Technologies Used
Power BI: For creating dashboards and visualizations.

DAX (Data Analysis Expressions): For custom calculations such as aggregating cancellations by reason.
