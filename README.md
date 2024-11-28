# TravelAnalytics-Dashboard via MongoDB Atlas

## Acknowledgment
I would like to express my heartfelt gratitude to the following individuals and sources for their support and inspiration during this project:

Prof. Ashok K Harnal

I deeply appreciate the guidance and mentorship of Prof. Ashok K Harnal, whose insights significantly contributed to the successful completion of this project.

Dataset Source

The project utilizes a traveler-trip dataset, providing insights into demographic preferences, travel costs, and trends to design better travel packages and marketing strategies. (https://www.kaggle.com/datasets/rkiattisak/traveler-trip-data?resource=download)

## Introduction
This project leverages MongoDB Atlas to create a dynamic and insightful dashboard analyzing travel patterns and preferences. The dashboard reveals actionable insights about traveler demographics, destinations, accommodation, transportation, and costs, empowering travel companies to craft data-driven marketing strategies and tailored travel packages.

## Table Of Contents

1.) Project Overview

2.) Objectives

3.) Features and Dataset

4.) Dashboard Overview

5.) Business Insights

6.) Insights

7.) How to Install and Use

## Project Overview
The TravelAnalytics Dashboard is designed to provide travel companies with actionable insights into traveler behavior and preferences. Built on MongoDB Atlas, the project facilitates scalable storage and efficient analysis of diverse travel-related datasets, aiding in strategic decision-making and customer segmentation.

## Objectives

● Understand Destination Preferences: Identify popular travel destinations based on demographic factors, like gender, to tailor destination-specific promotions.
 
● Analyze Accommodation and Transportation Choices: Determine accommodation and transportation preferences to refine travel package offerings for diverse traveler needs.
 
● AssessTrip Duration Patterns: Examine how trip durations vary by destination and transportation mode to inform the design of short- and long-stay travel packages.

● Evaluate Cost Distribution by Destination: Analyze total travel costs across destinations to create budget-friendly and premium package options.

● Identify Key Traveler Demographics: Study the age and gender distribution of travelers to customize marketing efforts for different demographic groups.

## Features and Dataset
This dataset provides a basis for understanding travel preferences, cost patterns, and demographic trends, supporting the creation of targeted travel packages and marketing strategies.

Source: https://www.kaggle.com/datasets/rkiattisak/traveler-trip-data?resource=download

● Traveler Demographics: Information on traveler gender and age, allowing for analysis of demographic preferences in destinations, transportation, and accommodations.
 
● Destinations: Various travel destinations are represented, with data indicating their popularity and associated travel costs.
 
● Accommodation Details: Data on preferred accommodation types (e.g., hotels, budget stays, homestays) by destination, specifically highlighting preferences in destinations like Bali and Paris.
 
● Trip Duration: Information on trip length, which varies by destination and transportation mode, allows for insights into common travel durations for each location.
 
● Transportation Mode and Costs: Details on the types of transportation used (e.g., flights, trains, cars) with associated costs, including specific data for Indian travelers’ transportation spending.
 
● Travel Costs: Information on total travel costs and breakdowns, such as accommodation vs. transportation costs, helps identify cost distribution across destinations like London.
 
## Dashboard Overview
The dashboard, built on MongoDB Atlas, offers interactive visualizations.

