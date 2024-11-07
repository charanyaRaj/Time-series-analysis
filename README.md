# Time-series-analysis
Forecasting Ola Bike Ride Request Demand Using Time Series Analysis
I've created a complete Streamlit app for forecasting Ola bike ride demand. The app includes interactive time series analysis with the following features:

Time series visualization with historical data and forecasts Prophet model for accurate predictions Customizable forecast period (1-30 days) Confidence intervals for predictions Hourly and weekly pattern analysis Forecast component breakdown

It is challenging to service ride requests because of their unpredictability and spontaneity. For this very reason, it is vital to have a prediction algorithm that can forecast the approximate number of rides in the near future. This project aims to predict the ride-request demands for a particular area for a given time. Latitude, longitude values, and duration measures in military hours recognize the area. Dataset Description Data is made available from Ola’s repository. It contains fields like user_ID, request_latitude, request_longitutude, request_Time, pickup location, and drop locations. We make some assumptions to simplify the data set, as follows. If there are multiple ride requests from an area ( unique latitude-longitude) in an hour, it is simplified as one request only. Subsequent ride requests under 8 mins after the first request will get ignored, regardless of the area of origin for the requests. Distances under 50 meters in pickup and drop locations are assumed as fraud and hence ignored.

find the dataset here https://drive.google.com/file/d/1iE6Q2UTOiAFNhUa97yjEYQ4yMsb8E4b1/view?usp=sharing
