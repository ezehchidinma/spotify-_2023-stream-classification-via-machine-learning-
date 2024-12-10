# Introduction
The Spotify Streams Classification project is designed to provide insights into how different features of a song correlate with its popularity, measured by streams. 
This can help music producers and enthusiasts understand what makes a song successful on streaming platforms.

# Dataset
The dataset used in this project was obtained from [kaggle]. It contains various features of songs including:

. speechiness

. streams

. danceability

. valence

. energy

. acousticness

. instrumentalness

. liveness

# Data Preprocessing

Before building the model, the data was cleaned and preprocessed. The steps included:

1. Handling missing values

2. Converting categorical variables to numerical

3. Normalizing the features

4. Removing outliers

# Dependencies

To run this project, you need the following libraries:

pandas

numpy

scikit-learn

matplotlib

seaborn

# Future Work

Future enhancements to this project could include:

1. Incorporating more features like tempo and key.

2. Experimenting with more advanced algorithms such as XGBoost.

3. Building a recommendation system based on the classification results.

# Conclusion
The project successfully classified songs based on their streams with promising accuracy.
Feature importance analysis highlighted that speechiness and energy were significant predictors of a song's popularity.

# Evaluation
The linear regression model was evaluated using the following metrics:

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.

R² Score: Indicates the proportion of variance in the dependent variable that is predictable from the independent variables.
