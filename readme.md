# Hotel Data Analysis

## Overview

This project analyzes hotel booking data to uncover trends and insights. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization of various metrics related to hotel bookings, cancellations, and guest behavior. The objective is to understand the factors affecting hotel bookings and cancellations and to derive actionable insights from the data.

## Table of Contents

- [Installation](#installation)
- [Data](#data)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)

## Installation

To run the notebook, you need to have Python and Jupyter Notebook installed. You also need the following Python libraries: pandas, numpy, matplotlib, and seaborn. These can be installed using pip.

## Data

The dataset used in this project contains information about hotel bookings. The main columns in the dataset include:

- **hotel**: Type of hotel (Resort Hotel or City Hotel)
- **is_canceled**: Whether the booking was canceled
- **lead_time**: Number of days between booking and arrival
- **arrival_date_year**: Year of arrival date
- **arrival_date_month**: Month of arrival date
- **arrival_date_day_of_month**: Day of arrival date
- **adr**: Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights

## Data Cleaning

The following steps were performed to clean the data:

1. **Handling Missing Values**: Missing values were addressed using appropriate techniques such as imputation or removal.
2. **Data Type Conversion**: Certain columns were converted to appropriate data types for better analysis.
3. **Feature Engineering**: New features were created from existing data, such as extracting month and year from the arrival date to facilitate monthly and yearly analysis.

## Exploratory Data Analysis

EDA was performed to understand the data better and to identify any patterns or trends. The key analyses included:

1. **Distribution of Bookings**: Analyzing the number of bookings for each hotel type to understand the popularity of Resort and City hotels.
2. **Cancellation Rates**: Investigating the cancellation rates and identifying factors contributing to cancellations, such as lead time and arrival month.
3. **Lead Time Analysis**: Understanding the relationship between lead time and cancellations to see if longer lead times are associated with higher cancellation rates.
4. **Average Daily Rate (ADR)**: Comparing ADR between canceled and non-canceled bookings to understand the financial impact of cancellations.

## Visualizations

Several visualizations were created to illustrate the findings from the data analysis:

1. **Bookings by Hotel Type**: A visualization showing the distribution of bookings between Resort Hotel and City Hotel.
2. **Cancellation Rates**: A bar plot showing the relationship between lead time and cancellation status.
3. **ADR per Month**: A bar plot showing the ADR per month for canceled bookings.
4. **Average Daily Rate**: A line plot comparing the ADR over time between canceled and non-canceled bookings.

## Conclusion

The analysis provided several key insights:

1. **Booking Preferences**: The distribution of bookings showed a preference for City Hotels over Resort Hotels.
2. **Cancellation Patterns**: Higher lead times were associated with increased cancellation rates. This indicates that guests who book far in advance are more likely to cancel.
3. **Seasonal Trends**: ADR varied significantly across different months, with certain months showing higher rates for canceled bookings. This could be due to seasonal trends affecting both demand and pricing strategies.
4. **Financial Impact**: Cancellations had a noticeable impact on the average daily rates, with canceled bookings generally showing different ADR trends compared to non-canceled bookings.

These insights can help hotel managers and decision-makers to develop strategies for reducing cancellations and optimizing pricing to improve revenue management.

For further details, refer to the `Hotel_data_analysis.ipynb` notebook.
