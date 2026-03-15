# TimeSeriesCrimeRateFocasting
Time series forecasting project for crime rate prediction using classical methods, MLP, CNN, and LSTM models with comparative evaluation.
This repository contains a time series forecasting project for crime rate prediction using both classical statistical methods and deep learning models.

The project explores how historical crime data and contextual time-based features can be used to forecast crime occurrence patterns and compare the performance of different forecasting approaches.

---

### Project Overview

Crime occurrence is influenced by multiple temporal and contextual factors.  
This project aims to build and compare forecasting models that can predict crime rate trends from historical data.

The workflow includes:

- data cleaning and preprocessing
- exploratory data analysis
- time series visualization
- white noise and stationarity checking
- classical forecasting models
- deep learning model development
- model comparison and evaluation

---

### Objectives

- Predict crime rate based on historical data
- Analyze temporal patterns in crime occurrence
- Compare classical and deep learning forecasting models
- Evaluate how contextual features improve prediction performance

---

### Dataset

The project uses a crime dataset containing records from 2020 onward.  
For efficiency and modeling purposes, the working dataset was filtered and reduced before analysis.

The final analysis focuses on a smaller subset of processed crime records suitable for time series modeling.

---

### Methods

#### 1. Data Preprocessing
- datetime conversion
- feature engineering
- sequence construction for time series input
- reshaping for neural network models

#### 2. Exploratory Analysis
- time plots
- seasonal plots
- lag plots
- scatterplots for crime type vs. time of day
- white noise detection
- stationarity analysis

#### 3. Classical Forecasting Models
- Mean model
- Naive model
- Drift model
- Seasonal Naive model
- Autoregression (AR)
- SARIMA
- Holt-Winters

#### 4. Deep Learning Models
- Standard MLP
- Multi-Head MLP
- Univariate CNN
- Multivariate CNN
- Multi-Parallel CNN
- Vanilla LSTM
- Stacked LSTM
- CNN-LSTM
- ConvLSTM
- Multi-Input LSTM
- Multi-Parallel LSTM

#### 5. Evaluation
Models are compared using metrics such as:
- MAE
- RMSE
- R² score
- validation performance comparison

---

### Key Highlights

- Compared both traditional and deep learning forecasting methods
- Built multi-input and multi-parallel neural architectures
- Explored temporal and contextual crime features
- Conducted performance comparison across multiple model families
- Investigated how model complexity affects forecasting accuracy

---

### Main Findings

The project shows that incorporating richer contextual and temporal inputs can improve forecasting performance.

Among the tested approaches, more advanced neural architectures such as multi-input models achieved stronger predictive results than simple baseline forecasting methods.

At the same time, the experiments also show that more complex models do not always guarantee better generalization, making model comparison essential.

---

### Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- TensorFlow / Keras

---

### Repository Structure

```text
crime-rate-forecasting/
│── notebooks/
│   └── CrimeRateForecasting_FinalVersion.ipynb
│── data/
│   └── processed crime dataset files
│── images/
│   └── plots and result figures
│── README.md
```

---

### Future Improvements

- Add external contextual features such as weather, holidays, or public events
- Improve robustness on rare crime spikes
- Perform more systematic hyperparameter tuning
- Deploy a simple forecasting dashboard or visualization interface

---

### Notes

This repository is intended for academic and portfolio purposes.
