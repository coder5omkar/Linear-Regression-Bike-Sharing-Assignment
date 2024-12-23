<p>
<img src="https://img.shields.io/badge/python-3.12.4-blue?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/numpy-1.26.4-blue?logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-2.2.2-blue?logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/seaborn-0.13.2-blue?logo=seaborn&logoColor=white" />
<img src="https://img.shields.io/badge/matplotlib-3.9.2-blue?logo=matplotlib&logoColor=white" />
</p>

# Shared Bike Demand Prediction 😄

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
``` 
This project aims to model the demand for shared bikes using various independent 
variables. The goal is to provide insights to the management team, helping them
understand how demand fluctuates with different features. By analyzing these patterns,
management can make informed decisions to adjust business strategies, optimize 
resource allocation, and align their operations with customer expectations. This model 
will serve as a valuable tool to anticipate demand and improve service delivery.
```

## Technologies Used
- [Python](https://www.python.org/) version: 3.12.4
- [Numpy](https://numpy.org/) version: 1.26.4
- [Pandas](https://pandas.pydata.org/) version: 2.2.2
- [Seaborn](https://seaborn.pydata.org/) version: 0.13.2
- [Matplotlib](https://matplotlib.org/) version: 3.9.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions 🔥
### Positive Coefficients:
- **year (0.2340)**: As the year increases, the demand for bikes increases slightly.
- **temp (0.4782)**: Higher temperature increases the demand for bikes, indicating people prefer to cycle in warmer weather.
- **summer (0.0623)** and **winter (0.0969)**: These seasons have a positive effect on demand, possibly due to seasonal preferences.

### Negative Coefficients:
- **holiday (-0.1043)**: On holidays, the demand for bikes may decrease, possibly due to fewer people commuting.
- **windspeed (-0.1480)**: Higher wind speeds seem to decrease bike demand, likely due to unfavorable cycling conditions.
- **Light_snowrain (-0.2904)**: Snow and rain significantly reduce demand, indicating that people avoid cycling in bad weather.
- **sun (-0.0495)**, **Misty (-0.0809)**, **spring (-0.0544)**: These have smaller negative impacts, which could reflect variations in weather conditions influencing demand.

## Acknowledgements
- This project was inspired by IIT-B AI-ML program at Upgrad

## Contact
Created by [@in/omkaramale](https://github.com/coder5om) - feel free to contact me!

Developed as part of the ML-1 Module assignment required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.

This project is open source and available under the [MIT License](https://github.com/coder5omkar/Linear-Regression-Bike-Sharing-Assignment/blob/main/licence.txt).
