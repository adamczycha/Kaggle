# Kaggle Competitions Overview

Welcome to my repository of Kaggle competition notebooks! Here you'll find my work on various challenges, including data exploration, feature engineering, model development, and performance evaluations. Below is an overview of the competitions featured in this repository.

---

## Table of Contents

- [Rohlik Sales Forecasting Challenge](#rohlik-sales-forecasting-challenge)
- [Spaceship Titanic Dimension Transport Challenge](#spaceship-titanic-dimension-transport-challenge)

---

## [Rohlik Sales Forecasting Challenge](https://www.kaggle.com/competitions/rohlik-sales-forecasting-challenge-v2)

**Objective:**  
Develop models to predict the next 14 days of sales for each warehouse inventory item using historical sales data.

**Datasets Provided:**

- **sales_train.csv & sales_test.csv:**  
  Contains inventory IDs, dates, warehouse names, total orders, sell price, availability, and discount features.  
  *Target Variable:* `sales` (in the training set)

- **inventory.csv:**  
  Offers additional details about each inventory item.

- **calendar.csv:**  
  Provides date-specific information, including holidays and warehouse events.

**Task:**  
Forecast the `sales` for each unique inventory-date combination.  
**Notable Achievement:**  
My solution ranked in the top 17% (137 out of 777 teams). <br>
Top:
![Top Solution](https://github.com/user-attachments/assets/3ca24dce-387b-4ae3-b5ce-e712887c7f2e)
Mine:
![Mine Solution](https://github.com/user-attachments/assets/cd15e1e1-046b-48d9-af34-4c36ea7ae41a)

---

## Spaceship Titanic Dimension Transport Challenge

**Objective:**  
Create a predictive model to determine whether a passenger was transported to an alternate dimension after the Spaceship Titanic collided with a spacetime anomaly.

**Datasets Provided:**

- **train.csv:**  
  Contains records for roughly 8,700 passengers, with features such as:
  - PassengerID
  - HomePlanet
  - CryoSleep
  - Cabin
  - Destination
  - Age
  - VIP status
  - Spending at various amenities  
  *Target Variable:* `Transported` (True/False)

- **test.csv:**  
  Contains data for about 4,300 passengers for which predictions are required.

- **sample_submission.csv:**  
  Outlines the correct submission format for the challenge.

**Task:**  
Predict the `Transported` status for each passenger based on their personal and voyage data.

