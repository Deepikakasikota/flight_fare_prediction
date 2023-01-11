# Flight_fare_prediction:
I am going to predict the flight prices for different locations in India.

## Business Problems :–

Flight ticket prices can be something hard to guess. we have been provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities, using which we aim to build a model which predicts the prices of the flights using various input features.

## About datasets:-

We have 2 datasets here — training set and test set.

The training set contains the features, along with the prices of the flights. It contains 10683 records, 10 input features and 1 output column — ‘Price’.

The test set contains 2671 records and 10 input features. The output ‘Price’ column needs to be predicted in this set. We will use Regression techniques here, since the predicted output will be a continuous value.

Following is the features available in the dataset – Airline, Date_of_Journey, Source, Destination, Route, Dep_Time, Arrival_Time ,Duration, Total_Stops, Additional_Info, Price.

## All the Lifecycle In A Data Science Project is divided into four parts:

1. Exploratory Data Analysis
2. Feature Engineering
3. Feature selection
4. Model Deployment

## Model Deployment (AWS Ec2):-

- First I create an ec2 instance. At that I provide all the information like adding security group and create a new key pair like that.
- Next I uploaded all the requird files into 'winscp' server. It is used to connect the local server with ec2 instance.
- After that I download all the required libraries on 'putty gen'.
- Before that we have to update with sudo.Once the downlooad complete run the app.py file, it will start running.
- Then go to ec2 instance and copy the generated url..for me it was (http://ec2-13-230-232-117.ap-northeast-1.compute.amazonaws.com:8080).

(![Screenshot (6)](https://user-images.githubusercontent.com/103427929/211822044-60258031-e2ea-431d-ab00-db92f393bd06.png)


