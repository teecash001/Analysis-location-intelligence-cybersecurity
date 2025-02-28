# Analysis-location-intelligence-cybersecurity

## Table of  Contents
- [Introduction](#Introduction)
- [Objective](#Objective)
- [Data Source](#Data-Source)
- [Data Processing & Cleaning](#Data-Processing-&-Cleaning)
- [Question Guiding Our Analysis](#Question-Guiding-Our-Analysis)
- [Insights](#Insights)
- [Recommendations](#Recommendations)


# Introduction
###### The dataset provides insights into cybersecurity threats affecting IoT devices across various locations and infrastructure types. It includes geospatial data (latitude, longitude, and elevation), environmental factors (temperature, humidity, rainfall), infrastructure types, and cyberattack records on IoT devices. By analyzing this dataset, we can identify high-risk areas, potential correlations between environmental conditions and cyber threats, and strategies for improving cybersecurity.

# Objective:
###### The primary objective of this study is to analyze the relationship between location intelligence, environmental factors, and cybersecurity threats targeting IoT devices. The study aims to identify high-risk areas, understand attack patterns, and recommend effective cybersecurity measures based on geospatial and environmental data.

# Data Source:
###### The data was downloaded from Kaggle.com and was loaded into Excel.
###### It contains 16 columns and 10,000 rows.
###### The following are the information on the dataset used.
1.	User_ID
2.	Latitude
3.	Longitude
4.	Location type
5.	Elevation
6.	Population density 
7.	Temperature
8.	Humidity
9.	Rainfall
10.	Infrastructure type
11.	Air quality index
12.	Traffic flow
13.	Public transport station

14.	Cyber attack type
15.	IoT device category
16.	IoT device type 

# Data Processing and Cleaning
###### Loading  the data in Excel;
![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/picture%201.png)

 
  
  ###### The dataset contains 16 columns and 10,000 rows. The data look good.

1.	I used Removed duplicates to check for duplicates, the data did not contain duplicates.
![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/picture%202.png)
 



3.	I checked for blanks, the data did not contain blanks
![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/picture%202.png)



 


# Questions guiding our analysis:
1.	 Which locations are most vulnerable to cyber threats?
2.	 Are certain infrastructure types (e.g., bridges, hospitals, or gas stations) more prone to cyberattacks?
3.	Do temperature, humidity, or rainfall levels influence the frequency or type of cyberattacks?
4.	How does air quality relate to cyberattack occurrences on IoT devices?
5.	Which cyberattacks (e.g., ransomware, phishing, malware) are most common?
6.	What IoT device categories (e.g., smart home, smart city, healthcare) are most targeted?
7.	Are certain public transport hubs (bus stops, metro stations) more associated with cyber threats?


# Insights:
![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/new%20picture%20Q1.PNG)
1.	City Boundary, Road, Railway, Hospital, Gas station, Forest and River are the most locations vulnerable to cyber threats, follow by Social network data and Smartphone data who has the lowest cyber threats.





![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/Question%20P%202.png)
2.	Sewage system, Powerline, Dam and Bridge has more prone on cyberattacks then Wifi hotspot, Cell tower, Data center and Mobile tower.




![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/Question%20P%203.png)
3.	Temperature, Humidity, Rainfall levels has influence on the cyberattack type.

  



![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/Question%20P%204.png)
5.	Traffic sensor has the highest number of air quality on IOT devices, follow by Iot-connected Ecg, Smart street light, Environmental sensor, Smartwatch, Remote patient monitor, Medical sensor, Fitness tracker etc.





![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/Question%20P%205.png)
6.	Brute Force Attack is the most common cyberattack type, follow by Session Hijacking and Zero Day Exploit who are second most common cyberattack, follow by others.

  



![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/Question%20P%206.png)
7.	Smart City are most targeted IOT device, follow by Smart Home, Wearable and others.





![create table](https://github.com/teecash001/Analysis-location-intelligence-cybersecurity/blob/main/assets/images/Question%20P%207.png)
8.	Metro Station are more associate with cyber threats, follow by Bus station.





# Recommendations:
 1. Implement stronger security protocols for IoT devices in high-risk areas, especially in smart city, smart home and industrial IoT.                                              
 2. Deploy real-time monitoring for traffic sensors and smart city infrastructure to prevent cyber intrusions.
 3. Prioritize cybersecurity investments in hospitals, gas stations, and railway hubs with high cyberattack rates.
 4. Consider the impact of weather conditions on IoT security, implementing additional safeguards for extreme climates.
 5. Educate users on the risks of IoT cybersecurity in urban areas.





