# new-york-taxi-data


In this project, I focused on processing and analysing NYC taxi data using Python, Pandas and PostgreSQL.

## Project Overview

The purpose of this project was to extract valuable insights from NYC taxi data. I covered data preprocessing, SQL querying and creating reporting tables to present meaningful information about taxi service operations, customer tendencies, and financial performance.

## Getting Started

### Installation

I ensured that I had Python, Pandas and PostgreSQL installed on my system.

### Cloning the Repository

To get started, I cloned this repository to my local machine using:

```
git clone https://github.com/HaelV2/new-york-taxi-data.git
cd new-york-taxi-data
```

### Data

I downloaded the NYC taxi dataset from Kaggle ('yellow_tripdata_2016-02.csv') and placed it in the project folder.

### Database Setup

For the database, I modified the PostgreSQL connection details in the code to match my environment.

## Key Steps

1. **Data Preprocessing:** I began by loading a sample of the data into a Pandas DataFrame and ensuring data integrity by converting date-time columns into the appropriate format.

2. **ETL Process:** I implemented the ETL function `etl_nyc_taxi()` to process the data in chunks of 100,000 to then insert it into the PostgreSQL database, optimising memory usage.

3. **Testing SQL Queries:** To verify the database's operational status, I ran SQL queries to preview the data.

4. **Operations and Performance:** Using analytical SQL queries, I revealed insights such as total trips, average trip distance and vendor statistics.

5. **Customer Tendencies:** Additional SQL queries shed light on the average trip amount, average trip distance and customer behaviours.

6. **Financial Performance:** I used SQL queries to gain insights into fare amounts, tolls and surcharges, providing a comprehensive view of financial metrics.

7. **Creating Reporting Tables:** To facilitate easier access, I crafted reporting tables from SQL query results and loaded them into the PostgreSQL database using Pandas.

## Usage

- Interested parties can run the provided Python script step by step to perform data preprocessing, ETL, querying, and reporting.
- Modifying SQL queries or adapting the code for different datasets or analysis needs is possible.


## Contributions

Contributions are welcome! I encourage others to suggest improvements, report issues, or extend the analysis. The project benefits from collaborative efforts.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as needed.

## Acknowledgments

I'd like to express gratitude to the open-source community, Python, Pandas and PostgreSQL teams for their remarkable tools and resources.

## Conclusion

This project exemplifies practical data engineering processes and insights extraction from real-world data.
