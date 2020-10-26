# NYC Citibike Analysis :bike:
Link to Tableau Project: [link to dashboard](https://public.tableau.com/profile/alexandra.valentine#!/vizhome/Challenge13_CitibikeData/NYCCitibikeAnalysisStory?publish=yes "link to dashboard")
Analysis on bikeshare data using Tableau visualizations 

## Overview of the Citibike Analysis
The purpose of this analysis is to use Python and Tableau to create dynamic visualizations using Tableau. This analysis uses Citibike data from New York City riders for the month of August 2018. This data is fed into Tableau and made into various line charts and heat maps. 

## Results 
The below five visualizations were created in Tableau using the Citibike information. 

### 1. Checkout Time for Users: 

This discrete line chart illustrates the length of time that bikes are checked out. 
- The x axis represents the amount of time the bikes are checked out and the y axis represents the number of bikes during that time. 
- Our analysis shows that most bikes are checked out from 4 to 6 hours for all Citibike riders.

<img width="498" alt="checkout times for users" src="https://user-images.githubusercontent.com/67871338/97122639-b9857400-16fd-11eb-8a2f-9ea8c827e141.PNG"> 

### 2. Checkout Times by Gender: 

This discrete line chart illustrates the length of time that bikes are checked out for each gender. 
- The x axis represents the amount of time that the bikes are checked out and the y axis shows the number of bikes during that time. 
- The difference between this graph and the previous graph is that this one contains a gender formula - orange represents male, blue is female, and red is undisclosed gender. 
- Our analysis shows that in general, Citibikes are more used by men than women. 
- Women and Men both have highest bike usage from hour 4 to 6. 

<img width="493" alt="checkout times by gender" src="https://user-images.githubusercontent.com/67871338/97122642-bbe7ce00-16fd-11eb-8532-6b03f2fbf5b9.PNG">

### 3. Trips by Weekday Per Hour: 

This heat map illustrates the number of trips by weekday by hour. 
- The x axis shows the day of the week and the y axis illustrates the hour of the day. 
- The darker the color, the higher number of Citibike trips are active. 
- According to the heat map, the highest bike usage is from 7AM to 9AM and 5PM to 7PM during the week. Thursday at 6PM is the highest bike usage for the entire week at 44,905 trips. 
- This proves that most Citibike users ride to and from work during the week. On the weekend, bikes are used consistently throughout the day, further proving that most people ride bikes to and from work. 
- The lowest bike usage occured between 12AM and 5AM, proving to be the best time to repair the bikes and conduct any maintenance.

<img width="503" alt="trips by weekday per hour" src="https://user-images.githubusercontent.com/67871338/97122647-be4a2800-16fd-11eb-81aa-24cd8e21f686.PNG">

### 4. Trips by Gender (Weekday Per Hour)

This heat map illustrates the number of trips of the week by gender. 
- As shown with the Checkout Times by Gender, males use Citibikes more than females. 
- Males most frequently travel during the week between 8AM and 9AM and then at night from 5PM to 7PM. This means most men use Citibike to and from work. The highest number of riders is Thursday evening from 5PM to 7PM. 
- Women follow this pattern as well, with highest numbers from 7AM to 9AM and then from 5PM to 7PM. 
- Men also use Citibike more on the weekends than women.

<img width="496" alt="trips by gender (weekday per hour)" src="https://user-images.githubusercontent.com/67871338/97122650-c1451880-16fd-11eb-8d78-21a8f44b5867.PNG">

### 5. Trips by Gender by User Type: 

This heat map illustrates the number of trips by gender by client usertype. 
- In general, there is a much higher number of subscribers than one-off customers throughout the week. 
- Along with the rest of the data, there are more males as subscribers than females. 
- The highest bike usage occurs for male subscribers during Monday, Tuesday, Thursday and Friday. 

<img width="497" alt="trips by gender by user type" src="https://user-images.githubusercontent.com/67871338/97122652-c3a77280-16fd-11eb-9ac3-6860900c7caa.PNG"> 

## Summary of Citibike Analysis

In summary of the data, the following points can be made: 
- Most Citibike usage during the month of August 2018 occured during 7AM to 9AM and 5PM to 7PM - most likely to and from work. 
- Thursdays were the most popular day during the week for Citibike usage. 
- The lest amount of activity occured between 12AM and 5AM - proving the best times for renovations or reparations to the bikes and docks. 
- Men use Citibike significantly more often than women during the week and weekends. 

Two Additional Visualizations for Furture Analysis: 
- It would be useful to examine trip origins and destinations. This would help plan where to increase or decrease the supply of bikes to meet the demand. 
- Further examining user demographics like birth date could provide insights into specific bike usage. 
