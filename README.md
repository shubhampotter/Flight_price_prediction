# Flight_price_prediction 
![image](https://user-images.githubusercontent.com/92949677/209949800-db3b9bcd-8a57-44d4-a33b-f893762817e3.png)
![image](https://user-images.githubusercontent.com/92949677/209949620-88e9548b-4bb0-4038-a15b-d1c6bf30275a.png)
![image](https://user-images.githubusercontent.com/92949677/209949688-11c2cc99-2c71-4a7c-861c-7c04a04e9f4f.png)


# Introduction
Everybody knows that holidays always call for a much-needed vacation and finalizing the travel itinerary becomes a tedious task. With the worldwide growth of internet and E-commerce, commercial aviation industry has witnessed a tremendous growth and has become a regulated marketplace. [1] Hence, for Airline revenue management, different strategies like customer profiling, financial marketing, social factors are used for setting ticket fairs. It is often seen that airfares are low when tickets are booked months in advanced and then they rise when booked in urgency. [2]. But, number of days/hours until departure isn’t the only factor which decides flight fare, there are numerous other factors as well.

Because of this complex pricing model of aviation industry, customers find it very difficult to find a perfect and cheapest ticket deal. To solve this problem, Machine Learning and Deep Learning based several technologies and modals are developed and extensive research is also underway. 
In this project , we will all the steps required for price prediction of a flight.
## Business Problem
Company like Find Flight  predict fare of the flight for the customers , But the question is why?
For the Business Purpose the Airlines companies change price according to the seasons or time duration. They will increase the price when people travel more. Many people don’t know these things and fall into the trap of Airline company.
## Objective
The main objective of this project to determine ideal purchase time for flight ticket and help customer to predict future flight prices and plan their journey accordingly.
Company like Find Flight helps customer to find the flight according to their time , interest and budget. So, that customer don’t have to pay more .
## ABOUT DATASET
![image](https://user-images.githubusercontent.com/92949677/209947993-3cb9842d-3481-4533-8bf4-2d7e1f2a9a41.png)
## DATA STRUCTURE
![image](https://user-images.githubusercontent.com/92949677/209948219-ab066f1f-4da9-469e-b555-758a135d0d9d.png)
## Machine learning Models
Applying machine learning model is one of the most step in machine learning life cycle. There are many different types of machine learning algorithm that we can apply for our problem. We will look see some of the algorithm that we have applied for our problem:
                          
                          1. Linear Regression
                          2. Random Forest 
## Linear Regression                        
In simple linear regression there's only 1 independent and one dependent feature but as our dataset consists of the many independent features on which the worth may rely on, we are going to be using multiple linear regression which estimates relationship between two or more independent variables and one dependent variable. The multiple linear regression models are represented by:
                 y=m1x1+m2x2+m3x3+………………….+ mnxn+ C
                 
Where,
             
             y = the predicted value of the dependent variable 

             Xn= the independent variables 
             
             m= independent variables coefficients 
             
             C= y-intercept x
             
## Random Forest
Random Forest is an ensemble learning technique where training model uses multiple learning algorithms then combine individual results to urge a final predicted result. Under ensemble learning random forest falls into bagging category where random number of features and records will average value of the expected values if considered because the output of the random forest model.
## Results
We had used two algorithms to prepared our ML model i.e., Linear Regression and Random Forest. From these two, Random Forest gives us the most accurate predictions. Models' performance using a few metrics are given below: 

Linear Regression:       

                               MAE: 1989.475840451
                               MSE: 8584809.071996346
                               RMSE: 2929.98448323474
                               R2 SCORE:   0.6367799086465608
Random Forest:             
                            
                           MAE: 1159.0048059537398                        
                           MSE: 3920052.4057357092
                           RMSE: 1979.91222172492
                           R2 SCORE: 0.9147644476401898
                           
 ## CONCLUSION
 This project can result in saving money of inexperienced people by providing them the information related to trends of the flight prices and also give them a predicted value of the price which they use to decide whether to book ticket now or later. On working with different models, it was found out that Random Forest algorithm gives the highest accuracy in predicting the output.






















