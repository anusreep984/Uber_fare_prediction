#Uber Fare Prediction using Linear Regression

This project builds a **Machine Learning regression model** to predict Uber ride fares based on trip distance, pickup/dropoff location, passenger count, and time-related features.

The model was implemented using **Python, Pandas, Scikit-Learn, and Google Colab**.


## Project Objective

The goal of this project is to build a **Linear Regression model** that predicts the fare amount of an Uber ride using historical trip data.

Predicting ride fares helps ride-sharing companies:

- estimate pricing
- analyze trip patterns
- optimize route efficiency

---

## Dataset Features

The dataset contains the following features:

| Feature | Description |
|------|------|
| fare_amount | Target variable (ride cost) |
| distance_km | Distance of trip in kilometers |
| pickup_longitude | Pickup longitude coordinate |
| pickup_latitude | Pickup latitude coordinate |
| dropoff_longitude | Dropoff longitude coordinate |
| dropoff_latitude | Dropoff latitude coordinate |
| passenger_count | Number of passengers |
| year | Year of trip |
| month | Month of trip |
| day | Day of trip |
| hour | Hour of trip |

Model Results

The Linear Regression model successfully predicts Uber ride fares using trip-related features.

Key observations:
	•	Trip distance strongly influences fare price.
	•	Time-related features affect ride cost during peak hours.
	•	Passenger count has a minor impact compared to distance.

⸻

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-Learn
	•	Google Colab
	•	Matplotlib (for visualization)

⸻

Project Learnings

Through this project I learned:
	•	Data preprocessing for regression problems
	•	Feature engineering with geospatial and time features
	•	Building regression models using Scikit-Learn
	•	Evaluating model performance using regression metrics
	•	Applying machine learning to real-world transportation data

⸻

Future Improvements

Future enhancements could include:
	•	Using Advanced Regression Models
	•	Applying Random Forest Regressor
	•	Using XGBoost for improved accuracy
	•	Adding traffic and weather data
	•	Deploying the model as a web application

⸻

Conclusion

This project demonstrates how machine learning can be used to predict ride fares based on trip characteristics. The Linear Regression model provides a simple and interpretable approach for fare estimation and highlights the importance of distance and trip timing in determining ride cost.
