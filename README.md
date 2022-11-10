# PI3---Data-Analytics-Project-
Data analysis project focusing on understanding the key factors that produced flight crashes from 1909 to 2021. This project corresponds to the third individual project of the Data Science career of Henry cohort 04 (DS04)
 
## Procedure

1. Data extraction and load of datasets.
2. Exploratory Data Analysis.
3. Data to SQL server.
4. Data analysis.
5. Preparation of a dashboard and storytelling.

## Dataset

The dataset for this project is formed by:

* Accidentesaviones.csv: Table containing information regarding flight accidents for a time frame over 100 years.
* 

## Features description.

In the repository files you will find a qualityreport.docx where a whole section is dedicated to giving detailed information on the features.

* Column			          Description
* date			            Date of the accident.
* time			            Time of the accident.
* time_of_day		        Time of the day in which the accident happened.
* crash_site		        Location of the accident.
* country			          Country of the accident
* continent		          Continent of the accident
* latitude		          Latitude of the accident.
* longitude		          Longitude of the accident.
* operator		          Airline or operator of the aircraft.
* Flight_type		        Type of flight
* Flight_no		          Flight number assigned by the aircraft operator.
* route_flight_type	    Complete or partial route flown prior to the accident.
* ac_type			          Aircraft type.
* registration		      ICAO registration of the aircraft.
* cn_ln			            Construction or serial number / Line or fuselage number.
* people_on_board		    Total people aboard.
* crew_aboard		        Crew aboard.
* passengers_on_board	  Passengers aboard.
* fatalities		        Total fatalities.
* crew_fatalities		    Crew fatalities.
* passenger_fatalities	Passengers’ fatalities.
* ground			          Total killed on the ground.
* summary			          Description of the accident and cause if known.


## 1. Data extraction and load of datasets:

In this first stage the files are opened as Dataframes using the Pandas Library.

## 2. Exploratory Data Analysis:

This stage is focused on become acquainted with usually using statistics and visualizations, to start formulating testable hypothesis. Previously a transformation process is executed for handling null values, identifying outliers and normalizing numerical variables.
The following are results from applying an EDA:
* Maximize insight into a data set.
* Uncover underlying structure.
* Extract and transform important variables.
* Detect outliers and anomalies.
* Test underlying assumptions.


## 3. Data to SQL server:

After the data is ready to be used, we transfer it to a local database where can be used by Power BI users.

## 4. Data analysis:

This is the most important section of the project where we look for insights, trends and behaviors to understand the causes of the flight accidents.

## 5. Preparation of a dashboard and storytelling.

Developing a story that explain the reasons behind the flight crashes.


## --> About the repository
You will find the following files:
* Data_transformation.ipynb: A Jupiter notebook file containing all the cleansing and transformation executed to the train file.
* MySql_conection.ipynb: A Jupiter notebook file containing the code for transferring the dataframe to a SQL server.
* daashboard.pbix: Dashboard developed. 
* crashes_modify.csv: A file with the data cleaned and ready to be used.
* report.docx: Quality report explaining in detail the transformation process.
* test_corrected.csv: The test data corrected, used for predictions of tags.

## --> Information to highlight
* [Geopy documentation](https://geopy.readthedocs.io/en/stable/)
* [Regular Expression Operation Module - RE](https://docs.python.org/3/library/re.html)

## Contact

Oscar Mario Mariño Arias: oscarmarinoa@gmail.com 

[LinkedIn](https://www.linkedin.com/in/oscar-mariño-arias-774098112/)
