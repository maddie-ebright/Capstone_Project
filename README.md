# Kent District Library Budget Forecasting and Optimization

## Project Overview

This capstone project was completed in partnership with Kent District Library (KDL) to analyze historical circulation and financial data and develop forecasts for future library usage and spending. The project combined multiple years of monthly data across digital and physical library services to identify trends, seasonal patterns, and opportunities for improved budget allocation.

## Objectives

- Combine and clean multiple financial and circulation datasets
- Analyze trends in digital and physical library usage
- Identify seasonal patterns in checkouts and spending
- Forecast future circulation and costs
- Compare growth across services such as OverDrive, Hoopla, Kanopy, and physical materials
- Provide data-driven insights for future budget planning

## Data Analyzed

The project included approximately four years of monthly data across several categories:

- Physical book checkouts and costs
- OverDrive checkouts, circulations, and expenditures
- Hoopla checkouts, circulations, and costs
- Kanopy circulations and costs
- Invoice and departmental spending data

More than 50 Excel files were combined, cleaned, and standardized for analysis.

## Methods

The project used multiple time-series and forecasting techniques, including:

- **STL Decomposition:** Used to separate observed data into trend, seasonal, and residual components
- **Holt-Winters Exponential Smoothing:** Used to forecast datasets with consistent trend and seasonal patterns
- **SARIMA/SARIMAX Models:** Used for time-series forecasting when autoregressive, differencing, moving-average, and seasonal components were appropriate
- **Scenario Analysis:** Used to evaluate potential changes in future spending and service allocation
- **Cost-per-Circulation Analysis:** Used to compare the financial efficiency of different library services

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Excel
- Time-Series Forecasting
- Data Cleaning and Integration

## Key Findings

The analysis showed a major shift toward digital library services. OverDrive checkouts increased approximately 63% from 2021 to 2024, while physical book checkouts increased by only about 2%.

The project also identified important differences in the cost structures of digital services. OverDrive operates through licensing models that can allow repeated borrowing, while Hoopla uses a pay-per-circulation model. Because of this structure, Hoopla spending can increase rapidly as usage grows.

Seasonal decomposition also revealed recurring patterns in library demand, demonstrating that certain periods experience predictable increases or decreases in circulation and spending.

## Conclusion and Recommendation

The project concluded that KDL’s growing digital demand should play a larger role in future budget planning. Forecasting results indicated continued growth in digital services, while physical circulation remained comparatively stable.

Based on these findings, the project recommended using forecasted demand and seasonal usage patterns to guide budget allocation. KDL should continue supporting physical materials while strategically allocating resources toward growing digital services. The analysis also highlighted the importance of closely monitoring pay-per-circulation platforms such as Hoopla because increased usage can lead to faster budget growth than services using reusable licensing structures.

Overall, the project demonstrated how time-series forecasting, cost analysis, and scenario modeling can support more proactive and data-driven library budget decisions.
