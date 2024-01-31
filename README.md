# Analysis of murders in USA from 2015. to 2020.
Seminar workis written in Croatian.
In this document there will be star model and dashboards I made using MS Access and MS Power BI.

## Used dataset
Dataset was downloaded from Kaggle, from this link: https://www.kaggle.com/datasets/ahsen1330/us-police-shootings 

## Star model of warehouse
![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/47d9a6d6-beb2-4225-ac8c-e6a6382ff1f7)

## Creating of dimension tables
![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/f35ebf2e-3908-47f7-bd81-08747d6104a1)
The same principle is used for other tables.

## Creating of fact table
![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/e3b718f8-1d8c-4cda-be54-28b9e1715622)

## Dashboard
![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/330a4aa4-ac92-4b78-beb8-22e245043623)

A dashboard consists of the following elements:
• Line chart depicting the number of homicides per year
• Stacked bar chart illustrating the distribution of weapon categories possessed by the victim
• Pie chart showing the numbers and percentages of homicides based on races
• Number of homicides
Filters:
• Age – range from 12 to 91 years
• Gender – F for female and M for male
• Attempted escape – by car, on foot, did not attempt, other
• Signs of mental illness – yes or no
• Mode of death – shot or shocked with an electroshock device and shot
• Body camera – present or not

![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/6bc7233c-5e1f-43ed-9813-5f448fbfde45)

The filters applied include an age range from 12 to 91, only males, the victim did not attempt to escape, the victim showed signs of mental illness, the police officer did not have a body camera, and the victim was of the black race. According to this statistics, we can see that 188 individuals matching our criteria were killed. The majority of the victims had some type of firearms, and the highest number of such homicides occurred in 2018, totaling 47.

## Murder locations
![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/3e9361c8-5d00-4621-8bce-0e611f139dd1)

A map of the USA is displayed, showing the states where homicides occurred. A stacked bar chart depicts cities with the number of homicides per city, and the number of homicides changes depending on the selected city or state. The size of the circles on the map indicates the quantity of homicides per state. It can be observed that the highest number of homicides occurred in the city of Houston, totaling 230, while the state with the highest number of homicides is California with 1,054 murders.

## Date hierarchy dashboard
![image](https://github.com/petakantonio/DWH-and-BI/assets/126813875/7e7185de-efea-4272-ae70-1dea4bf9b774)

The highest number of homicides occurred in the month of May, totaling 757. The first quarter witnessed the highest number of homicides, reaching 2,110, while on the 29th day of the month, 436 homicides occurred, representing the highest daily count. Filters are provided next to the graphs, allowing the selection of a specific month, quarter, or day.

