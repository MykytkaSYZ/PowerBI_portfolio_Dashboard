# PowerBI Car Sales Analytics Dashboard :car: :bar_chart: 

Welcome to Car Sales Analytics Dashboard :raised_hands:. This GitHub repository presents a complete and interactive Power BI dashboard for analyzing car sales data across different dimensions, including time, brand, dealership, customer demographics, and vehicle attributes.

# Project Objectives :dart:
- Track and compare sales performance between 2022 and 2023
- Explore average prices, sales volume, and customer income
- Analyze brand and dealership performance
- Compare sales by transmission type, body style, and color
- Identify customer behavior patterns using scatter plots and cohort analysis

# Dashboard
![image](https://github.com/user-attachments/assets/5380bf07-fc0c-4997-967a-c9d45cf161b1)
![image](https://github.com/user-attachments/assets/bac897a9-28e4-4aac-a290-1854e293e15f)
![image](https://github.com/user-attachments/assets/e7d27817-61a3-4f7f-9623-9644ca402a61)
![image](https://github.com/user-attachments/assets/7dca733f-440f-4fbf-90ea-3f280cee7d86)

# Data Description :memo:
This Car Sales Report dataset contains detailed records of vehicle sales transactions, including customer demographics, dealership information, car specifications, and pricing. The dataset spans multiple regions and includes fields such as brand, model, engine type, transmission, body style, and customer income. It is provided as a CSV file with approximately 24,000 rows.

Dataset: [Car Sales Report](https://www.kaggle.com/datasets/missionjee/car-sales-report)

# Key DAX Measures Used :green_book:

General KPIs

```dax 
Total Sales = SUM('car_data'[Price ($)])
Average Car Price = AVERAGE('car_data'[Price ($)])
Cars Sold = COUNT('car_data'[Car_id])
``` 

Company Metrics

```dax 
Avg Annual Income = AVERAGE('car_data'[Annual Income])
Avg Car Price = AVERAGE('car_data'[Price ($)])
Car Count = COUNT('car_data'[Car_id])
```

Dealer Metrics

```dax 
Dealer Sales = SUM('car_data'[Price ($)])
Dealer Avg Price = AVERAGE('car_data'[Price ($)])
Dealer Cars Sold = COUNT('car_data'[Car_id])
Dealer Customers = DISTINCTCOUNT('car_data'[Customer Name])
```

# The end :innocent:
Thank you for taking the time to view this project. I hope this dashboard provides you with a clear example of how data can be transformed into meaningful insights through visualization.








