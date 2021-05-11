# CIS4400-Project

The ETL(Extract, Transform, Load) documentation will provide a guide on how to extract data, transform data based on the project's requirements and finally load it into the the MySQL database.

The Analysis documentation will provide that the analysis of NYC Listings.

## Installation:
1. Install Anaconda Navigator- Jupyter Notebook onto your operating system:
https://docs.anaconda.com/anaconda/install/

2. Install MySQL on your pc. The link is for installation page for MySQL. Please read the following documets how to install and set MySQL on your pc.

[MySQL Download page](https://dev.mysql.com/downloads/mysql/)
[MySQL Local Environment Setup (Windows)](https://progate.com/docs/mysql-env-win)
[MySQL Local Environment Setup (MacOS)](https://progate.com/docs/mysql-env)


## [ETL](https://github.com/soichiromiyawaki/CIS4400-Project/blob/main/ETL.ipynb)
### Extract Data
We manually import datasets from two different websites.
1. [Airbnb Open Data in NYC - listing_detail](https://www.kaggle.com/peterzhou/airbnb-open-data-in-nyc?select=listings_detail.csv&fbclid=IwAR0pT11vw9LLVOodCrUePTaUl4Pf7yQOKHupieUPm11S8qkLYE_m1PgEgX4)
2. [NYC_ZIP_BOROUGH_NEIGHBORHOODS_POP](https://data.beta.nyc/en/dataset/pediacities-nyc-neighborhoods/resource/7caac650-d082-4aea-9f9b-3681d568e8a5?fbclid=IwAR2RCw0awQgGTPn3wvDN6TzSDCiTB1QiSy68jNjK4_2Jj3yNylDZ9xc1DTM)

### Transform Data
1. Drop listing information that has Null data
2. Remove unnecessary characters - i.g. "$", ","
3. Convert correct datatypes
4. Adjust Zipcode
5. Create necessary columns 

### Load Data
Load the transformed data into MySQL tables by Python Code.

## [Analysis for NYC Listings](https://github.com/soichiromiyawaki/CIS4400-Project/blob/main/Analysis.ipynb)
We analyzed the listing data.

## Question 
If you have any questions, please email us.

- mehdi.emon@baruchmail.cuny.edu
- saqif.ahmed@baruchmail.cuny.edu
- soichiro.miyazaki@baruchmail.cuny.edu
- steven.smith@baruchmail.cuny.edu
