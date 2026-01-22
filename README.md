# Visualizing US Natural Disaster Declarations 
## Problem Statement
The rise in frequency and intensity of natural disasters has become a major challenge in the disaster preparedness and policy-making arena in the United States. Although there is an ample volume of unutilized raw data relating to natural disasters, this project aims at creating powerful visualization from the FEMA data related to disasters in the country, their trends and high risk regions.
## Data Set Description
The project is informed by four key datasets, each selected from authoritative government sources: FEMA and NOAA. These datasets collectively represent administrative declarations of disasters and scientific event-level observations for a move from mere counts to understanding the patterns, severity, and real-world impact of natural disasters in the United States.
### Disaster Declaration Dataset
This is the primary dataset of the project, as it contains official records of federally declared disasters in the United States. It is mainly used to analyze disaster frequency, affected regions, and government response.
#### Key Columns Used
* FEMA Declaration String, Disaster Number – these are the unique identification of each disaster
* Declaration Type, Declaration Title, Declaration Request Number – used for classification of disasters
* Declaration Date, FY Declared, Incident Begin & End Date, Disaster Closeout Date – used for time and duration analysis
* Incident Type, Designated Incident Types – represent nature of disasters
* IH, IA, PA, HM Programs – are the type of federal assistance provided
#### Usage and Key Metrics Analysis
* To calculate total disaster declarations and year-wise trends
* To identify disaster-prone states and regions
* To analyze disaster duration and assistance coverage
### Earthquake Dataset
This dataset provides event-level earthquake information and adds scientific depth to the project. It helps in understanding the severity and real-world impact of seismic events.
#### Key Columns Used
* Date, Time, Location Name – for timing and event identification
* Latitude, Longitude – for mapping earthquake epicenters
* Magnitude, MMI Intensity, Tsunami Indicator, VOL Indicator – for severity measurement
* Deaths, Damage (USD) – for impact assessment
#### Usage and Key Metrics Analysis
* To classify earthquakes based on severity
* To identify high-risk seismic zones
* To analyze the relationship between magnitude and damage
### Tsunami Dataset
The tsunami dataset focuses on coastal disaster events and captures both physical characteristics and impact
#### Key Columns Used
* Date of Occurrence, Time, Location Name – reflects the event timing and location
* Maximum Water Height, Number of Run-ups, Tsunami Magnitude, Tsunami Intensity – shows the physical severity
* Total Deaths, Total Damage (USD) – showing the human and economic impact
#### Usage and Key Metrics Analysis
* To identify high-intensity tsunami events
* To analyze coastal risk exposure
* To compare tsunami severity with impact
### Volcanic Eruption Dataset
This dataset captures volcano-related disaster declarations and focuses on officially recognized events and their duration.
#### Key Columns Used
* Declaration Title, Designated Area - represents the place of ccurance and the type of eruption
* Declaration Date, Incident Begin Date, Incident End Date - reflects the events timing based data
## KPIs (Key Performance Indicators)
## Dashboard Pages
## Key Insights
## Recommendation
## Tools Used
