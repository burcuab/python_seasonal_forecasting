**Sales Forecasting with Seasonality Analysis**

The purpose is to forecast e-commerce sales using historical transaction data. The analysis incorporates seasonality detection, moving averages, and basic predictive modeling to estimate future sales trends.

**Dataset Used**

Source: Kaggle (E-commerce Sales Data) 

Columns:

InvoiceDate: Date of transaction

Quantity: Number of items sold

UnitPrice: Price per unit

TotalSales: Computed as Quantity * UnitPrice

DayOfWeek: Extracted from InvoiceDate

Month: Extracted from InvoiceDate

**Steps in the Analysis**

Data Preprocessing:

Convert InvoiceDate to datetime format.

Aggregate total sales per day.

Extract seasonal indicators (day of the week, month).

Seasonality Analysis:

Identify high and low sales days.

Compute monthly and weekly sales trends.

Sales Forecasting:

Use historical sales trends for prediction.

Forecast next 90 days using weighted averages.

Visualization:

Plot actual sales trends.

Display seasonal trends.

Compare forecasted vs. actual sales.

