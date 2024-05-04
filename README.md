# -Weather-forecast-Project
Write a server by using SpringBoot Java and integrate Weather API from Rapid API. On the basis of that integration, expose your RESTful APIs as follows with JSON response. Authentication Method: Header-based authentication with random client id and random client secret


# How to Run Project

1) Download the zip folder
2) Import Project in Tools(Eclips, STS).
3) Build the project
4) Run the Project
Run as-> Spring boot app

# output of 2 API
## API 1: Get the Weather forecast summary of Any city using API (RapidApiGetForecastSummaryByLocationName)
In the below picture geeting output for Forecast Summary By Location Name
![image](https://github.com/KondaShriya/Weather-API-from-Rapid-API/assets/99605851/a42c2167-eb80-4b9a-b151-347316f658ac)




## API 2: Get hourly Weather forecast details of Any city using API (RapidApiGetHourlyForecastByLocationName)

In the below picture geeting output for Hourly Forecast By Location Name
![image](https://github.com/KondaShriya/Weather-API-from-Rapid-API/assets/99605851/6cbc7670-0adc-4f1d-838e-71ffef56b2de)



follow the steps for output
1) step1: Use default issuer for access tocken {https://dev-64151434.okta.com/oauth2/default}
2) step2: For access tocke we need to set authorization header a) type-> basic Auth b) username-> Client ID c) password-> CLIENT SECRETS
3) d) in body we need to enter key and value
    After authorization header will be automatically generated when you send the request.


4)Access tocken
![227787690-243802b3-432b-41cc-9995-17437a3fcc87](https://user-images.githubusercontent.com/73180409/229243709-9fd45c59-25db-40a5-9a46-8e7739669784.png)

#   W e a t h e r - f o r e c a s t - A P I - f r o m - R a p i d - A P I 
 
 
