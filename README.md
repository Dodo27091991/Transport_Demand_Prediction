<h2>Project Name - Transport Demand Prediction </h2>
<h3>Project Summary -</h3>
<br />
This challenge asks to build a model that predicts the number of seats that Mobiticket can expect to sell for each ride, i.e. for a specific route on a specific date and time. There are 14 routes in this dataset. All of the routes end in Nairobi and originate in towns to the North-West of Nairobi towards Lake Victoria.
<br />
The towns from which these routes originate are: Awendo

<ol> Homa Bay </ol>
<ol> Kehancha </ol>
<ol> Kendu Bay </ol>
<ol> Keroka </ol>
<ol> Keumbu </ol>
<ol> Kijauri </ol>
<ol> Kisii</ol>
<ol> Mbita</ol>
<ol> Migori</ol>
<ol> Ndhiwa</ol>
<ol> Nyachenge</ol>
<ol> Oyugis</ol>
<ol> Rodi</ol>
<ol> Rongo</ol>
<ol> Sirare</ol>
<ol> Sori</ol>

The routes from these 14 origins to the first stop in the outskirts of Nairobi takes approximately 8 to 9 hours from time of departure. From the first stop in the outskirts of Nairobi into the main bus terminal, where most passengers get off, in Central Business District, takes another 2 to 3 hours depending on traffic.

The three stops that all these routes make in Nairobi (in order) are: Kawangware: the first stop in the outskirts of Nairobi Westlands

Afya Centre: the main bus terminal where most passengers disembark All of these points are mapped here. Passengers of these bus (or shuttle) rides are affected by Nairobi traffic not only during their ride into the city, but from there they must continue their journey to their final destination in Nairobi wherever that may be. Traffic can act as a deterrent for those who have the option to avoid buses that arrive in Nairobi during peak traffic hours. On the other hand, traffic may be an indication for people’s movement patterns, reflecting business hours, cultural events, political events, and holidays.

Data Description Nairobi Transport Data.csv (zipped) is the dataset of tickets purchased from Mobiticket for the 14 routes from “up country” into Nairobi between 17 October 2017 and 20 April 2018. This dataset includes the variables: ride_id, seat_number, payment_method, payment_receipt, travel_date, travel_time, travel_from, travel_to, car_type, max_capacity.

Uber Movement traffic data can be accessed here. Data is available for Nairobi through June 2018. Uber Movement provided historic hourly travel time between any two points in Nairobi. Any tables that are extracted from the Uber Movement platform can be used in your model.

Variables description: ride_id: unique ID of a vehicle on a specific route on a specific day and time. seat_number: seat assigned to ticket

payment_method: method used by customer to purchase ticket from Mobiticket (cash or Mpesa)

payment_receipt: unique id number for ticket purchased from Mobiticket

travel_date: date of ride departure. (MM/DD/YYYY)

travel_time: scheduled departure time of ride. Rides generally depart on time. (hh:mm)

travel_from: town from which ride originated

travel_to: destination of ride. All rides are to Nairobi.

car_type: vehicle type (shuttle or bus)

max_capacity: number of seats on the vehicle

<h3>GitHub Link -</h3>
https://github.com/Dodo27091991/Transport_Demand_Prediction.git

<h3>Problem Statement </h3>
Data given is the information of ticket sold by the Mobiticket that are designated to Narirobi from 14 Location. Using this we'll need to make a model that will be able to predict the number of ticket sold by the Mobiticket for a perticular ride.

Since we've to find Number of ticket sold by the Mobiticket. We've not been given dependent variable in the data. In order to find the dependent variable we'll need to group the data

<h3>Objective :-</h3>
We'll be using the extensive feature engineering techinque and will be trying multiple model that will be able to predict the ticket sold by the Mobiticket in accurate manner.

<h3>Conclusion </h3>
<ol>In this project, we have used four different types of regression-based algorithms like Random Forest Regressor, Gradient Boosting Regressor, and XGBoost Regressor. We have tried Regularization and hyperparameter tuning to determine the best model.
</ol>
<ol> All of the models were able to give 100% accuracy but Random Forest and Decision Tree were able to give a MSE of 0.0. Hence Any of these two model can be used to accurately predict the ticket that will be sold by Mobiticket for a perticular ride.</ol>
