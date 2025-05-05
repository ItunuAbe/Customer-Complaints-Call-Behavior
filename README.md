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

To uncover patterns and operational pain points within the dataset, I conducted a detailed exploratory analysis focusing on call volume trends, repeat call behavior, issue categories, and service center performance.

## Key Areas Explored

#### Repeat Call Trends
Using a card chart, I analyzed follow-up calls within 6 days of the initial contact. The data revealed that:

9% of customers placed a repeat call the very next day

5% followed up after 2 days

3% returned after 6 days

These trends suggest a significant portion of customers require follow-up, particularly within the first day, indicating potential issues with first-call resolution.


![Screenshot (102)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/3b18711c-1bb7-47ae-849c-49718eec361f)

#### Service Center Comparison
Drilling down by service center:

Centre_1 handled the highest volume, receiving 45,333 calls on initial contact days, with a 7% repeat rate

Centre_2 recorded 4,389 calls, with 6% repeating the next day

Centre_3 received 15,217 calls, with a concerning 13% repeat rate—the highest among the three.

This indicates that Centre_3 may benefit from deeper quality assurance reviews or resource reallocation. Also, The higher follow-up rate warrants further investigation into their processes or the types of issues they handle.



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
