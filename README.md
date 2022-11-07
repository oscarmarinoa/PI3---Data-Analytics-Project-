# PI3---Data-Analytics-Project-
Machine learning project focused on 

## Procedure

1. Data extraction and load of datasets.
2. Data cleansing and transformation with python.
3. Machine learning model and hyperparameters. definition (sklearn).
4. Calculation of accuracy parameters.
5. Hyperparameters update.

## Dataset

The dataset for this project is formed by .

* Train.csv: Table containing information regarding to several properties in Colombia, their prices, locations, amenities among other characteristics. This is the data to train the machine learning model for defining the cheap or expensive tag.
* Test.csv: Table containing information for properties in Colombia, for which the definition of expensive or cheap classification will be predicted.

## 1. Data extraction and load of datasets:

In this first stage the files are openeded as Dataframes using the Pandas Library.

## 2. Data cleansing and transformation with python:

This stage is focused on handling the missing and null values of the data, identifying outliers, normalizing numerical variables, transforming categoral data in suitable information for the ML model and performing some feature engineering.

## 3. Machine learning model and hyperparameters:

After the data is ready to be used, we select the machine learning model based on the problem we are trying to solve and the characteristics of the data we are using.

This step and the following two are try and error stages, where the hyper parameters and machine learning models are continuosly change to improve the results obtained.

## 4. Calculation of accuracy parameters.

In order to review the effectiveness of our model for cataloguing the properties correctly, some metrics are calculated:
* Confussion matrix.
* Accuracy.
* Recall.

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
