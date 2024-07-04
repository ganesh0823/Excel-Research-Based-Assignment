# Hotel Reservation Data Analysis Using Excel

## Table of Contents :
   - [Project Overview](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#Project-Overview)
   - [Dataset](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#Dataset)
   - Task       
      - [Data Exploration](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#data-exploration)
      - [Descriptive Statistics](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#descriptive-statistics)
      - [Room Type Analysis](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#room-type-analysis)
      - [Booking Channel Insights](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#booking-channel-insights)
      - [Reservation Status Analysis](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#reservation-status-analysis)
      - [Rate Type Comparison](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#rate-type-comparision)
      - [Property Performance](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#property-performance)
      - [Advanced Booking Analysis](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#advance-booking-analysis)
      - [Special Requests Impact](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#special-request-impact)
   - [Recommendations](https://github.com/ganesh0823/Excel-Research-Based-Assignment/edit/main/README.md#recommendations)
           

## Project Overview : 
   In this project, we aim to analyze hotel reservation data to uncover patterns and perform various data analysis tasks to extract meaningful insights from the data.
#### Methodology:
   1) Using Excel, we will perform data cleaning, visualization, and analysis to extract meaningful insights from the dataset. 
   2) with the help of pivot table we will analyze all the dataset for descriptive analysis and comparative analysis.
   Key steps will include:
- Data Cleaning: Address missing values, correct data types, and standardize formats for consistency.
- Data Visualization: Create charts and graphs to visualize trends and patterns in the data.
- Descriptive Analysis: Calculate summary statistics to understand the distribution and central tendencies of various variables.
- Comparative Analysis: Compare completion rates between different groups (e.g., advanced bookings vs. regular bookings, reservations with vs. without special requests).


 ## 1) Data Exploration :
 #### Dataset : [Hotel Reservation](https://github.com/ganesh0823/Excel-Research-Based-Assignment/blob/main/Hospitality%20(1).xlsx)

   
  #### Task
      1) Open the Excel sheet and explore the dataset’s structure (columns, data types).
      2) Check for missing values and handle them appropriately.


#### Dataset Structure :

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
  The dataset was completely checked for missing values and there were no missing values found in the columns. This ensures the integrity of the data and allows for accurate analysis.

  
## 2) Descriptive Statistics :

  #### Task 
     1) Calculate and summarize the basic descriptive statistics for the ‘Avg Room Rate’ column.
     2) Identify the maximum, minimum, mean, and median room rates.

   The basic descriptive statistics for the ‘Avg Room Rate’ column as show below :
   
|             |
| ----------- |
| ![Screenshot (37)](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/af5b9abb-31fa-456e-b459-98bd7824fe94) |

  1) Mean (Average) Room Rate: This provides an overall measure of the central tendency of the room rates in the dataset.
  2) Median Room Rate: This measure is less affected by outliers and skewed data than the mean.
  3) Maximum Room Rate: This indicates the peak room rate charged.
  4) Minimum Room Rate: This indicates the lowest room rate charged.

## 3) Room Type Analysis :

  #### Task
      1) Analyze the distribution of room types (‘Room Type’ column).
      2) Determine the most and least popular room types based on the number of reservations.

For Room Type Analysis here we have used of pivot table as show below : 
|             |
| ----------- |
| ![H11](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/40dc428b-1a91-4430-aaeb-0bcdb712aa44) |
  
 - To determine the popularity of each room type, we counted the number of reservations for each type.
 - This helps in identifying the most and least popular room types based on customer preferences.
   
#### Conclusion : 
- Double rooms are the most preferred choice among guests, accounting for **12,936** reservations, highlighting their popularity and demand.
- Executive Suites, with **4,240** reservations, are less favored compared to other room types, indicating potential opportunities for targeted marketing or promotional strategies to increase their appeal to guests.


 ## 4) Booking Channel Insights :

 #### Task

     1) Investigate the distribution of booking channels (‘Booking Channel’ column).
     2) Identify the most effective booking channel based on the number of completed reservations.

With the help of pivot table we analyzed booking channel column.

|             |
| ----------- |
| ![H21](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/8be00fed-a04d-4d35-997a-e25ca51ce631) |

- Here we determined the effectiveness of each booking channel by calculating the no. of completed reservations for each channel.
- And analyzed the distribution to understand the proportion of reservations made through each booking channel.
   - Here are most 3 effective channel with completion rate 
      1. Travel Agent: 90.61% of reservations completed 
      2. Website: 90% of reservations completed
      3. Phone App: 89.97% of reservations completed
-  as shown above completion rate the analysis reveals that while the **Phone App** is the most popular channel in terms of the total number of completed reservations, the **Travel Agent** channel is the most effective in terms of the completion rate. This suggests that reservations made through travel agents are more likely to be completed than those made through the phone app or website.

### Conclusion : 
- After analyzing the data, it appears that **Phone App** has the highest number of completed reservations, indicating it as the most effective channel for booking hotel reservations. Understanding this can help focus marketing efforts and optimize resources towards channels that yield the highest booking conversions.
      

## 5) Reservation Status Analysis :

#### Task 
      1) Explore the distribution of reservation statuses (‘Reservation Status’ column).
      2) Calculate the percentage of completed, no-show, and other reservation statuses.

