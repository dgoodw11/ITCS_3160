# ITCS_3160

///////////////////////////////////////////////////////////////////////////////////////////////

Team 29:
Dakota Goodwin
  
///////////////////////////////////////////////////////////////////////////////////////////////
  
Project Description:
Insert a rating system for both the drivers and restaurants to the pre-exsiting database

///////////////////////////////////////////////////////////////////////////////////////////////

Narrative:

The purpose of this project is to implement a rating system for drivers and restaurants for the provided database. This added functionality allows for customers to leave a rating for both the driver and restaurant pertaining to their order they placed. This is an important feature because the use of rating systems is very common amoungst service-based applications which allows for users to give their input on how well a service was performed.

///////////////////////////////////////////////////////////////////////////////////////////////

Use Case for Rating System:

![rating-use-case.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/rating-use-case.png)

///////////////////////////////////////////////////////////////////////////////////////////////

Business Rules:

///////////////////////////////////////////////////////////////////////////////////////////////

EERD: 

![eerd.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/eerd.png)

///////////////////////////////////////////////////////////////////////////////////////////////

MySQL Queries:

/======================================================================/

SQL query that selects driver information, including their corresponding ratings:

![driver_ratings_select.PNG](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/driver_ratings_select.PNG)

/======================================================================/

SQL query that selects restaurant information, including their corresponding ratings:

![restaurant_ratings_select.PNG](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/restaurant_ratings_select.PNG)

/======================================================================/

Stored procedure for calculating the given driver rating:

![calc_driver_rating.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/calc_driver_rating.png)

/======================================================================/

Stored procedure for calculating the given restaurant rating:

![calc_restaurant_rating.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/calc_restaurant_rating.png)

////////////////////////////////////////////////////////////////////////////////////////////////

Advanced views:

/======================================================================/

View for order details (SQL and Return):

![order_details_view.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/order_details_view.png)
![order_details_return.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/order_details_return.png)

/======================================================================/

View for driver details (SQL and Return):

![driver_details_view.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/driver_details_view.png)
![driver_details_return.png](https://raw.githubusercontent.com/dgoodw11/ITCS_3160-052/main/images/driver_details_return.png)

/////////////////////////////////////////////////////////////////////////////////////////////////

MySQL Dump:
![sql_dump.sql](sql/sql_dump.sql)

/////////////////////////////////////////////////////////////////////////////////////////////////

PPT Video:
