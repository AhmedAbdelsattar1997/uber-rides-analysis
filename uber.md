# Uber Data Analysis Project 🚗📊

## Project Description
This repository contains a comprehensive data analysis project using a dataset of Uber ride bookings (approximately 102,000 records). The goal of this analysis is to understand vehicle performance, revenue distribution, and the underlying reasons for customer cancellations.

## Features & Technical Highlights

### 1. Data Cleaning
* Handled missing values (NaN) in critical columns like `Booking Status` and `Reason for cancelling`.
* Ensured data consistency across 100k+ rows for accurate aggregation.

### 2. Vehicle Performance Metrics (Aggregation)
Using Python's `groupby` and `agg` functions, I transformed the raw transactional data into a performance summary table including:
* **Total Booking Value:** Gross revenue per vehicle type.
* **Success Booking Value:** Revenue filtered by 'Completed' status.
* **Average & Total Distance:** Insights into fleet efficiency and travel patterns.

### 3. Monthly Cancellation Trends (Data Reshaping)
* **Technique:** Used `Pivot` and `unstack` to reshape the data from a long format to a wide format.
* **Result:** A monthly view of cancellation reasons, allowing for a comparative analysis of customer behavior over time.

## Technologies Used
* **Python 3.x**
* **Pandas Library:** The core tool for data manipulation and reshaping.
* **Jupyter Notebook:** For an interactive and documented analysis workflow.

## How to Run
1. Clone the repository.
2. Ensure you have `pandas` installed: `pip install pandas`.
3. Open `uber.ipynb` in Jupyter Notebook or VS Code.

---
*Created as part of my Data Analysis portfolio.*