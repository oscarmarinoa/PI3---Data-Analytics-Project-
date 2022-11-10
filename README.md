# PI3---Data-Analytics-Project-
Data analysis project focusing on understanding the key factors that produced flight crashes from 1909 to 2021. This project corresponds to the thirdd individual project of the Data Science career of Henry cohort 04 (DS04)
 
## Procedure

1. Data extraction and load of datasets.
2. Data cleansing and transformation with python.
3. String data in SQL server.
4. Data analysis.
5. Preparation of a dashboard.

## Dataset

The dataset for this project is formed by .

* Accidentesaviones.csv: Table containing information regarding flight accidents for a time frame over 100 years.
* 

## Features description.

In the repository files you will find a qualityreport.docx where a whole section is dedicated to giving detailed information on the features.

Column			Description
date			Date of the accident.
time			Time of the accident.
time_of_day		Time of the day in which the accident happened.
crash_site		Location of the accident.
country			Country of the accident
continent		Continent of the accident
latitude		Latitude of the accident.
longitude		Longitude of the accident.
operator		Airline or operator of the aircraft.
Flight_type		Type of flight
Flight_no		Flight number assigned by the aircraft operator.
route_flight_type	Complete or partial route flown prior to the accident.
ac_type			Aircraft type.
registration		ICAO registration of the aircraft.
cn_ln			Construction or serial number / Line or fuselage number.
people_on_board		Total people aboard.
crew_aboard		Crew aboard.
passengers_on_board	Passengers aboard.
fatalities		Total fatalities.
crew_fatalities		Crew fatalities.
passenger_fatalities	Passengers’ fatalities.
ground			Total killed on the ground.
summary			Description of the accident and cause if known.


## 1. Data extraction and load of datasets:

In this first stage the files are openeded as Dataframes using the Pandas Library.

## 2. Data cleansing and transformation with python:

This stage is focused on handling the missing and null values of the data, identifying outliers, normalizing numerical variables, transforming categoral data in suitable information for the ML model and performing some feature engineering.

## 3. String data in SQL server:

After the data is ready to be used, we select the machine learning model based on the problem we are trying to solve and the characteristics of the data we are using.

This step and the following two are try and error stages, where the hyper parameters and machine learning models are continuosly change to improve the results obtained.

## 4. Data analysis:

In order to review the effectiveness of our model for cataloguing the properties correctly, some metrics are calculated:
* Confussion matrix.
* Accuracy.
* Recall.

## 5. Preparation of a dashboard.

In this specific project, the performace of the model will be based on how well it can identify expensive properties using the recall:

--> Formula: Recall=TP/TP+FN

where:
TP: True positive.
FN: False negative.

## 5. Hyperparameters update: 

An ongoing update of the data is performed to improve the results obtaining, repeting the stages 3, 4 and 5, until securing relevant results.


## --> About the repository
You will find the following files:
* Train Script.ipynb: A Jupiter notebook file containing all the cleansing and transformation executed to the train file.
* Test Script.ipynb: A Jupiter notebook file containing the same cleansing and transformation for the test file.
* models.ipynb: A Jupiter notebook file with the models proposed and their performanca metrics. 
* oscarmarinoa.csv: A file with the predictions for the properties.
* test_corrected.csv: A file with the train data corrected, used for training the machine learning models.
* test_corrected.csv: The test data corrected, used for predictions of tags.
* Pipeline.ipynb: A short basic pipeline created for the project.
* Train_pipeline: File for running the pipeline.
* data_standardized_pipeline: File for running the pipeline.

## --> Information to highlight
* [Geopy documentation](https://geopy.readthedocs.io/en/stable/)
* [Regular Expression Operation Module - RE](https://docs.python.org/3/library/re.html)
* [numpy.isnan()](https://numpy.org/doc/stable/reference/generated/numpy.isnan.html)

## --> Lesson learned
* In a correlation matrix you would expect NaN if the values used for the correlation do not vary.
   According to the formula:

	* cor(i,j) = cov(i,j)/[stdev(i)*stdev(j)]

  If the values of the ith or jth variable do not vary, then the respective standard deviation will be zero and so will the denominator of the fraction.

## Contact

Oscar Mario Mariño Arias: oscarmarinoa@gmail.com 

[LinkedIn](https://www.linkedin.com/in/oscar-mariño-arias-774098112/)
