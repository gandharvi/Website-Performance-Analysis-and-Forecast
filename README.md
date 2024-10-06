# Website Performance Analysis and Forecast

## Overview
This project focuses on analyzing and forecasting website performance metrics, such as user sessions, engagement, and channel performance. We use time-series forecasting models to predict future website traffic and engagement trends, providing insights into user behavior and engagement across different channels.

## Dataset
The dataset used for this project can be found at the following link:  
[Website Performance Dataset](https://statso.io/website-performance-case-study/#google_vignette)

It includes data on user sessions, engaged sessions, engagement time, events, and channel performance over time.

## Key Metrics Analyzed
1. **Total Users and Sessions**: Tracks user activity over time.
2. **Engagement Metrics**: Includes average engagement time, engaged sessions per user, and events per session.
3. **Channel Performance**: Evaluates how different traffic channels (e.g., direct, organic search, referrals) perform in terms of user engagement.

## Forecasting
The SARIMA (Seasonal ARIMA) model is applied to forecast website traffic (sessions) for the next 24 hours, offering a glimpse into expected future performance. Both the actual data and forecasted results are plotted for comparison.

## Requirements
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Statsmodels
