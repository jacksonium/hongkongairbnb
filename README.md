Motivation for the project
--------------------------
This repository consists of data files (Nov 2019 & Nov 2020) obtained from insideairbnb.com for Hong Kong.

The jupyter notebook contains my analysis and findings to answer:

1) What is the COVID-19 impact on Airbnb market in Hong Kong?
2) What is the most common type of Airbnb rental property? Where is the most popular area?
3) Any price seasonality trend observed?
4) Can we predict the Airbnb prices and figure out a way to provide pricing insight? 


Libraries used
--------------
1) numpy
2) matplotlib
3) pandas
4) folium
5) sklearn
6) seaborn
7) itertools


Files in the respository
------------------------
1) Hong_Kong_airbnbn.ipynb     - jupyter notebook containing the analysis
2) 2019_hongkong_calendar.csv  - 2019 Nov Airbnb data containing calendar data(pricing & availability)
3) 2019_hongkong_listings.csv  - 2019 Nov Airbnb data containing unique listing information and attributes
4) 2019_hongkong_reviews.csv   - 2019 Nov Airbnb data containing reviews from customers for different properties
5) 2020_hongkong_calendar.csv  - 2020 Nov Airbnb data containing calendar data(pricing & availability)
6) 2020_hongkong_listings.csv  - 2020 Nov Airbnb data containing unique listing information and attributes
7) 2020_hongkong_reviews.csv   - 2020 Nov Airbnb data containing reviews from customers for different properties
8) README.md                   - This file

Summary of the results of the analysis
--------------------------------------
The questions were answered and a prediction model was built using machine learning techniques from 2019 data using random forest regression algorithm with a R^2 score of over 0.85 which seems to be satisfactory. Please refer to the jupyter notebook for detail.

However fitting the model with 2020 data did not produce desire results. Further investigation and work are required, which including but not limited to using different modelling alogorithm or using data from longer time horizon.

A blog post has also been published at:

https://jackson-chan.medium.com/predicting-hong-kong-airbnb-prices-4384891bcd04


Acknowledgement
---------------
Many thanks to insideairbnb.com for providing the necessary publicly available Airbnb data



