### Overview
This project involves building a machine learning model to predict the fare of Uber rides based on key features such as passenger count, distance, time of day, and the day of the week. The model is trained using a  Uber dataset, and it includes an interactive interface built with Gradio to allow users to input ride details and get fare predictions in Indian Rupees (INR).

## Features
**Data Cleaning:**
* Ensures that only valid data (e.g., geographical coordinates and reasonable fares) is used for training.

**Feature Engineering:**
* Key features like ride distance, pickup hour, and day of the week are derived from the dataset.

**Machine Learning:**
* Linear Regression is used as the primary model for fare prediction, with an option to explore Gradient Boosting and Random Forest models.

**Interactive Deployment:**
* The trained model is deployed using Gradio, allowing users to input ride details and view predicted fares.

**Dataset Description**
The dataset contains Uber ride details with the following features:

* Pickup and Dropoff Coordinates: Latitude and longitude for ride start and end points.
* Pickup Datetime: Date and time when the ride began.
* Passenger Count: Number of passengers during the ride.
* Fare Amount: Total fare for the ride (in USD).
* Derived Features: Includes distance (in km), pickup hour, and the day of the week.

**Technologies Used**
* Python Libraries:

- Pandas: Data manipulation and cleaning.
- NumPy: Numerical computations.
- Scikit-learn: Machine learning model training and evaluation.
- Gradio: Interactive model deployment.
* Machine Learning Models:

- Linear Regression.
- Gradient Boosting (optional).
- Random Forest (optional).


**Usage Example**
Enter the following details in the Gradio interface:

* Passenger Count: Number of passengers (e.g., 2).
* Distance (in km): The estimated travel distance (e.g., 10).
* Pickup Hour: The hour of the day (e.g., 15 for 3 PM).
* Day of Week: The day of the week (e.g., 1 for Tuesday).
* The predicted fare will be displayed in Indian Rupees (INR).

**Future Enhancements**
* Implement additional machine learning algorithms for better accuracy.
* Integrate real-time currency conversion for fare predictions.
* Add more features like weather conditions or traffic data for improved predictions.
