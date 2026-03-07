# Airline Passenger Satisfaction Analysis
This project focuses on a machine learning classification task to analyze and predict customer satisfaction levels within the airline industry. The primary goal is to identify the key factors that drive customer satisfaction with airline services and suggest ways for the industry to enhance its service quality.

**Key Objectives**

* Determine the overall level of passenger satisfaction.
* Identify which services have a positive or negative influence on the quality of the airline's service.
* Develop a classification model to predict passenger satisfaction.

**Dataset Overview**
* The project utilizes a comprehensive dataset derived from an airline passenger satisfaction survey. The dataset contains 103,904 entries and 25 features covering various aspects of the passenger journey and demographics.



**Prediction Task (Classification)**
* The core machine learning problem is to predict the target variable, satisfaction, which is categorized into two classes:

* Satisfied

* Neutral or Dissatisfied

**Key Features Analyzed**
The analysis incorporates numerous factors rated on a scale of 0 (Not Rated) to 5 (Highly Satisfied), in addition to demographic and flight details:



Category,Key Features
Service Ratings,"Inflight wifi service, Online boarding, Seat comfort, Inflight entertainment, On-board service, Cleanliness"
Experience,"Ease of Online booking, Gate location, Baggage handling, Checkin service, Departure/Arrival time convenient"
Flight Details,"Flight Distance, Departure Delay in Minutes, Arrival Delay in Minutes"
Demographics,"Gender, Age, Customer Type, Type of Travel (Personal/Business), Class (Business, Eco, Eco Plus)"


**Results (Logistic Regression Model)**
The project utilized a Logistic Regression model for the classification task.


Model,Accuracy Score
Logistic Regression,,87.6%
