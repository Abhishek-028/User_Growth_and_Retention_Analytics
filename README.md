# Weekly User Growth Dashboard

This project focuses on analyzing user activity and growth metrics over time. The main goal is to calculate and visualize key user metrics such as retention, new users, churn, and resurrection on a weekly basis.

## Project Overview

The **Weekly User Growth Dashboard** aims to provide insights into user behavior through the following metrics:
- Retained Users
- New Users
- Churned Users
- Resurrected Users

These metrics are calculated for each week to understand user engagement, retention, and growth patterns.

## Data Description

The input data is a CSV file containing user activity data across multiple weeks. Each column in the dataset represents a specific week, and each row represents a user.

## Metrics Calculated

The project calculates the following metrics for each week:
1. **Retained Users**: Users active in both the current and previous week.
2. **New Users**: Users active in the current week but not in the previous week.
3. **Churned Users**: Users active in the previous week but not in the current week.
4. **Resurrected Users**: Users active in the current week who were inactive for a period before the previous week.
