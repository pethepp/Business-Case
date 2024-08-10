# Yulu Demand Analysis Project

## Overview
This project analyzes the key factors influencing the demand for Yulu's shared electric cycles in the Indian market. Yulu is a leading micro-mobility provider in India, offering sustainable transportation solutions through shared electric cycles. The analysis aims to identify trends and insights to help Yulu address its recent decline in revenues.

## Dataset
The dataset used in this project includes various features such as:
- `datetime`: The date and time of the ride.
- `season`: The season in which the ride took place (1: Spring, 2: Summer, 3: Fall, 4: Winter).
- `holiday`: Whether the day was a holiday or not.
- `workingday`: Whether the day was a working day or not.
- `weather`: The weather condition.
- `temp`: The temperature in Celsius.
- `atemp`: The perceived temperature in Celsius.
- `humidity`: The humidity level.
- `windspeed`: The wind speed.
- `casual`: The number of casual users.
- `registered`: The number of registered users.
- `count`: The total number of bike rentals.

## Project Structure
- `notebooks/`: Contains the Jupyter notebook with the analysis and visualizations.
- `data/`: The dataset used for analysis (if included).
- `README.md`: Project documentation.

## Analysis and Findings
- **Univariate Analysis**: We explored the distribution of individual variables, including temperature, humidity, and wind speed, to understand their effect on bike rentals.
- **Bivariate Analysis**: We examined the relationship between variables such as season and bike rentals to identify patterns and correlations.
- **Modeling**: We used regression models to predict demand based on the provided features.

## Conclusions
Our analysis revealed that certain factors, such as weather conditions and time of year, significantly influence the demand for Yulu's shared electric cycles. By focusing on optimizing operations during favorable conditions, Yulu can improve revenue and service efficiency.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    ```
2. Navigate to the project directory:
    ```bash
    cd yourrepository
    ```
3. Open the Jupyter notebook to explore the analysis.


