# Travel Bookings Data Ingestion Pipeline With SCD2 Merge

1. In this we have booking data and customer data for each date.
2. Firstly going to perform PyDeeQu checks on both the data , run on verification suite and check verification results.
3. We create a fact table for aggregation to store quantities and a dimension table to keep track of the history by changing valid_to and valid_from accordingly.
