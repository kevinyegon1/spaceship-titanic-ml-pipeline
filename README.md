# 🚀 Spaceship Titanic: Interstellar Passenger Recovery

## 🌌 Project Overview
Welcome to the year 2912! The **Spaceship Titanic**, an interstellar liner, collided with a spacetime anomaly near Alpha Centauri. Almost half of the passengers have been transported to an alternate dimension. 

This project uses machine learning to predict which passengers were transported based on damaged records recovered from the ship's computer system. The goal is to assist rescue crews in identifying the missing and bringing them home.

## 🛠️ Technical Implementation
This repository contains a complete end-to-end machine learning workflow, featuring:
* **Target Encoding:** Handling boolean targets for compatibility with ML models.
* **Robust Preprocessing:** A `ColumnTransformer` approach to handle numeric and categorical data simultaneously.
* **Automated Pipelines:** Scikit-learn Pipelines to prevent data leakage and ensure consistent scaling.
* **Missing Value Imputation:** Strategic handling of NaNs in cosmic data (like `HomePlanet` and `CryoSleep`).

## 📊 Dataset Features
The model analyzes several key features, including:
- `HomePlanet`: Earth, Europa, or Mars.
- `CryoSleep`: Whether the passenger was confined to their cabin.
- `Destination`: The planet the passenger was debarking to.
- `Age`, `VIP` status, and spending habits (Food Court, Spa, VR Deck).

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/spaceship-titanic-classification.git](https://github.com/kevinyegon1/spaceship-titanic-classification.git)
