# 311 Street Light Complaints vs. Car Crashes in NYC (Jan. 2019 - Dec. 2021)

**Context:**\
The data sets used for this project are the *311 Service Requests from 2010 to Present* filtered by Street Light Complaints and the *Motor Vehicle Collisions - Crashes*. Both data sets were sourced from NYC OpenData. Records used in this project are dated between January 2019 and December 2021.

The ETL was performed using Python, Socrata's OpenData API, and Google BigQuery's python connector packages and API. Data is hosted on Google BigQuery. Ad-hoc analysis and dashboarding were both performed using Tableau

**Objective:**\
Given the data sets that were selected for this project, try to answer the following questions:
- Which borough had the most crashes?
- Which borough saw the most fatalities related to car crashes?
- What were the most prevalent 311 complaints regarding street lights for every borough?

**Tools Used:**\
Python, Pandas, Google BigQuery, Socrata OpenData API, Tableau

**Data Source:**\
Links to the data sets (from NYC OpenData) can be found below. Data dictionaries for each respective data sets can be found via the links provided as well.
- 311 Service Requests from 2010 to Present: https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9
- Motor Vehicle Collisions - Crashes: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95

---

**Tableau Dashboard:**\
![311 Traffic Light Complaints and Car Crashes in NYC 2019-2021](https://user-images.githubusercontent.com/82073881/151912103-e0b331ad-9547-4dd5-9044-082b7ebdbaf1.png)
