Below is the description of tasks I was solving here. I haven't put the solution to task 1 - only obtained csv files. 
Solutions to tasks 2 and 3 are in files groceries_delivery_analysis and groceries_delivery_research, respectively.

Introduction
Our company delivers grocery orders placed online, using GPS data from driver devices to predict delivery times. We currently use a simple average of past delivery times for predictions. 
Our aim is to refine these predictions to improve planning accuracy.

Data Definition
Data is stored across four tables:

    orders: Includes order_id, customer_id, sector_id, planned_delivery_duration.
    products: Includes product_id, weight.
    orders_products: Links orders to products and quantities.
    route_segments: Tracks delivery segments with details like driver_id, segment_type, segment times, and linked order_id for stops.

Tasks

   1. Data modeling [SQL]:
        -Set up a database from a provided SQL file.
        -Create a query to find the total weight of products ordered by customer 32 on February 13, 2024, sorted by weight. Export this as a CSV file.

  2. Data Analysis and Visualization:
        -Produce a histogram of actual delivery times with 1-minute intervals.
        -Chart the prediction errors (actual vs. planned times).
        -Visualize delivery time differences across sectors.
        -Explore the data for trends that could improve prediction accuracy and document these in a report.

  3. Building and Verifying Hypotheses:
        -Assess the viability of sector-based delivery time predictions.
        -Suggest and validate a new prediction model based on the findings.

The goal is to move from a simplistic average-based prediction to a more accurate and sector-specific approach. Reports should be clear and include all methodologies and assumptions.

