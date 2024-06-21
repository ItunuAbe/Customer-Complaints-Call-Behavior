# Customer Complaints Call Behavior Analysis

## Project Objective

The project aims to create an accessible dashboard that provides insights into customer repeat calls. It will analyze the frequency of repeat calls, identify the issue category generating the most repeats, and highlight the service center with the highest repeat call volume. This analysis will help the stakeholders understand the team's ability to resolve queries on the first contact and facilitate improvements in customer satisfaction and operational efficiency.

## Data Overview
It’s a fictional dataset, provided by the Google Fiber Customer Service team, covering customer service calls from January 2022 to March 2022. The dataset includes the number of calls received, call type, service center, and date. Each table included the following columns:

•	Number of calls: Sum of calls received by the customer service team in a given day.

•	Call type: The type of problem or issue that the customer reported. There were five problem types: Account Management, Technician Troubleshooting, Scheduling, Construction and Internet & Wifi 

•	Service Center: The center where the customer called. There were service centers: Centre_1, Centre_2, and Centre_3

•	Date: The date when the call was received.

## Data Wrangling Process:
Since the data provided were already cleaned, no missing values, outliers, duplicates, or errors were found. Using Tableau I combined the data from the three service centers into one reporting table. 

## Exploratory Data Analysis

In the phase I explored to understand the patterns and trends within the dataset to derive meaningful insights, I focused on various aspects such as the repeat call trend, the issue category that generates the highest number of calls, and the service center with the highest volume of repeat calls.

## Insights

I visualized the follow-up calls for the next 6 days after the first contact day with Card Chart, showing the volume and percentage of the total. Approximately 9% of the callers called back one day after the initial call, 5% called back 2 days after, and 3% called back after 6 days.


![Screenshot (102)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/3b18711c-1bb7-47ae-849c-49718eec361f)


Drilling down by service center, centre_1 support desk received 45,333 calls on the initial contact day and approximately 7% called back the next day on the same issue. centre_2 generated a total call of 4,389 on the initial contact day and 6% of the customers called back one day after on the same issue. centre_3 received 15,217 calls on the initial contact day and approximately 13% of the customer called back the next day on the same issue.

![Screenshot (103)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/cb17bf2c-0cfa-4f5c-ba23-397b422a4c90)


![Screenshot (104)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/90535312-f6bc-4350-8d32-be256d4325de)


![Screenshot (105)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/345be00f-3805-4341-a843-b30fcf07ca7b)



The complaint/Issue category was visualized using a Bar Chart, the analysis shows Technician Troubleshooting and Internet & Wifi issues generated the highest number of calls. The Construction issue category has the least volume.


![Screenshot (102)c](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/f283d6ec-3649-4c3b-b366-1b3b2cbee920)



Using a pie Chart, I analyzed the service centers by call volume, centre_1 generated approximately 70% of the total of calls, centre_3 generated 23%, and centre_2 generated just 7%. 


![Screenshot (102)a](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/76e0a9a5-1602-4ebf-af4d-4890ad63296b)


## Recommendation

•	Stakeholders need to consider employing more technicians and providing training for the team to reduce repetitive calls on the same issue.

•	It is recommended that the stakeholders invest in new technologies to optimize the internet & wifi service. This will increase customer satisfaction and loyalty.

•	More investigation is required on service centre_3, to know the reason for generating the highest percentage of repeat calls, despite receiving less service centre_1.

## Usage

This notebook contains the explanation and interpretation of the data

The Tableau link can be use to interact with data visual.
https://public.tableau.com/app/profile/abe.itunu/viz/CustomerComplaintsAnalysisGoogleFibreCaseStudy/Dashboard2
