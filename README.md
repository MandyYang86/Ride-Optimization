# Ride Sharing Optimization Project
------------------------------------

Eugene Cheah | Mengting Yang | Rahil Shah

cheah.eug@husky.neu.edu | yang.meng@husky.neu.edu | shah.rah@husky.neu.edu

CSYE 7245: Big Data Systems and Intelligence Analytics
INFO 7390: Advances Data Science/Architecture

Spring 2018, Northeastern University College of Engineering

## Abstract
We are aspiring data scientists working on a project to predict the prices of ride sharing services Uber and Lyft. We have retrieved data from Uber and Lyft and applied linear regression, machine learning algorithms, the Moving Average model, deep learning with TensorFlow, and the Facebook Prophet package.

## Introduction
Whether you’re a driver or passenger, you must’ve found yourself pondering whether to use Uber or Lyft at some point. Time and money are lost in the decision-making process. Our solution is to build an app that streamlines the decision process. By providing real-time and forecasted prices of both ride-sharing services, users can now make an informed decision. Our team has successfully automated the continuous extraction of data from Uber and Lyft. We have also applied models in linear regression, machine learning algorithms, moving average, deep learning recurrent neural network as well as the Facebook prophet package for forecasting the prices estimates of Uber and Lyft.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Download and install [Python distributed by Anaconda](https://www.anaconda.com/download/).

### Installing Dependencies
The following are commands to install Python packages not included in the Anaconda installed which we have used and are Windows-supported, some changes may need to made in the case of an Apple or a Linux machine:
* SQLite
```
conda install -c conda-forge sqlite  
```

* Uber Rides
```
pip install uber-rides  
```

* GeoPy
```
conda install -c conda-forge geopy  
```

* Lyft Rides
```
pip install lyft_rides  
```

* XGBoost - Gradient Boosting
```
conda install -c conda-forge xgboost  
```

* Facebook Prophet
```
conda install -c conda-forge fbprophet
```

* TensorFlow
```
conda install -c conda-forge tensorflow 
```

## Getting the Data Needed
[Data Retrieval](https://github.com/rahilshah10/IS/blob/master/ADS/Final%20Project/Notebooks/Data%20Retrival.ipynb) contains details on how we scrapped our data.

### Datasets
Uber API - https://developer.uber.com/dashboard/

Uber Rides Python SDK (beta) - https://github.com/uber/rides-python-sdk 

Lyft API - https://developer.lyft.com/v1/reference 

Weather API - https://openweathermap.org/api

Yelp API - https://www.yelp.com/developers/documentation/v3/business_search 

The dataset headings glossary can be found [here](dataset_headings_glossary.docx).

## Navigating the Ride Sharing Optimization Project

##### Data Cleaning
* [Lyft Notebook](https://github.com/MandyYang86/Ride-Optimization/blob/master/Data%20Clean%20Part/DataClean_OneMonth_Lyft_Line.ipynb)
* [Uber Notebook](https://github.com/MandyYang86/Ride-Optimization/blob/master/Data%20Clean%20Part/DataClean_OneMonth_Uber_Pool.ipynb)

##### Machine Learning 
* [Ride Sharing Machine Learning Notebook](https://github.com/rahilshah10/IS/blob/master/ADS/Final%20Project/Notebooks/Machine%20Learning.ipynb)

##### Time Series Analysis with Moving Average
* [Lyft Notebook](https://github.com/MandyYang86/Ride-Optimization/blob/master/MA%20Model/Time%20Series%20-%20Moving%20Average%20Model-Lyft.ipynb)
* [Uber Notebook](https://github.com/MandyYang86/Ride-Optimization/blob/master/MA%20Model/Time%20Series%20-%20Moving%20Average%20Model-Uber.ipynb)

##### Time Series Analysis with Facebook Prophet 
* [Facebook Prophet Notebook](https://github.com/echeah/big_data_systems_and_intelligence_analytics/blob/master/rides_sharing_optimization_project/time_series_facebook_prophet.ipynb)

##### Time Series Analysis in Deep Learning with TensorFlow
* [Deep Learning Notebook](https://github.com/echeah/big_data_systems_and_intelligence_analytics/blob/master/rides_sharing_optimization_project/time_series_deep_learning_tensorflow.ipynb)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments
A special thank you to __Professor Nik Bear Brown__ for providing guidance and thoughtful insights throughout the course of the project.
You are very welcome to modify these tutorials and use them in your own projects.
