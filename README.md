# SheSafe
SheSafe is a machine learning–based tool that predicts a contextual safety risk score (1–10) for women, based on travel conditions such as time, location, mode of transport, and device context.

Problem Statement:
Women often travel alone, late at night, or in unfamiliar areas where safety is uncertain. There is no simple way to assess how risky a particular place or time may be.
SheSafe addresses this gap by using real crime data and contextual features to produce a personalized safety score.

Key Features
Uses real-world crime data from Indian states
Synthetic contextual data generated for time, battery level, travel mode, and solo travel status
State-wise target encoding for regional safety patterns
Random Forest regression model for accurate risk scoring
Predicts safety risk score on a scale from 1 (very safe) to 10 (very risky)

Technologies Used
Python (Pandas, NumPy)
scikit-learn (Random Forest Regressor)
Google Colab (for prototyping and development)

Sample Prediction
Input:
Time: 22:00 (10 PM)
State: Delhi
Battery: 15%
Is Alone: Yes
Mode of Travel: Cab

Output:
Predicted Risk Score: 8.4 / 10

Future Improvements
Integrate real-time GPS and police reports
Train on district- or city-level datasets for greater granularity
Build a web or mobile interface for real-time use
