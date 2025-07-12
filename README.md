# Customer Segmentation & Marketing Channel Analysis
## Project Overview
This project aims to analyze customer behavior by performing segmentation, both from the original dataset and using the Recency, Frequency, and Monetary (RFM) Analysis method. Additionally, it includes calculations for conversion rates across various advertising channels used.

---

## Dashboard Insight
### Overview: Customer Segmentation
<img width="1676" height="996" alt="image" src="https://github.com/user-attachments/assets/daa5be57-4ef1-44a8-95b7-8aaae1a2e982" />

This dashboard provides a general overview of customer data and segmentation without RFM analysis, displaying:
* Total customers and total orders both overall and by active year.
* The top 3 cities by profit along with their respective customer counts.
* The most frequently sold product categories.
* Cities with the highest to lowest total orders.

### RFM Analysis & Marketing Channeling
<img width="1691" height="1006" alt="image" src="https://github.com/user-attachments/assets/39f86055-9683-4bf5-831b-0819a0e00c26" />

This dashboard focuses on customer segmentation based on RFM analysis and the number of converted customers (those who made a purchase) from all visitors for each marketing channel used.
* Customer segmentation using RFM Analysis: RFM scores are calculated on a scale of 1-3 for each metric:
  * A higher `Recency` score indicates a more recent transaction since the customer's last purchase or a specified date.
  * A higher `Frequency` score indicates how often a customer makes purchases within a given period.
  * A higher `Monetary` score indicates how much money a customer has spent within a given period.
  * The combination of these scores results in 8-9 distinct customer categories.
* Total converted customers from impressions: Filters are available to display conversion rates for each marketing channel used.

---

## Repo Content
This repository contains the main components of the project:
* Power BI Report: the Power BI `.pbix` file
* Exported Report: The files which are exported version of the Power BI Dashboars

---

## Workflow
The project workflow involves the following steps:
1. Data Preparation and Manipulation: All data cleaning, transformation, and manipulation processes were performed directly within Power BI using DAX (Data Analysis Expressions) formulas. This approach was chosen for efficiency and to centralize all data logic within the Power BI environment.
2. RFM Score Calculation: RFM scores were calculated using DAX, along with the percentage of conversions from impressions for each marketing channel.

---

## Tools
* Power BI
* DAX (Data Analysis Expression)
