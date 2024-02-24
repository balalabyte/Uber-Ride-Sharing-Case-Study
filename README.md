# Uber-Ride-Sharing-Case-Study
TL;DR: The analysis of ride-sharing data, focusing on Commute vs. Non-Commute Hours and Treatment vs. Control Groups, revealed significant patterns. Commuting hours see more ride-sharing trips, with varied profitability and service preferences. Treatment vs. Control Groups showed nuanced impacts on user behavior and highlighted sensitivity to wait times. Kernel density estimation illustrated cancellation rate variations. Rigorous statistical testing confirmed complexities in user preferences, offering valuable operational insights for ride-sharing companies to optimize services and enhance satisfaction and profitability.

![image](https://github.com/balalabyte/Uber-Ride-Sharing-Case-Study/assets/60688697/15a0ff5f-6343-49b6-a006-41f9eb3c47e6)

## Project Overview

This project involves analyzing ride-sharing data to understand patterns related to commute and non-commute hours, the impact of treatment and control groups on rider behavior, and various statistical aspects such as cancellations, payouts, and trip frequencies. The goal is to derive insights that can help improve ride-sharing efficiency and profitability.

## Dataset

The analysis is based on a dataset that includes details on trips, cancellations, payouts, and other relevant information for a ride-sharing company. This dataset is divided into several files:

- `Case-Data 3.xlsx`: Contains the main ride-sharing data, including trip information, commuter flags, and payout details.
- `Case-Data 3 Data Dictionary.csv`: Provides a description of the data fields in the main dataset.

## Key Findings

### 1. Commute vs. Non-Commute Hours Analysis

- **Higher Ride-Sharing Trips During Commuting Hours**: The data analysis revealed that commuting hours experience a higher number of ride-sharing trips compared to non-commuting hours. The difference was statistically significant, indicating a robust pattern where commuting times are peak periods for ride-sharing services.
- **Service Type Preference**: During commuting hours, there was a noticeable preference for certain types of ride-sharing services over others. A statistically significant association between commuting hours and the type of ride (pool vs. express) was observed, suggesting that user preferences for ride-sharing services vary with the time of day.
- **Profitability Analysis**: The analysis of Uber's profit revealed distinct patterns between commuting and non-commuting hours. Despite the higher number of trips during commuting hours, the profit margins varied significantly, with non-commuting hours showing substantial profitability under certain conditions. This aspect highlights the complexity of ride-sharing economics and the importance of strategic pricing and service allocation.

### 2. Treatment vs. Control Groups Analysis

- **Impact on Ride-Sharing Trips**: The comparison between treatment and control groups during commuting and non-commuting hours provided insights into user behavior under different operational strategies. The statistical tests indicated that the differences in the number of ride-sharing trips between these groups were not always significant, suggesting that factors other than just commuting times influence ride-sharing decisions.
- **Rider Cancellation and Payouts**: The analysis extended to rider cancellation rates and driver payouts, uncovering significant differences between treatment and control groups. These differences were particularly pronounced during commuting hours, where the cancellation rate was higher for the treatment group, pointing to the sensitivity of ride-sharing users to wait times and service expectations.

### 3. Kernel Density Estimation of Cancellation Rates

- **Distribution of Cancellation Rates**: Utilizing kernel density estimation, the study explored the distribution of cancellation rates during commuting and non-commuting hours. This approach revealed distinct patterns in cancellation behaviors, with commuting hours showing a wider range of cancellation rates. These findings suggest that users' tolerance for wait times and other service factors varies significantly during peak periods.

### 4. Statistical Significance and Implications

- **Statistical Analysis**: Through rigorous statistical testing, including t-tests and chi-square tests, the analysis confirmed several hypotheses about ride-sharing behaviors and refuted others. The statistically significant differences found in various aspects of the data underscore the complexity of user preferences and operational efficiencies in ride-sharing ecosystems.
- **Operational Insights**: The detailed statistical analysis offers valuable insights for ride-sharing companies to optimize their services. By understanding the nuances of user behavior during different times and under different conditions, companies can tailor their offerings to maximize user satisfaction and profitability.



## Prerequisites

Before running the analysis, ensure you have the following installed:

- Python 3.x
- Pandas library
- NumPy library
- Matplotlib library
- Seaborn library
- SciPy library

