# Vehicle_Part_Calim_Analysis_Model 
# For Dataset visit on My Kaggle Account : https://www.kaggle.com/sahilprajapati143
This is a vehicle industry the i need to analyse the total claimed part by which city more with this analysis it can help company to make availability of vehicle parts that users claim on their city .
#requirement :
On the sale of the vehicle company provides one year base warranty on its parts and also provides optional one year extended warranty on additional cost. If the customer has not opted for the extended warranty option then after the one year in case of any failure of any part, the warranty is said to be expired and all the expenses has to be incurred by the customer itself and company will not take any responsibility for the same.
On the other hand, if the vehicle is secured by extended warranty assurance, then after the one year from the sale i.e. after the base warranty period, if any failure happens then the affected part/parts is/are either repaired or replaced under the warranty terms of the company and all the expenses will be done by the company.
USE CASES:
1) Monthly report of top ten Dealers and parts that has been failed:
- We need to generate the list of top ten dealers that are processing the extended warranty of parts and also need to find out the most frequent part’s which are reported as a defective.
- The list of top ten dealers helps the company to analyze and understand the performances of dealers.
- Monthly report of top ten failed parts helps the company to understand following:
a) Quality of the parts
b) Pattern of failure
c) Mostly reported failed part in the quarter/year
- Data visualization libraries like seaborn and matplotlib are used to visualize the data.
2) Predict the parts that may fail according to the location, mileage and age:
- In this case, by analyzing the historical data, we need to predict the parts that can be expected to fail according to the age, km driven and location of the vehicle.
- This data helps the company to understand the manufacturing requirements of the part i.e. which part is to be manufactured in what quantity so as to avoid unavailability of the parts when claim is raised for that part.
3) To determine whether the defective part is to be replaced or repaired:
- The model was developed to decide whether the failed part has to be repaired or replaced with the new one.
- For this, we had the last claimed data of the company.
- As this is the binary classification problem, Decision tree and Random Forest algorithms are used to build the model.
4) Customer Retention Model:
- This model helps the company to understand the service provided by the dealers is satisfactory or not.
- The model analyses the performance of the dealers by considering the customers feedback, churn rate of that location, preference to the other locations by the customers, change of base location etc.
- The model helps the company to take some regulatory decisions based the performance of dealer.
- It also helps the company to decide, whether to introduce new schemes, offers etc. to the affected location or to change the dealer.
5) Processing of variety of data:
- The data were coming from various locations like US, Canada, China, India in huge amount with varying data-types.
- It was required to club the data and then process it further for the analyzing.
- Processing large volume of data also caused memory issues which was then handled by memory management.


