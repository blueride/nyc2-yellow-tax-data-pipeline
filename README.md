# nyc2-yellow-tax-data-pipeline
NYC Yellow Taxi Dataset Analysis

This project involves analyzing the NYC Yellow Taxi dataset to extract various insights and statistics using SQL queries. The dataset contains information about taxi rides in New York City, including details such as trip distance, passenger count, fare amount, and more.

Dataset Description

The NYC Yellow Taxi dataset is a collection of taxi trip records in New York City. It includes information about millions of taxi rides, such as pickup and dropoff locations, trip duration, fare amounts, and more. The dataset can be obtained from https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data?resource=download


    analyze_taxi_data.py: This Python script contains SQL queries for extracting various statistics from the NYC Yellow Taxi dataset using a database connection.

    README.md: This file provides information about the project, dataset, and usage instructions.

Setup and Usage

    Clone the repository to your local machine.

    Install the required dependencies using the following command:

pip install pandas sqlalchemy

Open analyze_taxi_data.py and replace 'your_database_connection_string' with the actual connection string to your database containing the NYC Yellow Taxi dataset.

Run the analyze_taxi_data.py script using the following command:

    python analyze_taxi_data.py

    The script will execute SQL queries to extract insights from the dataset and display the results in the terminal.

Analysis Results

The analyze_taxi_data.py script provides the following statistics and insights:

    Total number of trips.
    Average trip distance.
    Vendor with the most trips.
    Vendor with the least trips.
    Average passenger count.
    Average trip amount per passenger.
    Average trip distance per passenger.
    Count of shared rides.
    Average fare amount.
    Total revenue (including tolls and surcharges).
    Average total amount.

Future Enhancements

    Visualize the analysis results using graphs and charts.
    Perform more complex analysis, such as time-based trends, geospatial analysis, etc.

References

    NYC Taxi and Limousine Commission (TLC) [https://www.nyc.gov/site/tlc/index.page]

License

This project is licensed under the [10Alytics] License 
