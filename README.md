Mechanical Properties Prediction

Predicting mechanical performance to accelerate the design of novel steels by Machine Learning Algorithms.

1、Introduction

This package contains the code for the Deep Neural Network (DNN), RF, SVR, and BP models used in the article. In addition, it also includes code for correlation analysis of the data.


2、Environment Setup

The codes were implemented on the MATLAB2023a platform.


3、To use this package

(1) The codes for correlation analysis of original data are stored in “data processing” folder:
    ●  Run Pearson correlation analysis.m to calculate correlation coefficients between the influencing factors and mechanical properties.
    ●  Select parameters with correlation coefficients greater than 0.2 for tensile strength (TS) and 0.3 for elongation (EL) respectively.
    ●  Run correlation coefficient code.m to draw a correlation heat map for the influencing factors and mechanical properties.

(2) The code for the Deep Neural Network (DNN), RF, SVR, and BP models used in the article are stored in “model code” folder:
   ●  Load result.mat to view the network structure and specific parameters of the model.
   ●  Run test.m to obtain the prediction result and draw the prediction result graph.


4、Free use statement

The code and resources are available for educational, research, and non-commercial purposes. 
