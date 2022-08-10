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


