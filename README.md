# Travel Package Purchase Prediction

# Context
I am a Data Scientist for a tourism company named "Visit with us". The Policy Maker of the company wants to enable and establish a viable business model to expand the customer base. A viable business model is a central concept that helps us to understand the existing ways of doing the business and how to change the ways for the benefit of the tourism sector.

One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, it was difficult to identify the potential customers because customers were contacted at random without looking at the available information.

The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. This time company wants to harness the available data of existing and potential customers to target the right customers.

As a Data Scientist at "Visit with us" travel company, I have to analyze the customers' data and information to provide recommendations to the Policy Maker and build a model to predict the potential customer who is going to purchase the newly introduced travel package. The model will be built to make predictions before a customer is contacted.

# Objective
To build a model to predict which customer is potentially going to purchase the newly introduced travel package.

# Data Description
CustomerID: Unique customer ID <br>
ProdTaken: Whether the customer has purchased a package or not (0: No, 1: Yes) <br>
Age: Age of customer <br>
TypeofContact: How customer was contacted (Company Invited or Self Inquiry) <br>
CityTier: City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. Tier 1 > Tier 2 > Tier 3. It's the city the customer lives in. <br>
DurationOfPitch: Duration of the pitch by a salesperson to the customer <br>
Occupation: Occupation of customer <br>
Gender: Gender of customer <br>
NumberOfPersonVisiting: Total number of persons planning to take the trip with the customer <br>
NumberOfFollowups: Total number of follow-ups has been done by the salesperson after the sales pitch <br>
ProductPitched: Product pitched by the salesperson <br>
PreferredPropertyStar: Preferred hotel property rating by customer <br>
MaritalStatus: Marital status of customer <br>
NumberOfTrips: Average number of trips in a year by customer <br>
Passport: The customer has a passport or not (0: No, 1: Yes) <br>
PitchSatisfactionScore: Sales pitch satisfaction score <br>
OwnCar: Whether the customers own a car or not (0: No, 1: Yes) <br>
NumberOfChildrenVisiting: Total number of children with age less than 5 planning to take the trip with the customer <br>
Designation: Designation of the customer in the current organization <br>
MonthlyIncome: Gross monthly income of the customer <br>
