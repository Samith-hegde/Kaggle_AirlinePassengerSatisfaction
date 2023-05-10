# Kaggle_Projects

# Airline Passenger Satisfaction
The dataset contains an airline passenger satisfaction survey. 
The aim of the project was to use ML models to predict passenger satisfaction (Binary Classification: 'satisfied' and 'neutral/dissatisfied') based on their ratings of specific factors relating to their experience in one flight journey, 
and other general factors such as the passenger's air, arrival and destination time of the flight, flight duration, etc.
What was done in the project:
1) Importing the data
2) Data Visualization
3) Plotting Correlation Map
4) Feature Engineering (by using Mutual Information Scores between various features)
5) Train-test split
6) Pipeline of categorical data (One-Hot or Ordinal Encoded) and numerical data (Normalized)
7) Trained and tested the data on 3 models: Linear SVC (Support Vector Classification), SGD Classifier (Stochastic Gradient Descent), and Gradient Boosting Classifier
8) Metrics used to evaluate models: Accuracy score, F1 score, Precision score, Recall score, Confusion matrix
9) Best model: Gradient Boosting Classifier (Accuracy score on testing data = 0.9295, Recall score = 0.9477, F1 score = 0.9219)

# Spaceship Titanic Competition
Problem Statement - The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.
While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!
To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.
What was done in the project:
1) Importing the data
2) Data Visualization
3) Plotting Correlation Map
4) Pipeline of categorical data (One-Hot Encoded) and numerical data (Standardized) using ColumnTransformer
5) Train-test split
6) Trained and tested data on Linear SVC (Support Vector Classification), obtained accuracy score for testing data of 0.7948
7) Performed hyperparameter tuning using GridSearchCV, a cross-validation technique.
8) Retrained the model using the optimum parameters, accuracy score for testing data increased marginally to 0.7976

Final Rank in the competition: 
