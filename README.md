# Forecasting-Mobile-Network-Traffic

Image

## Overview 

This is a task that is focused on analyzing and forecasting future traffic from mobile data traffic dataset recorded in a real-world network that covers a large city of Milan & Province of Trentino, covering the period of November to December 2013. 

The task can be broken down into two main parts: 

- In the first task, we need perform basic characterization of the data such as figure illustrating the distribution (eg. Probability density function) of a total traffic recorded in a geographical area in the period of two months and discussing the homogeneity and diversity of total traffic per area. Figure illustrating the time series of network traffic traffic during the first two weeks in four popular areas (with different square id) in the city of Milan and discussing the similarities or differences observed in the temporal dynamics of each area, and speculating their causes. 

- In the second task, we need to code an algorithm for one-step prediction of future traffic in a single area. Formally, let us denote as x<sub>a(t) the traffic observed at area a during the time interval t. At each time t, the algorithm receives as input a history x<sub>t, ie., a vector of traffic values in past time intervals, up to t included. The algorithm shall then produce as output an estimate x<sub>(t+1) of future traffic t+1 in area a. The algorithm should be able to forecast traffic in the four geographical areas identified at the Task I, during the week from December 16 to 22.
  
  
## Dataset 

The dataset reports lines in the format above for 10,000 areas (organized in a regular grid) during a continued period of two months.
A preliminary description of the data is provided in a paper published in Scientific Data by Barlacchi et al. [Link](https://www.nature.com/articles/sdata201555). While the paper presents the many datasets that were made available for the other challenges, only two are relevant to the above mentioned tasks:

- The Telecommunication activity dataset for the city of Milan (i.e., data citation 5 in the paper), which contains mobile network traffic

- The Grid dataset for the city of Milan (i.e., data citation 2 in the paper), which describes the tessellation of space into the areas over which such information is aggregated

Further, the network traffic is measured in terms of number of call detail records (CDR) generated by mobile Internet sessions. This is
only a proxy for the actual traffic volume in bytes, which provides however a decent estimate for the fluctuations of mobile data traffic.

## Representing Geographical Data using Grid GeoJSON dataset

Image

#### This work was submitted to Assoc. Prof. Marco Fiore (Research Associate Professor, IMDEA Networks Institute - Madrid) as a part of Phd Audition Process. 

## References

- [1] Barlacchi, G., De Nadai, M., Larcher, R. et al. A multi-source dataset of urban life in the city
of Milan and the Province of Trentino. Sci Data 2, 150055 (2015)

- [2] Trinh, Hoang Duy & Bui, Nicola & Widmer, Joerg & Giupponi, L. & Dini, Paolo. (2017). Analysis and Modeling of Mobile Traffic Using Real Traces. 10.1109/PIMRC.2017.8292200

- [3] Aarshay Jain, (2016, Feb 6), A comprehensive beginner's guide to create Time Series Forecast - Blog Post

- [4] Selva Prabhakaran, (2019, Feb 18), ARIMA Model - Time Series Forecasting - Blog Post

- [5] Kaggle: Mobile Activity in a city [Link] (https://www.kaggle.com/marcodena/mobile-phone-activity/kernels)

- [6] Raymond Camden, (2019, Sep 4), An Introduction to GeoJSON - Blog Post

LICENSE: This task is licensed under the terms of the MIT license.
