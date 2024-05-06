# US Border Crossings
Visualizations and maps about border crossings towards the US (1995-2024)

The Bureau of Transportation Statistics (BTS) Border Crossing Data provide summary statistics for inbound crossings at the U.S.-Canada and the U.S.-Mexico border at the port level. Data are available for trucks, trains, containers, buses, personal vehicles, passengers, and pedestrians. Border crossing data are collected at ports of entry by U.S. Customs and Border Protection (CBP). The data reflect the number of vehicles, containers, passengers or pedestrians entering the United States.

In this project, we draw insights on the nature of border crossing through data visualization with time plots, barplots and maps. We also spatially compare crossings and mass shootings.

---

### Dataset ###
The dataset was provided by Sahir Maharaj on Kaggle and can be found at this link: https://www.kaggle.com/datasets/sahirmaharajj/border-crossing-dataset.
The variables described are: 
- Port Name: the name of the border crossing port
- State: the U.S. state where the port is located
- Port Code: a unique numerical identifier for the port
- Border: specifies which border, US-Mexico or US-Canada
- Date: the month and year when the crossing was recorded
- Measure: the type of crossing activity
- Value: the quantity of the crossing activity
- Latitude: the latitude coordinate of the port
- Longitude: the longitude coordinate of the port
- Point: a textual representation of the geographic point (latitude and longitude)
---

### Findings ###
The project reveals that there are overall more crossings on the US-Canada border than on the US-Mexican border. However, the overall value (people crossing) is higher on the Mexican border, all year round, across all years. The value of crossing tends to increase on the Canadian border during summer months.
Furthermore, regarding the measure by which people cross the border, the value of crossings by personal vehicle passengers, personal vehicles and pedestrians has decreased over time. However, the value of trucks and truck containers has slowly, but steadily increased, with no exception for the pandemic years. Overall, during summer, the number of people transported on personal vehicles increases. This is in particular due to the value of crossings on the border with Canada. In recent years (since 2010), the value of crossings have decreased, escpecially on the Mexican border; however, crossings have started to decrease in 2016. 
For what concerns distribution, overall, crossings on the Mexican border are less frequent, but they have a higher value than crossings on the Canadian border.

Comparing the number of crossings and their value with the spatial distibution of mass shootings, no peculiar correlation arises, neither in the severity of the shootings, nor in their overall distribution.

