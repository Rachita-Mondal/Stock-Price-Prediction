# Stock-Price-Prediction
This repository contains the codes, report and slides for the project of the course MTH517A-Time Series Analysis at IIT Kanpur, during the academic year 2021-2022.
# Project Title 
Time Series Analysis for Daily Stock Price Prediction of **Indus Tower Limited**
[Report](https://github.com/Rachita-Mondal/Stock-Price-Prediction/blob/main/Group%203_Final%20Report_MTH517A.pdf)
[Slides](https://github.com/Rachita-Mondal/Stock-Price-Prediction/blob/main/Group%203_Presentation_MTH517A.pptx)
[Codes](https://github.com/Rachita-Mondal/Stock-Price-Prediction/blob/main/Group%203_Codes_MTH517A.ipynb)
# Supervisor
Prof. Amit Mitra, Department of Mathematics & Statistics, IIT Kanpur 
# Team Members
* Rachita Mondal
* Souvik Bhattacharyya
* Shreya Pramanik
* Arkaprova Saha
* Bimal Roy
# Abstract 
The aim of our work is to apply relevant concepts of Time Series Analysis for daily closing stock price prediction of *Indus Tower Limited*. At first we tried to predict the mean behavior of the data set using appropriate AR, MA and ARIMA models. Thereafter, we have used Hybrid ARIMA-ARCH and Hybrid ARIMA-GARCH to capture the volatility of the series.
# Table of Content 
1 Introduction 1
2 Components Of a Time Series: 1
2.1 Trend(Long Term Direction): . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
2.2 Seasonal Component: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
2.3 Cyclical Component: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
2.4 Random Component: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
3 Decomposition Of a Time Series: 1
4 Test for Stationarity: 2
4.1 Kwiatkowski-Phillips-Schmidt-Shin (KPSS) Test: . . . . . . . . . . . . . . . . . . 2
5 Test For Existence of Trend: 2
5.1 Mann-Kendall Test: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2
6 Elimination of Deterministic component: 3
7 Introduction: MA Model 4
7.1 Definition . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
7.2 Fitting the model . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
7.2.1 Determination of Confidence Interval for ACF . . . . . . . . . . . . . . . . 5
7.2.2 Akaike Information Criterion (AIC) . . . . . . . . . . . . . . . . . . . . . . 5
7.3 Model Building . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
8 Introduction: AR Model 7
8.1 Definition . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
8.2 Fitting the model . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
8.2.1 Determination of Confidence Band for PACF . . . . . . . . . . . . . . . . . 7
8.2.2 Order Selection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
9 Introduction: ARIMA 9
9.1 Explanation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
9.2 Definition . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10
9.3 Model Fitting . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10
10 Introduction: ARCH-GARCH 11
10.1 Definition: ARCH model . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
10.2 Definition: GARCH model . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
11 ARIMA-ARCH Model 13
11.1 ARCH effect in ARIMA residuals . . . . . . . . . . . . . . . . . . . . . . . . . . . 13
11.2 Model Building . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
11.2.1 Algorithm . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
11.2.2 Order Selection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
11.3 Volatility Prediction by ARCH(3) . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
12 ARIMA-GARCH Model 16
12.1 Model Buliding . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16
12.1.1 Algorithm and Order Selection . . . . . . . . . . . . . . . . . . . . . . . . 16
12.2 Volatility Prediction by GARCH(1,1) . . . . . . . . . . . . . . . . . . . . . . . . . 17
13 Conclusion 17
iv




