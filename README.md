# <center> Human-Activity-Recognition

## Introduction
This dataset is taken from UCI's machine learning repository.
We are provided with sensory data from smartphone, now given this data our task is to predict the activity of a person.
This is a multi-class classification problem. We have 6 activities as our class labels, they are:
Walking, Sitting, Standing, Laying down, Walking upstairs and walking downstairs

## Data description

We will have a quick overview of the data

- Accelerometer and Gyroscope readings are taken from 30 volunteers(referred as subjects) while performing the following 6 Activities. Walking , Walkingupstairs , Walkingdownstairs , Standing , Sitting , Lying .
- Readings are divided into a window of 2.56 seconds with 50% overlapping.
- Accelerometer readings are divided into gravity acceleration and body acceleration readings, which has x,y and z components each.
- Gyroscope readings are the measure of angular velocities which has x,y and z components.
- Jerk signals are calculated for BodyAcceleration readings.
- Fourier Transforms are made on the above time readings to obtain frequency readings.
- Now, on all the base signal readings., mean, max, mad, sma, arcoefficient, engerybands,entropy etc., are calculated for each window.
- We get a feature vector of 561 features and these features are given in the dataset.
- Each window of readings is a datapoint of 561 features.

## Objective

Given a new datapoint we have to predict the Activity
