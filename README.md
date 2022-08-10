# Investigate Business Hotel Using Data Visualization
It is very important for a company to always analyze its business performance. This repository represents my analysis of hotel business dataset. The purpose of this project is to analyze customer behaviors in hotel business such as average number of reservation made each month and cancellation rates based on various factors.
## Tools
I've used Python as programming language. I also have used Jupyter Lab as notebook, common libraries like Pandas and NumPy, and for visualization i've used Matplotlib and Seaborn. 

## Contents
### Data Preparation
* Dataset consist of 119390 rows and 29 features
* There were null values in 'children', 'city', 'agent', 'company' features
* Odd values in 'meal' feature
* Unecessary values which are 0 guests and 0 nights
* 33261 duplicated rows
* Unecessary data types
Dropping, imputations, changing data types and values were conducted for data preparation.
### Monthly Hotel Booking Analysis Based on Hotel Type
![image](https://user-images.githubusercontent.com/108931989/183958020-f05d642e-1923-40b2-a011-1a00f3326d05.png)
* There are 2 holiday seasons in Indonesia, which starts around June to July and November to December, even through January on the next year.
* By general, reservation for city hotel is higher than resort hotel.
* Both hotels receive more reservations for 1st Holiday Season while both receive less in the 1st quarter of the year.
* City hotel has decreased reservations in August and September.
* Resort hotel has a slight decreased reservations in November but receive more by December.
### Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rate
![image](https://user-images.githubusercontent.com/108931989/183958353-7162dfcd-b4f6-41df-810c-fd5b79a06722.png)
* Stay durations have a positive effect on the cancellation rate of reservations for both hotels.
* The longer stay duration, the higher the precentage of a reservation being canceled.
* For city hotel, the highest cancellation rate is around 4 weeks ++ stay duration, about 86.67%.
* As for resort hotel, the highest cancellation rate is around 3 weeks stay duration, about 35.07%
* Most reservations are made for around 1 weeks stay duration.
### Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate
* Lead time is the range of time from booking date to the actual / arrival date of reservations.
* Both hotel types have the lowest cancellation rate in around 1 month lead time duration, which around 19.67% for City Hotel, and 12.19% for Resort Hotel.
* Both hotel types also have the highest cancellation rate in around 11-12 months lead time duration. City Hotel at 60.67% and Resort Hotel at 38.99%.
## Summary
* City hotel has a higher number of reservations probably because it is common that resort hotel is more expensive. Furthermore, some resort hotels are located outside the city, while most of people probably choose to have a short vacation or staycation in nearby city or even in the same area.
* Both hotels receive more reservations for 1st Holiday Season while both receive less in the 1st quarter of the year.
* City hotel has decreased reservations in August and September due to the start of 2nd productive semester
* Resort hotel has a slight increase of reservations in December probably affected by Christmas Day and New Year’s Eve.
* The longer stay duration, the higher the percentage of reservation being canceled. This is probably due to the sudden schedule change of customers which may have an impact at the time when they have planned for how long they stay.
* Most reservations are made for around 1 week stay duration. This is probably due to most of people tend to choose a short vacation.
* Both hotels have the lowest cancellation rate in around 1 month lead time duration and also have the highest cancellation rate in around 11-12 months lead time duration. This also probably due to the sudden change in schedules which affect their free time, thus cancel the reservations.






