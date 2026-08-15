# Flight Delay Prediction

A machine learning project for predicting flight delays using historical flight data. This project explores two prediction scenarios based on the information available at different stages of a flight.

## Overview

Flight delays can be influenced by various factors, including airline operations, airport conditions, scheduled departure times, weather-related factors, and previous flight information.

This project investigates how machine learning can be used to predict flight delays under two different scenarios:

1. **Pre-Flight Prediction** — predicting whether a flight will be delayed before departure using information available prior to the flight.
2. **Post-Departure Prediction** — predicting flight delays after the aircraft has departed by incorporating additional information available during the flight process.

The project uses a large-scale flight dataset containing more than 7 million records.

## Project Structure

The project is divided into two main experiments:

### 1. Pre-Flight Prediction

The model predicts flight delays using information that is available before the scheduled departure.

**Objective:**
Predict whether a flight will experience a delay before it departs.

**Model:**

* XGBoost

**Notebook:**
[Open Pre-Flight Prediction in Google Colab](YOUR_PRE_FLIGHT_COLAB_LINK)

---

### 2. Post-Departure Prediction

The second experiment explores flight delay prediction after the aircraft has already departed. Additional information available after departure is used to improve the prediction.

**Objective:**
Predict potential flight delays using information available after departure.

**Notebook:**
[Open Post-Departure Prediction in Google Colab](YOUR_POST_DEPARTURE_COLAB_LINK)

## Dataset

The project uses a large flight dataset containing approximately **7 million records and 35 features**.

The dataset contains information related to:

* Flight schedules
* Airlines
* Airports
* Departure and arrival times
* Flight duration
* Delays
* Distance
* Operational information

Due to the size of the dataset, preprocessing and model training were performed with consideration for computational efficiency.

## Methodology

The general workflow of the project is:

```text
Raw Flight Data
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Selection & Engineering
       ↓
Train / Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Prediction & Analysis
```

The same general workflow is applied to both prediction scenarios, while the available features differ depending on whether the prediction is performed before or after departure.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Google Colab

## Key Focus

This project focuses not only on model performance, but also on the effect of **feature availability** on flight delay prediction.

The comparison between pre-flight and post-departure scenarios provides insight into how additional operational information can affect the ability of a machine learning model to identify potential delays.

## Notebooks

| Experiment     | Description                     | Notebook                                       |
| -------------- | ------------------------------- | ---------------------------------------------- |
| Pre-Flight     | Predict delays before departure | [Google Colab](YOUR_PRE_FLIGHT_COLAB_LINK)     |
| Post-Departure | Predict delays after departure  | [Google Colab](YOUR_POST_DEPARTURE_COLAB_LINK) |

## Project Context

This project was developed as part of an academic machine learning and big data project, focusing on applying machine learning techniques to a large-scale real-world dataset.

---

**Author:** Bima Saputra, Dimas Rasyach Nur Fathi, Al Hadid Aditya
