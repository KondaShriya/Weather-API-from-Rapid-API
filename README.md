-Weather-forecast-Project


Write a server by using SpringBoot Java and integrate Weather API from Rapid API. On the basis of that integration, expose your RESTful APIs as follows with JSON response. Authentication Method: Header-based authentication with random client id and random client secret


How to Run a Project

1) Download the zip folder
2) Import Project in Tools(Eclips, STS).
3) Build the project
4) Run the Project
Run as-> Spring boot app

output of 2 API

API 1: Get the Weather forecast summary of Any city using API (RapidApiGetForecastSummaryByLocationName)
In the below picture getting output for Forecast Summary By Location Name
![image](https://github.com/KondaShriya/Weather-API-from-Rapid-API/assets/99605851/19d93634-3135-402c-b487-0f4d351f0f7f)




## API 2: Get hourly Weather forecast details of Any city using API (RapidApiGetHourlyForecastByLocationName)

In the below picture getting output for Hourly Forecast By Location Name
![image](https://github.com/KondaShriya/Weather-API-from-Rapid-API/assets/99605851/c4ac533e-13c6-4090-8ec8-409d944ba610)



follow the steps for output
1) step1: Use default issuer for access tocken {https://dev-64151434.okta.com/oauth2/default}
2) step2: For access token we need to set authorization header a) type-> basic Auth b) username-> Client ID c) password-> CLIENT SECRETS
3) d) in the body we need to enter the key and value
    After authorization header will be automatically generated when you send the request.


4)Access token
![image](https://github.com/KondaShriya/Weather-API-from-Rapid-API/assets/99605851/a058d0dc-1ce2-4278-8e45-45d9eb78aa83)


#   W e a t h e r - f o r e c a s t - A P I - f r o m - R a p i d - A P I 
 
 
