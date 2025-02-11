---
title:  Satellite Image Time Series Classification
collection: projects
category: course_projects
---

[[Github Repo](https://github.com/khanhtrq/Satellite-Image-Time-Series-Classification)]  

This project is a part of my AI training program in 2022 at [Computer Vision Lab](https://bkai.ai/research/cv-team/), The International Research Center for Artificial Intelligence (BK.AI), Hanoi University of Science and Technology. It was supervised by one member of Computer Vision Lab.

## Summary

A satellite image time series (SITS) is a sequence of signals of a geographic area taken by a satellite at different times. SITS classification is widely applied to study and monitor enviroment, agriculture, and climate. Due to changes in environmental conditions, such as weather and seasonal changes, leveraging temporal data is necessary for accurate classification [1]. This project aimed at employing pattern recognition techniques to classify time-series data into land cover types. In particular, one-dimensional convolutional neural network (1D-CNN) and recurrent neural network (RNN) were applied to classify Sentinel-1 SITS into five types of land cover, namely Crop, Forest, Rice, Urban, and Water. The highest accuracies of 1D-CNN and RNN models are 84.2% and 85.9%, respectively.   


## Project Tasks and Knowledge Acquired
Project tasks:
- Designing one-dimensional convolutional neural network (1D-CNN) and recurrecurrent neural network (RNN) architectures for time series classification.  
- Implementing designed models with PyTorch.  
- Implementing deep learing model development pipeline with PyTorch.  
- Conducting experiments on Google Colab platform.  

Knowledge acquired:  
- Time series classification with deep learning.  
- Understanding of deep learing model development pipeline: data pre-processing, training (gradient backpropagation, parameters updating, monitoring training process), hyperparameters tuning, inference, model evaluation.  

## References
[1] Gómez C, White JC, Wulder MA. Optical remotely sensed time series data for land cover classification: A review. ISPRS Journal of photogrammetry and Remote Sensing. 2016 Jun 1;116:55-72.  


<!-- In some cases, classification using single image is not enough because of random noise is generated from sensors or environment. This small project is an example for student(s) to know how to apply pattern recognition techniques on time-series data (https://towardsdatascience.com/a-brief-introduction-to-time-series-classification-algorithms-7b4284d31b97). In this project, student will use extracted/pre-prepared time-series data (3 different bands) from Sentinel-1 images to classify pixels to land cover types
 - Plot some sample time-series to see why pattern recognition is needed
 - Apply ML algorithm(s) to classify pixels using single bands
 - Apply ML algorithm(s) to solve the problem using multiple bands
 - Analyse/ Report results  

Note: Detailed instructions and sample codes (if needed) will be provided by the supervisor. Student can read some tutorials in advance  
https://www.analyticsvidhya.com/blog/2019/01/introduction-time-series-classification/  
https://towardsdatascience.com/hands-on-climate-time-series-classification-with-deep-learning-using-python-6d5de81004c9  
https://keras.io/examples/timeseries/timeseries_classification_from_scratch/  -->
