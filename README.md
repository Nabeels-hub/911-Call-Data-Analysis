# 911 Calls Analysis

## Overview:

This project analyzes 911 emergency call data to identify trends in emergency types, call volume, peak hours, and regional patterns. The analysis provides insights into emergency response patterns and helps optimize emergency services.

## Dataset:

The dataset contains emergency call details with the following fields:

lat: Latitude of the call location

lng: Longitude of the call location

desc: Description of the emergency call

zip: Zip code of the call location

title: Emergency call title, which includes the type of emergency

timeStamp: Date and time of the call (YYYY-MM-DD HH:MM:SS format)

twp: Township where the call was made

addr: Address of the call

e: Dummy variable (always 1)

## Visualizations:

911 Calls by Zip Code: Top 5 zip codes where most calls were made

911 Calls by Township: Top 5 townships with the most emergency calls

911 Calls by Emergency Type: Count of calls categorized by EMS, Fire, and Traffic

911 Calls by Day of the Week: Heatmap and countplot showing call frequency by day

911 Calls by Month: Monthly trend analysis using countplot and line charts

Peak Emergency Hours: Hourly breakdown of emergency calls with heatmaps and clustermaps

911 Calls Over Time: Line charts tracking daily call volumes for Traffic, Fire, and EMS emergencies

## Results:

Most Common Emergencies – EMS (48,877 calls) is the most frequent, followed by Traffic (35,695) and Fire (14,920).

Top Locations – Zip code 19401 (6,979 calls) and Lower Merion Township (8,443 calls) have the highest 911 call volumes.

Peak Hours – Most emergencies occur between 7 AM - 8 PM, peaking around noon.

Seasonal Trends – Calls rise in winter (Dec-Feb) and spike again in summer (May-July).

Day & Night Patterns – Fridays and Saturdays have the most calls, with EMS & Traffic emergencies peaking from 12 PM - 6 PM.

Emergency Type Trends – Traffic calls peak during rush hours, while Fire emergencies are more evenly spread throughout the day.
