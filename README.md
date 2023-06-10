# Building an Azure Data Lake for Bike Share Data Analytics

## **Project Overview**

Divy is a bike sharing program in Chicago, Illinis USA that allows riders to purchase a pass at a kiosk or use a mobile application to unlock a bike at stations arount the city and use the bike for a specified amount of time. The bikes can be returned to the same station or to another station. The City of Chicago makes the anonymized bike trip data publicly available for project like this where we can analyze the data.

![image](https://user-images.githubusercontent.com/58150666/235313136-794785c9-5f99-488a-81e6-0e6ac300612a.png)


### The **Goal** of this project is to develop a data lake solution using Azure Databrikcs using a lake house architecture.

* `Design` a star schema based on the business outcomes listed below
* `Import` the data into Azure Databricks using Delta Lake to create a Bronze data store
* `Create` a gold data store in Delta Lake tables
* `Transform` the data into the star schema for a Gold data store

### **The buisness outcomes designed are as follows** :
1. Analyze how much time is spent per ride
    * Based on date and time factors such as day of week and time of day
    * Based on which station is the starting and / or ending station
    * Based on age of the rider at time fo the ride
    * Based on whether the rider is a memeber or casual rider
2. Analyze how much money is spent
    * Per month, quarter, year
    * Per member, based on the age of the rider at account start
3. EXTRA CREDIT - Analyze how much money is spent per member
    * Based on how many rides the rider averages per month
    * Based on how many minutes the rider spends on a bike per month

![image](https://github.com/Abdelrahman13-coder/Building-an-Azure-Data-Lake-for-Bike-Share-Data-Analytics/assets/58150666/8235515d-f356-4d72-9c8b-2d6e63d42ba3)


<img width="959" alt="image" src="https://github.com/Abdelrahman13-coder/Building-an-Azure-Data-Lake-for-Bike-Share-Data-Analytics/assets/58150666/cdcf5868-a19b-49bf-9ae9-1f72aa67a4bd">

<img width="957" alt="image" src="https://github.com/Abdelrahman13-coder/Building-an-Azure-Data-Lake-for-Bike-Share-Data-Analytics/assets/58150666/ab29d6fa-9b47-4248-9498-be634f319839">


<img width="960" alt="image" src="https://github.com/Abdelrahman13-coder/Building-an-Azure-Data-Lake-for-Bike-Share-Data-Analytics/assets/58150666/8dfe33d1-99fe-4f3c-9ac5-90f84e3c58de">

<img width="398" alt="image" src="https://github.com/Abdelrahman13-coder/Building-an-Azure-Data-Lake-for-Bike-Share-Data-Analytics/assets/58150666/f081baec-2774-4db3-80fd-4f051ef1ee28">

