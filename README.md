##Forecasting customer churn in a hotel chain  

# Description of the project

The customer of this study is the chain of hotels   

To attract customers, this hotel chain has added the ability to book a room without prepayment on its website 
However, if the client canceled the booking, then the company suffered losses  
The hotel staff could, for example, buy groceries for the arrival of the guest or simply not have time to find another client  

To solve this problem, you need to develop a system that predicts armor rejection  
If the model shows that the booking will be cancelled, then the client is asked to make a deposit  
The deposit is 80% of the cost of the room for one day and the cost of one-time cleaning  
The money will be debited from the client's account if he still cancels the reservation  

# Business metric and other data  

The main business metric for any hotel chain is its profit  
The profit of the hotel is the difference between the cost of the room for all nights and the cost of service:  
both during the preparation of the room and during the stay of the guest  

The hotel has several types of rooms  
Depending on the type of room, the cost is per night  
There are also cleaning costs. If the client rented a room for a long time, then they are cleaned every two days  

**Hotel room rates:**
- category A: per night - 1000, one-time service - 400  
- category B: per night - 800, one-time service - 350  
- category C: per night - 600, one-time service - 350  
- category D: per night - 550, one-time service - 150  
- category E: per night - 500, one-time service - 150  
- category F: per night - 450, one-time service - 150  
- category G: per night - 350, one-time service - 150  

he hotel's pricing policy uses seasonal coefficients: in spring and autumn, prices increase by 20%, in summer - by 40%  
The loss of the hotel in case of cancellation of the room reservation is the cost of one cleaning and one night, taking into account the seasonal factor  

A budget of 400,000 was allocated for the development of a forecasting system  
At the same time, it should be taken into account that the implementation of the model should pay off during the test period  
Development costs should be less than the revenue that the system will bring to the company.  
