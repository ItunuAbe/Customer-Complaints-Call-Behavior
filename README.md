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

## Key Areas Explored are:

### Repeat Call Trends

Using a card chart, I analyzed follow-up calls within 6 days of the initial contact. The data revealed that:

9% of customers placed a repeat call the very next day

5% followed up after 2 days

3% returned after 6 days

These trends suggest a significant portion of customers require follow-up, particularly within the first day, indicating potential issues with first-call resolution.


![Screenshot (102)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/3b18711c-1bb7-47ae-849c-49718eec361f)

### Service Center Comparison

Drilling down by service center:

Centre_1 handled the highest volume, receiving 45,333 calls on initial contact days, with a 7% repeat rate

Centre_2 recorded 4,389 calls, with 6% repeating the next day

Centre_3 received 15,217 calls, with a concerning 13% repeat rate—the highest among the three.

This indicates that Centre_3 may benefit from deeper quality assurance reviews or resource reallocation. Also, The higher follow-up rate warrants further investigation into their processes or the types of issues they handle.



![Screenshot (103)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/cb17bf2c-0cfa-4f5c-ba23-397b422a4c90)


![Screenshot (104)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/90535312-f6bc-4350-8d32-be256d4325de)


![Screenshot (105)](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/345be00f-3805-4341-a843-b30fcf07ca7b)

### Issue Category Breakdown

A bar chart visualization showed that:

Technician Troubleshooting and Internet & Wifi issues generated the highest number of calls, flagging them as critical areas for proactive resolution strategies.

Construction issues had the lowest call volume, suggesting fewer service complaints or less immediate urgency in that category.

Identifying Technician Troubleshooting and Internet & Wifi as high-volume, focusing on improving resolution processes for these categories could significantly reduce the overall call volume.

![Screenshot (102)c](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/f283d6ec-3649-4c3b-b366-1b3b2cbee920)



### Call Volume by Service Center

A pie chart comparison showed:

Centre_1 accounted for ~70% of total call volume

Centre_3 contributed 23%

Centre_2 managed only 7%, likely due to smaller coverage or staffing

The overwhelming volume at Centre_1 suggests the need to ensure adequate staffing and efficient processes at this location.

![Screenshot (102)a](https://github.com/ItunuAbe/Customer-Complaints-Call-Behavior/assets/110028869/76e0a9a5-1602-4ebf-af4d-4890ad63296b)

## Conclusion & Recommendation

The exploratory analysis of customer service call data from January to March 2022 uncovers critical insights into repeat call patterns, issue categories, and service center performance.

### Key findings include:

A notable volume of repeat calls occurs within the first few days after initial contact, with 9% of customers calling back the next day, indicating unresolved issues or follow-up needs.

Centre_3 recorded the highest percentage of repeat calls (13%), while Centre_1 handled the highest call volume overall, suggesting workload strain or inefficiencies.

Technician Troubleshooting and Internet & Wifi problems are the most reported issues, signaling areas where proactive solutions, improved knowledge bases, or technician support could significantly reduce customer friction.

Construction-related issues generated the least number of calls, indicating fewer concerns in infrastructure but possibly reflecting delayed reporting.

### Recommendations:

Implement a targeted quality assurance initiative for Centre_3 to investigate the causes of repeat calls and boost first-call resolution rates.

Prioritize proactive troubleshooting content or self-help resources for Internet & Wifi and Technician Troubleshooting categories.

Allocate additional support or training resources to Centre_1, which handles 70% of total call volume, to manage high demand more effectively.


## Tableau Link
This notebook contains the explanation and interpretation of the data and the link can be use to interact with data visual.
https://public.tableau.com/app/profile/abe.itunu/viz/CustomerComplaintsAnalysisGoogleFibreCaseStudy/Dashboard2