The pivot table below was created to analyze and summarize the Reservation Status.
  - This analysis explores the distribution of reservation statuses and calculates the percentage of each status type, including completed reservations, no-shows, and other reservation statuses.
 
|             |
| ----------- |
| ![H31](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/c30f285b-2035-4660-9186-fc41c9869b07) |

### Conclusion : 
- The majority of reservations, approximately 90.07%, are successfully completed, indicating a high level of reservation fulfillment.
- A significant but manageable 7.10% of reservations result in no-shows, highlighting a potential area for improvement in reservation management or guest communication.
- Understanding these percentages allows for targeted efforts to reduce no-shows and optimize reservation handling processes.


## 6) Rate Type Comparison :

#### Task
    1) Compare the average room rates for weekday and weekend stays (‘Rate Type’ column).
    2)  Determine if there is a significant difference in rates between weekdays and weekends.

Using pivot table to analyze the rate type comparison 

  
|             |
| ----------- |
| ![H41](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/c54645ba-0ba9-4794-86a5-ed78b25b2763) |

- This analysis looks into average room rates for weekday and weekend stays
  - The t-test was performed to determine if there is a statistically significant difference rates for weekdays and weekends.
       - T-test excel formula : T.Test(A2:A25001,A25002:A50000,2,2) 

#### Statistical Analysis:

  - T-Test Result (p-value): **0.761394**
   
       1) Significance Level: Typically, a significance level (alpha) of 0.05 is used.
       2) Comparison: The p-value (0.761394) is much greater than the significance level (0.05).

### Conclusion:
  1) Result: Since the p-value is greater than 0.05, we fail to reject the null hypothesis. This means there is not enough statistical evidence to suggest a significant difference between the average room rates for weekdays and weekends.   
 2) Final Summary: The analysis indicates that there is no statistically significant difference between the room rates for weekday and weekend stays. The average rates for both periods are similar, and the t-test confirms that any observed difference is likely due to random variation rather than a true difference in rates.


## 7) Property Performance:

#### Task:
    1) Analyze the performance of different properties (‘Property’ column).
    2) Identify the property with the highest average room rate and the one with the most reservations.

 Using Pivot table.
  - calculate the average room rate for each property and,
  - count the number of reservations for each property.

|             |
| ----------- |
| ![H54](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/f9fd173f-4ea7-4fc9-ab9f-2dace6305e2c) |
    

### Conclusion:
   - Based on the analysis, "The Sankey" has the highest average room rate with $184.84 indicating it may be positioned as a premium property.
   - "The Sankey" also has the most reservations counts with 27400, suggesting it is the most popular among customers.
   - This information can help in strategic decision-making for pricing and marketing efforts to optimize revenue and occupancy rates.

## 8) Advanced Booking Analysis :

#### Task : 
    1) Investigate the impact of advanced booking (‘Advanced Booking’ column) on reservation completion.
    2) Compare completion rates for reservations with and without special requests.

We used a pivot table to illustrate the advance booking distribution, as shown here.

  - Using this formula for completion rate
    
       1) Advance Booking (Yes) : =Completed / (Completed+No-Show+Extended+Reduced)
       2) Regular Booking (No) : =Completed / (Completed+No-Show+Extended+Reduced)

|             |
| ----------- |
| ![H56](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/07c45c59-e656-4ff6-b909-87d6e6e20512) |


### Conclusion : 

  - Advanced bookings have a slightly higher completion rate compared to regular bookings, with a difference of **0.74%.**
  - The higher completion rate for advanced bookings suggests that customers who book in advance are slightly more likely to complete their reservations compared to those who book closer to the reservation date.


## 9) Special Requests Impact :

  #### Task : 
        1) Analyze the impact of special requests (‘Special Requests Flag’ column) on reservation completion.
        2) Compare completion rates for reservations with and without special requests.

  With the help of pivot table  

  - Here we calculate count of reservation status on Special request.
  - for completion rate used above formula for reservations with and without special requests.
  

|             |
| ----------- |
| ![H58](https://github.com/ganesh0823/Excel-Research-Based-Assignment/assets/164488911/1be492f7-5d8d-49ba-aee4-6d5bb52e1633) |


### Conclusion : 

  - The slight difference in completion rates suggests that accommodating special requests does not significantly influence the likelihood of reservation completion.
  - This finding indicates that handling special requests should not be a major concern regarding the overall completion rate of reservations.


## Recommendations : 
   1) Since Double Rooms are the most popular, so ensure Double Rooms are consistently available and consider offering promotions or packages to capitalize on their popularity.
   2) Investments in channels that yield the highest completed reservation rates. Explore partnerships or promotional strategies to enhance visibility on these channels.
   3) To reduce no-show rates (7.10%), Implement proactive communication strategies to reduce no-shows, such as reminder emails or flexible cancellation policies.
   4) Adjust Weekday and Weekend rates based on demand patterns and seasonal variations to optimize occupancy and profitability.
   5) For the property with the highest average room rate, focus on enhancing guest experiences and amenities to justify premium pricing.
   6) Promote advanced bookings through incentives such as early booking discounts with Double room type reservations or exclusive offers.
   7) Offer personalized packages or upgrades for guests who make special requests, enhancing their experience and potentially increasing satisfaction and repeat bookings.

  

   


    





    


  
 

 

  
   
   

  






    
