# Spotify Song Popularity Prediction
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

## Project Overview
This project aims to analyze and predict the popularity of Spotify songs using various song attributes. By leveraging machine learning techniques, we explore how features like tempo, energy, and danceability influence a song's popularity.

### Dataset 
| Name                  | Description                                                                                                                                  |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| `track_id`            | The Spotify ID for the track.                                                                                                                 |
| `artists`             | The artists' names who performed the track. If there is more than one artist, they are separated by a semicolon (;).                          |
| `album_name`          | The album name in which the track appears.                                                                                                    |
| `track_name`          | Name of the track.                                                                                                                           |
| `popularity`          | The popularity of a track, a value between 0 and 100. An algorithm calculates it and is mainly based on the total number of plays and recency. |
| `duration_ms`         | The track length in milliseconds.                                                                                                            |
| `explicit`            | Whether or not the track has explicit lyrics. (true = yes; false = no or unknown).                                                           |
| `danceability`        | Describes how suitable a track is for dancing, based on tempo, rhythm stability, beat strength, and overall regularity. Ranges from 0.0 to 1.0. |
| `energy`              | A measure from 0.0 to 1.0 representing intensity and activity.                                                                                 |
| `key`                 | The key the track is in, with integers mapping to pitches using standard Pitch Class notation. E.g., 0 = C, 1 = C♯/D♭, etc. -1 indicates no key detected. |
| `loudness`            | The overall loudness of a track in decibels (dB).                                                                                             |
| `mode`                | Indicates whether the track is major (1) or minor (0).                                                                                        |
| `speechiness`         | Detects the presence of spoken words in a track.                                                                                             |
| `acousticness`        | A measure from 0.0 to 1.0 of whether the track is acoustic.                                                                                   |
| `instrumentalness`    | Predicts whether a track contains no vocals. Values closer to 1.0 suggest no vocal content.                                                |
| `liveness`            | Detects the presence of an audience in the recording. Values above 0.8 indicate a live performance.                                           |
| `valence`             | A measure from 0.0 to 1.0 describing the musical positiveness conveyed by the track.                                                         |
| `tempo`               | The overall estimated tempo of a track in beats per minute (BPM).                                                                            |
| `time_signature`      | The time signature (meter) specifies how many beats are in each bar (or measure).                                                           |
| `track_genre`         | The genre to which the track belongs.                                                                                                        |

## Project Objectives
1. **Data Cleaning & Preprocessing**: Handling missing values, transforming categorical data, and normalizing numerical features.
2. **Exploratory Data Analysis (EDA)**: Understanding patterns, correlations, and distributions of song features.
3. **Feature Engineering**: Extracting relevant features to improve model performance.
4. **Model Training & Evaluation**: Implementing and assessing different machine learning models to predict song popularity.

## Machine Learning Models Used
- **Multiple Linear Regression**: Used for predicting numerical popularity scores.
- **Decision Trees**: A non-linear model for better feature interpretation.
- **eXtreme Gradient Boosting (XGBoost)**: An advanced ensemble learning method for improving accuracy.

## Technologies Used
- **Programming Language**: R
- **Libraries**: dplyr, ggplot2, caret, xgboost
- **Data Processing**: dplyr for data manipulation
- **Visualization Tools**: ggplot2, plotly for graphical analysis

## Project Workflow
1. **Data Acquisition**: Load and inspect the dataset.
2. **Data Cleaning & Processing**: Handle missing values, normalize numerical variables, and transform categorical features.
3. **Exploratory Data Analysis (EDA)**: Generate descriptive statistics, correlation heatmaps, and distribution plots.
4. **Feature Engineering**: Select relevant features that impact song popularity.
5. **Model Training**: Train Multiple Linear Regression, Decision Trees, and XGBoost models.
6. **Model Evaluation**: Compare model performance using MSE, MAE, and RMSE.
7. **Results Interpretation**: Draw insights and conclusions from the predictive analysis.
