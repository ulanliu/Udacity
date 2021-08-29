# Bike Sharing System Data exploration
## by Peter Liu


## Dataset

This dataset containing renting time, information of bike stations and renters for approximately 180,000 
renting data, and I transform some data types into appropriate data types.  

## Summary of Findings  

1. Most renting activities are occured in 7am-9am and 4pm-6pm of weekdays which is rush hour in San Francisco.  

2. The population of renters consist mainly of male subscribers which born between 1980 to 2000.  

3. The renting number of non-subscriber group hold steady in each day of week; the subscribers tend to rent 
bikes in weekday than weekend.  

4. The duration time of non-subscribers is two times as longer as subscribers' duration time and the standard 
deviation of non-subscribers' duration time is larger than subscribers' standard deviation in every time 
section. It may means that subscribers have consistent reason to rent bikes, for example, they want to rent a 
bike for commuting on weekday. However, the non-subscribers may just rent bikes for exercise or just travel 
around the city which will take more time.  

## Key Insights for Presentation

For the presentation, I focus on the time section that takes most trips and the composition of renters.
I start by the distribution of start_time, divided by day and hour, and then plot the barplot. To demonstare 
the time section which contains the most data.

Afterwards, I introduce the features of renters' information one by one. In each variable, I create three 
plot, one is the overall compisition, and the other are the compisition of rush hours. However, with these 
three variables, I can not see the big difference between three groups. In the end, I use pie chart to 
demonstrate the main gorup of bike sharing system.
  
### Resource 
1. https://stackoverflow.com/
2. Exploratory Data Analysis with Python - O’Reilly