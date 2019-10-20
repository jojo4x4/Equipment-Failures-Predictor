## Inspiration
Challenge by ConocoPhilips

## What it does
Takes in sensor data and uses a neural network to determine if there will be an equipment failure or not.

## How I built it
I used sklearn and pandas to clean up the csv data input. Then I oversampled the failure cases to account for class imbalance. I then made a binary classifier in Keras and fit it to the data and used it to predict the test data for failures which were then evaluated on Kaggle using the F1 metric.

## Challenges I ran into
I ran into a lot of confusion on optimizing for F1 and trying to do that directly. There was also a lot of challenge in handling missing data and interpolating and filling null values.

## Accomplishments that I'm proud of
I am proud of my first non classroom data science project and my first neural network (in or out of class).

## What I learned
I learned about SMOTE oversampling and made my first Keras neural network.

## What's next for Equipment Failure Prediction
Better handling of null values
More hyperparameter tuning
