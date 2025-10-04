# Road-Accident-Analysis 


### Project Overview 

This data analysis projects is a systematic breakdown of road traffic accidents that occured within United Kindom between 1/1/2021 and 2/28/2022 to identify key performance indicators and provide technical insights. 

### Data Source

[Download_here](https://docs.google.com/spreadsheets/d/1UE8dpLhUe6AQ6PXYiLoLQ8VJM5FK-Yn9/edit?usp=drivesdk&ouid=104813495679773169446&rtpof=true&sd=true)

### Tools

- Microsoft Excel: Data formatting 
- Microsoft Power BI: Data cleaning, analysis and visualization


### Data formatting 

The following tasks were performed using Microsoft Excel:

- Data loading and inspection
- Formatting in preparation for the analysis.

### Data Cleaning 

The dataset was uploaded into the Power BI and then transformed using power query. Under Accident-severity column, "fetal" (a grammatical error) was changed to "fatal".

### Data Analysis and Visualization 
The data was analysed using Power BI. The objectives of the analysis was to find:
1. Total casualties and accident value for 2022 and YoY growth
2. Total casualties and accident severity for 2022 and YoY growth
3. Total Casualties with respect to vehicle type, road_type, light conditions (day/night), location (urban/rural), road surface conditions for 2022 Total Casualties.
4. Monthly trends showing comparison of casualties between 2022 ahd previous year.

The visualization was created as a dashboard titled "Data Accident Analysis"
Find [dashboard](https://github.com/AdeyilolaAyomide/Road-Accident-Analysis/blob/ae294bdee1adeada4cf6ee9a6f1214886ebd6a0c/Road%20accident%20dashboard.pdf)


### Results 

The results are as follows:

1. There were 195.7K casualties in 2022 which is 11.9% lesser than the previous year
2. There were 144.4k accidents in 2022 which is 11.7% lesser than the previous year
3. Casualties (percentage change compared to previous year): Fatal = 2.9k (-33.3%), Serious = 27.0k (-16.2%), Slight= 165.8k (-10.6%)
4. Casualties by vehicle type: Agricultural vehicle (399), Bus (6573), Car (155804), Motorcycle (15610), Van (15905), Others (1446).
5. Casualties by road_type: Single carriageway (145k), Dual carriageway(32k), Round about(13k), One way street (3k), slip road (3k)
6. Casualties by light conditions: Daylight (73.84%) Dark (26.16%)
7. Casualties by location: Urban (61.95%), Rural (38.05%)
8. Casualties by road surface conditions: Dry (132k), Wet/damp (50k), Frost/Ice (9k), Snow (4k), Flood over 3cm deep (<1k)
9. Month trend of casualties in 2022 and previous year shows that casualties are consistently highest in November compared to other months. Also shows that casualties are lesser in 2022 compared to previous year for all months except February where it was almost at the same level.

### Inferences/Recommendations

- There is 11.7% decrease in the number of accidents recorded in 2022 compared to previous year. This is a positive result which suggests that the interventions of relevant stakeholders in preventing road accidents are yielding positive outcome. Those interventions should be intensified.
- Cars are the main vehicle type involved in the accidents, and are responsible for over 70% of the casualties. More road traffic regulations should be targeted towards car use.
- There is a strong relationship between road type, light conditions (daylight/dark), location (urban/rural), road surface conditions and the number of casualties in 2022. Specifically, single carriageways, daylight, urban areas, and dry road surfaces each account for over 50% of the casualties recorded within their respective categories.Hence, these factors should be considered and stricter road traffic regulations targeted towards them.
- Both in 2021 and 2021, the month of November had highet record of casualties. This is suggestive of a seasonal influence in road traffic accidents. Relevant stakeholders should strategically implement more road safety measures during this season.
