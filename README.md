# Hotel Reservation Data Analysis Using Excel

## Table of Contents :
  - [Data Exploration]
  - [Descriptive Statistics]
  - [Room Type Analysis]
  - [Booking Channel Insights]
  - [Reservation Status Analysis]
  - [Rate Type Comparison]
  - [Property Perfomance]
  - [Advance Booking Analysis]
  - [Special Requests Impact]
  - [Conclusion]


 ## Data Exploration :
   
  #### Task
      1) Open the Excel sheet and explore the dataset’s structure (columns, data types).
      2) Check for missing values and handle them appropriately.


### Dataset Structure :

| Column Name            | Data Type   |                         
|------------------------|-------------|           
| Average Room Rate      | Numeric     |           
| Reservation_Id         | Text        |
| Check_In_Date          | Date        |
| stay_duration          | Numeric     |
| Adults                 | Numeric     |
| Children               | Numeric     |
| Room Type              | Text        |
| Special Request Flag   | Text        |
| Booking Channels       | Text        |
| Reservation Status     | Text        |
| Advance Booking        | Text        |
| Property               | Text        |
| Date                   | Date        |
| Rate Type              | Text        |

### Missing Values : 
  No missing values were found in any of the columns.


## Descriptive Statistics :

  #### Task 
     1) Calculate and summarize the basic descriptive statistics for the ‘Avg Room Rate’ column.
     2) Identify the maximum, minimum, mean, and median room rates.

   The basic descriptive statistics for the ‘Avg Room Rate’ column as show below :
   
|             |
| ----------- |
| ![Screenshot (37)](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/af5b9abb-31fa-456e-b459-98bd7824fe94) |

## Room Type Analysis :

  #### Task
      1) Analyze the distribution of room types (‘Room Type’ column).
      2) Determine the most and least popular room types based on the number of reservations.

  For Room Type Analysis here we have used of pivot table as show below : 
  
     - To determine the popularity of each room type, we counted the number of reservations for each type.
     - This helps in identifying the most and least popular room types based on customer preferences.
           1) Double Room Type is Most popular with 12936 reservations.
           2) Executive Suite is least popular room type with 4240 reservations.

|             |
| ----------- |
| ![H11](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/40dc428b-1a91-4430-aaeb-0bcdb712aa44) |


 ## Booking Channel Insights :

 #### Task

     1) Investigate the distribution of booking channels (‘Booking Channel’ column).
     2) Identify the most effective booking channel based on the number of completed reservations.

  A pivot table was created to break down the distribution of booking channel as illustrated here.

      - Here we determined the effectiveness of each booking channel by calculating the no. of completed reservations for each channel.
      - And analyzed the distribution to understand the proportion of reservations made through each booking channel.
          * Here are most 3 effectice channel with completion rate 
             1. Travel Agent: 90.61% of reservations completed 
             2. Website: 90% of reservations completed
             3. Phone App: 89.97% of reservations completed

|             |
| ----------- |
| ![H21](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/8be00fed-a04d-4d35-997a-e25ca51ce631) |

### Conclusion:

  The analysis reveals that while the **Phone App** is the most popular channel in terms of the total number of completed reservations, the **Travel Agent** channel is the most effective in terms of the completion rate. This suggests that reservations made through travel agents are more likely to be completed than those made through the phone app or website.
      

## Reservation Status Analysis :

#### Task 
      1) Explore the distribution of reservation statuses (‘Reservation Status’ column).
      2) Calculate the percentage of completed, no-show, and other reservation statuses.

The pivot table below was created to analyze and summarize the Reservation Status.
   - This analysis explores the distribution of reservation statuses and calculates the percentage of each status type, including completed reservations, no-shows, and other reservation statuses.


|             |
| ----------- |
| ![H31](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/c30f285b-2035-4660-9186-fc41c9869b07) |


### Conclusion:
  - This insights provide a clear understanding of the outcomes of reservations and can be useful for addressing issues like no-shows and optimizing overall reservation processes.


## Rate Type Comparison :

#### Task
    1) Compare the average room rates for weekday and weekend stays (‘Rate Type’ column).
    2)  Determine if there is a significant difference in rates between weekdays and weekends.

Using pivot table to analyze the rate type comparison 
  - This analysis looks into average room rates for weekday and weekend stays
  - The t-test was performed to determine if there is a statistically significant difference rates for weekdays and weekends.
       - T-test excel formula : T.Test(A2:A25001,A25002:A50000,2,2) 

#### Statistical Analysis:

  - t-Test Result (p-value): **0.761394**
   
       1) Significance Level: Typically, a significance level (alpha) of 0.05 is used.
       2) Comparison: The p-value (0.761394) is much greater than the significance level (0.05).

  
|             |
| ----------- |
| ![H41](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/c54645ba-0ba9-4794-86a5-ed78b25b2763) |

### Conclusion:
  1) Result: Since the p-value is greater than 0.05, we fail to reject the null hypothesis. This means there is not enough statistical evidence to suggest a significant difference between the average room rates for weekdays and weekends.   
 2) Final Summary: The analysis indicates that there is no statistically significant difference between the room rates for weekday and weekend stays. The average rates for both periods are similar, and the t-test confirms that any observed difference is likely due to random variation rather than a true difference in rates.


## Property Performance:

#### Task:
    1) Analyze the performance of different properties (‘Property’ column).
    2) Identify the property with the highest average room rate and the one with the most reservations.

 using Pivot table.
  - calculate the average room rate for each property and,
  - count the number of reservations for each property.


|             |                                                                                                                     
| ----------- |                                                                                                                     
| ![H41](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/c54645ba-0ba9-4794-86a5-ed78b25b2763) |      


### Conclusion:
   - Based on the analysis, "The Sankey" has the highest average room rate with $184.84 indicating it may be positioned as a premium property. "The Sankey" also has the most reservations counts with 27400, suggesting it is the most popular among customers. This information can help in strategic decision-making for pricing and marketing efforts to optimize revenue and occupancy rates.

    





    


  
 

 

  
   
   

  






    
