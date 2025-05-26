# Flight Fare Prediction System ✈️💸

## Project Description

<b>
Flight travel has become a crucial part of modern transportation. With increasing demand and seasonal variations, airfare pricing tends to fluctuate based on various factors such as travel dates, airline, duration, stopovers, and festivals or holiday seasons. This project aims to build an intelligent system that can accurately predict flight fares based on historical and real-time data, thereby assisting travelers in planning more cost-effective journeys.
</b><br><br>

## Objectives

The primary goal of this project is to develop a web-based system that:

* Predicts flight ticket prices using machine learning algorithms.
* Allows users to input travel details via a web interface.
* Provides real-time fare predictions based on a trained model.
* Offers CSV-based batch prediction support.

<br>

## ML Project Life Cycle

This machine learning application follows the standard lifecycle:

* Data Collection
* Data Exploration and Visualization
* Data Preprocessing (Handling Missing Values, Encoding, etc.)
* Model Building (Regression Techniques using scikit-learn)
* Model Evaluation (using R2 score, MAE, RMSE)
* Model Deployment using Flask & integrated with React.js UI

<br>

## Dataset

We used the "Flight Fare Prediction MH" dataset available on Kaggle. It contains information like airline, date of journey, source, destination, duration, total stops, and price.

* [Dataset Link](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)

<br>

## Tech Stack

* **Frontend**: js (Responsive UI)
* **Backend**: Python Flask
* **Machine Learning**: scikit-learn
* **Data Processing**: Pandas, NumPy
* **IDE**: Visual Studio Code


<br>

## App Screenshots

* Homepage

  <img src="image/Home.png" width="700px">
* Input Form

  <img src="image/Ind.jpg" width="700px">
* Prediction Result

  <img src="image/Predict.jpg" width="700px">

<br>

## How to Run the Project 🛠️

### 1. Set up a Virtual Environment:

```bash
conda create -n flightfareenv python=3.8
conda activate flightfareenv
```

### 2. Install Dependencies:

```bash
pip install -r requirements.txt
```

### 3. Run Flask Server:

```bash
python app.py
```

### 4. Access Application:

Open browser and go to: `http://127.0.0.1:5000/`

### 5. Usage:

* Fill in flight details on the web form.
* Or upload a CSV file with flight data.
* Click "Predict" to see the fare estimation.

<br>

## Modules Summary

1. **Data Collection**: Kaggle dataset on flight prices.
2. **Data Cleaning**: Missing value imputation, formatting, encoding.
3. **Model Training**: Regression algorithms (RandomForest, Linear Regression, etc.).
4. **Model Deployment**: Backend with Flask API.
5. **Frontend**: React UI for user interaction.
6. **Integration**: End-to-end ML pipeline deployed on a full stack system.

<br>

## Team Members

* **Sk Rahemur Rahaman** – Team Lead Full Stack Developer with Data Analyst(23000121004) -- https://github.com/rahemur0910
* **Sathi Brahmachari** – Frontend Developer (23000122058)
* **Pritam Sarkar** – Backend Developer (23000122051)
* **Arunaditya Dutta** – Data Analyst (23000122041)
* **Mainak Pal** – Model Developer (23000122050)

<br>

## Project Supervisors

* **Prof. Anubhav Pal** – Internal Supervisor
* **Prof. Alok Kr Barma** – Project Guide

<br>

## Institution Details

* **College Name**: Camellia Institute Of Technology
* **University Name**: Maulana Abul Kalam Azad University of Technology

<br>

## Future Enhancements 🚀

* Dynamic scraping of live flight data.
* Integration with travel APIs (e.g., Skyscanner).
* Fare forecasting visualization (charts).
* User login and trip management.

---
