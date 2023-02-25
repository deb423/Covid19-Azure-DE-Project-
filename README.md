
# Use Case 
GM is one of the leading heavy vehicle manufacture company. To improve their service they are planning to rollout new features based on IOT.

They have a tied up with a third party. Third party gives them a device which GM plugs into their cars and other vehicles. The device has the capability to capture the temperature (inside and outside temperature), speed , vehicle turbulence. These telemetry data (in JSON format) will be send to AWS cloud. 

The requirement is:
 i. To move the data from AWS to GM’s Azure cloud
ii. Data validation- if the data is in proper JSON format
iii. Once the JSOn gets validated the would be stored in SQL database which will be utilized by the Data Science team for analysis.

# Architecture Diagram for this project 

![image](https://user-images.githubusercontent.com/108168020/221332517-73f005c9-e12f-4dcd-b601-2f452866b0e9.png)
