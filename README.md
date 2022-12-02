# Ironhack Final Project: Flight Ticket Predictor



![image](https://user-images.githubusercontent.com/111467622/205284554-ccfeedf3-bbf9-49bd-8a53-d8d5a8cba69d.png)

# Business Questions

* How does the ticket price vary between Economy and Business class?
* Does price vary within Airlines?
* How the price changes when tickets are bought before departure?
* Does ticket price change based on the departure time and arrival time?
* How the price changes based on Source and Destination?
* Does the number of stops influences the price?


# Dataset
We've extracted our data from Kaggle.
Source: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction

# Prediction

After the EDA, I attempt to predict how much a flight ticket it's going to cost.


# Conclusions

* There is a big gap between flight tickets in business and economy. Business tickets are 6 times more expensive than economy tickets.
* The most expensive airlines appear to be Vistara and AirIndia, while AirAsia is the least expensive. There are just two airlines that provide business class tickets, Vistara and AirIndia, and Vistara is significantly more expensive.
* Prices generally increase gradually until 20 days prior to the flight, at which point they dramatically increase. However, there are frequently open seats that haven't been filled a day before takeoff. As a result, tickets can be found for three times less than the previous day.
* It appears that early morning and late night departures are less expensive, whereas evening departures are more expensive. It appears that early departure, late departure, and late departure are less expensive than night time departure.
* Flights to Chenai are slightly more expensive than those to other cities, but flights from Delhi are the least expensive overall.
* Generally, the cost of an airline ticket increases with the number of stops.
* The model that gives the best result is the Random Forest Regressor with a R2 Score:  0.989,  a Mean Squared Error of 5398550.098, a Mean Absolute Error of 888.23 and a Root Mean Squared Error of 2323.478

# Presentation

Tableau presentation is availabe on the following link: https://public.tableau.com/app/profile/clara6389