![Traveler_trip_dataset](https://github.com/user-attachments/assets/a6729145-ba6e-46e0-907a-e64910d8f537)

The Traveler Trip Dataset Dashboard provides a detailed analysis of travel patterns, preferences, and costs across various destinations. It highlights destination popularity segmented by gender, accommodation preferences (e.g., Bali's dominance in resort stays), and average trip durations. Transportation mode usage, traveler demographics, and age distributions offer insights into traveler behavior, while charts on costs (total, transportation, and accommodation) across destinations such as Paris and London reveal spending trends and trade-offs. A word cloud visualizes the most visited locations, and a global map illustrates the geographical distribution of travelers. These insights are complemented by scatter and line plots analyzing relationships between trip durations, transportation types, and costs, making the dashboard a comprehensive tool for data-driven decision-making in travel and tourism.

Explore the live dashboard here: https://charts.mongodb.com/charts-project-0-trkgmus/public/dashboards/6d73b769-2d5c-4968-8938-9126313ee88e

## Business Insights

### Destination Popularity (As per Gender)

![Destination popularity](https://github.com/user-attachments/assets/429f4b1b-2b02-461a-b311-0f491bf08647)

Description: This bar chart shows the number of trips taken by males and females to various destinations like Rome, Bali, and Tokyo.

Insights: Destinations such as Bali and Paris are popular among both genders, while some destinations show gender-specific preferences. This could be useful for tailoring marketing campaigns by gender.

### Accommodation Type Preference (In Bali)

![Accommodation type preference](https://github.com/user-attachments/assets/eb47a6bb-18dc-4471-a9ed-5ab3a247e1f6)

Description: A pie chart illustrating the distribution of accommodation types in Bali, including resorts, villas, and hostels.

Insights: Resorts dominate with 58.3% preference, followed by villas at 25%. Hostels have a minimal share, indicating that travelers to Bali prefer comfort and luxury over budget options.

### Average Trip Duration (According to Destination)

![Average trip duration](https://github.com/user-attachments/assets/c1b3a8c7-ffa5-4158-ab18-a2117f9e13d3)

Description: A bar chart displaying the average number of days spent at each destination.

Insights: Destinations like Vancouver and Sydney have the longest average stays (10-13 days), while Bangkok and Phuket have shorter durations, likely indicating short getaways or budget constraints.

### Transportation Mode Usage (As per Gender)

![Transportation mode usage](https://github.com/user-attachments/assets/6287e8a8-ac32-44fc-a1ab-d11881cee6c7)

Description: A stacked bar chart showing the percentage of males and females using transportation modes like trains, airplanes, and buses.

Insights: Airplanes are the most used transportation mode by both genders, while modes like buses and ferries are less common. This indicates that most travelers prefer speed and convenience.

### Total Cost (By Destination)

![Total cost](https://github.com/user-attachments/assets/15a5667b-9ffb-489f-bfc6-ec38b6c9437f)

Description: A bar chart comparing the total costs (accommodation and transportation) for each destination.

Insights: Paris and Rome incur the highest total costs, while destinations like Phuket and Bangkok are more budget-friendly, reflecting their appeal to cost-conscious travelers.

### Average Transportation Cost (Spent by Indians)

![Average transportation cost](https://github.com/user-attachments/assets/58270e3d-a468-4307-8498-c359c4d721f5)

Description: A gauge chart showing the average transportation cost incurred by Indian travelers.

Insights: The average cost is $325, suggesting Indian travelers opt for moderate-cost options for transportation.

### Traveler Age Distribution (As per Gender)

![Traveler age distribution](https://github.com/user-attachments/assets/e609054a-73c8-400f-be08-5053f2fb3ecc)

Description: A bar chart showing the proportion of male and female travelers in different age groups.

Insights: Most travelers fall within the 20-40 age range, with fewer travelers above 50. This highlights the dominance of younger audiences in travel markets.

### Accommodation Cost vs. Duration (For Hotels in Paris)

![Accommodation cost VS duration](https://github.com/user-attachments/assets/789dd13d-476c-45a3-8a77-31f07531ccce)

Description: A scatter plot showing how accommodation costs in Paris vary with trip durations.

Insights: Costs increase linearly with duration, indicating predictable expenses for extended stays.

### Different Destinations (Word Cloud)

![Different destinations](https://github.com/user-attachments/assets/ec421e3b-de71-4a1f-af6f-0d12f8e3bd02)

Description: A word cloud of various travel destinations, with font size reflecting popularity.

Insights: Popular destinations like Rome, Tokyo, and Sydney stand out, emphasizing their global appeal.

### Trip Duration Distribution (As per Transportation Type)

![Trip duration distribution](https://github.com/user-attachments/assets/b9033b87-b2c4-4158-b576-614ce20220c5)

Description: A line chart showing the number of travelers and their trip durations for each transportation mode.

Insights: Airplane trips are associated with longer durations, while train journeys are shorter, reflecting the nature of intercity or international travel.

### Number of Travelers to Each Destination (Geographical Map)

![No  of travelers to each destination](https://github.com/user-attachments/assets/9d4ab8dd-a537-4638-a889-81a4e8d08e68)

Description: A global map illustrating the volume of travelers across various destinations.

Insights: Major travel hubs like Paris, London, and Tokyo attract significant numbers of travelers, indicating their strong tourism infrastructure and appeal.

### Accommodation Cost vs. Transportation Cost (For Destination - London)

![Accommodation cost VS Transportation cost](https://github.com/user-attachments/assets/dcd4c288-28d9-4464-ad27-b6c63548d029)

Description: A line chart comparing accommodation and transportation costs in London.

Insights: Higher transportation costs are associated with lower accommodation expenses, suggesting budget trade-offs made by travelers.

## Insights

● Certain destinations appeal more to specific demographics (e.g., Bali may attract more females), allowing targeted marketing to boost travel interest among these groups.

● Accommodation Preferences: Preferences for accommodation types vary, with budget stays or homestays often favored in specific destinations, indicating a trend towards affordable and immersive travel experiences.

● CostTrends by Destination: Expensive destinations like Paris attract premium travelers, while budget-friendly spots like Bangkok appeal to cost-conscious
 travelers, guiding pricing and promotion strategies.
 
● Trip Duration and Transportation: Shorter trips align with air travel, while longer trips suit trains or cars, suggesting package themes based on quick getaways or leisurely journeys.

● Traveler Demographics: Younger age groups often prefer adventurous or budget-friendly options, while older travelers might favor comfort, guiding the focus of experience-based packages for each group.

## How to Install and Use

Install MongoDB Atlas

Create an account on MongoDB Atlas: MongoDB Atlas

Set up a cluster and import the dataset.

Install MongoDB Compass

Download MongoDB Compass: MongoDB Compass

Connect to your cluster and explore the dataset.

Configure the Dashboard

Open MongoDB Atlas Charts and create a dashboard.

Build visualizations using the dataset's features.

Publish the dashboard and share insights with stakeholders.
