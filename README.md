# Spotify Song Popularity Prediction

Welcome to the Spotify Song Popularity Prediction project readme! 

In this project, we will work with a sample of 10,000 records from the "Spotify Dataset 1921-2020, 600k+ Tracks," available on Kaggle. Our goal is to predict the popularity of songs on the Spotify platform, which is represented as a float ranging from 0 to 100.

## Dataset

The dataset includes the following columns:

**Numerical Columns:**
- `popularity`: Popularity of the song (target variable).
- `duration_ms`: Duration of the song in milliseconds.
- `explicit`: Whether the song is explicit (contains swearing or inappropriate language).
- `danceability`: Ranges from 0 to 1, representing how suitable a song is for dancing.
- `energy`: Ranges from 0 to 1, measuring the energy of the song.
- `loudness`: Loudness of the song, typically ranging from -60 to 0.
- `speechiness`: Ranges from 0 to 1, measuring the presence of spoken words in the song.
- `acousticness`: Ranges from 0 to 1, indicating the acoustic nature of the song.
- `instrumentalness`: Ranges from 0 to 1, indicating the instrumental nature of the song.
- `liveness`: Ranges from 0 to 1, measuring the presence of a live audience in the song.
- `valence`: Ranges from 0 to 1, representing the musical positiveness conveyed by the song.
- `tempo`: Tempo of the song, typically ranging from 50 to 150.

**Categorical Columns (string types):**
- `explicit`: Whether the song is explicit (contains swearing or inappropriate language).

### Data Preprocessing

The dataset is preprocessed to prepare it for model building. This includes:

- Dropping unnecessary columns such as `name`, `artists`, `id`, and others.
- Converting the `release_date` to a datetime format and extracting the year.
- Standardizing the numerical features.
- Splitting the data into training and testing sets.

### Model Building

In this project, we explore several regression models, including:

- **Linear Regression**: A basic model to establish a benchmark.
- **Polynomial Regression**: Using polynomial features to capture more complex relationships.
- **Random Forest Regressor**: An ensemble method for regression.
- **XGBoost Regressor**: A powerful gradient boosting algorithm.

### Model Evaluation

We evaluate our models using various metrics, including:

- **R-squared (R2) Score**: Measures the proportion of the variance explained by the model.
- **Root Mean Square Error (RMSE)**: Provides the average magnitude of prediction errors.
- **Mean Absolute Error (MAE)**: Measures the average absolute difference between predicted and actual values.
- **Mean Absolute Percentage Error (MAPE)**: Evaluates the percentage difference between predicted and actual values.

### Model Tuning

We perform hyperparameter tuning for the XGBoost Regressor and Random Forest Regressor to optimize their performance.

## Getting Started

To run this project, you will need Python and the following libraries installed:

- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

You can clone this repository and run the provided code in a Jupyter notebook or any Python environment.

## Conclusion

This project is an excellent opportunity for you to demonstrate your data analysis, preprocessing, model building, and evaluation skills. By working through this project, you can showcase your ability to handle real-world data and make predictions. Good luck with your internship application at Microsoft!

For any questions or assistance, feel free to reach out.

Best of luck, and happy coding! 🚀🎵
