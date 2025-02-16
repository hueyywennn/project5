# Song Popularity Prediction
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

## Project Overview
Performed a Spotify Song Popularity data analysis to explore factors influencing song popularity on the platform. Utilized descriptive statistics and machine learning techniques to analyze song features such as tempo, energy, and danceability.

### Dataset 
| Name                  | Description                                                                                                                                  |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| `track_id`            | The Spotify ID for the track.                                                                                                                 |
| `artists`             | The artists' names who performed the track. If there is more than one artist, they are separated by a semicolon (;).                          |
| `album_name`          | The album name in which the track appears.                                                                                                    |
| `track_name`          | Name of the track.                                                                                                                           |
| `popularity`          | The popularity of a track, a value between 0 and 100. It is calculated by an algorithm and is mainly based on the total number of plays and recency. |
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
| `time_signature`      | The time signature (meter) specifying how many beats are in each bar (or measure).                                                           |
| `track_genre`         | The genre to which the track belongs.                                                                                                        |

### Features
1. **Data Cleaning**
  -	Check missing values, null values, and duplicated values
  -	Data Transformation: grouping genres into bigger categories (parent genres)
  -	Data Normalization: min-max scaler
2. **Exploratory Data Analysis (EDA)**
  -	Statistical Summaries: mean, median, variance, and standard deviation
  -	Correlation Analysis: heatmap correlations
  -	Distribution Plots: histograms, scatter plots, box plots,
3. **Machine Learning Models**
  -	Feature Engineering: 
  -	Classifier Algorithms: eXtreme Gradient Boosting (XG BOOST), desicion trees
  -	Regression Algorithms: multiple linear regression
  -	Model Evaluation: MSE, MAE, RMSE, confusion matrix
  -	Predictive Modeling: eXtreme Gradient Boosting (XG BOOST), desicion trees, multiple linear regression
4. **Interactive Visualizations**
  -	null

## Tools used 
1. **Programming Language** 
   - R
2. **Libraries**
   - dplyr, ggplot2, caret, xgboost
3. **Visualization Tools**
   - ggplot2, plotly
