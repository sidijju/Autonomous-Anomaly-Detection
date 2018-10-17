# Autonomous Anomaly Detection

## Overview
Science Research 2017-2018. Built neural network (autoencoder + retrained MobileNet) in order to classify objects on trails for SAR purposes.

## Abstract
  The purpose of this project was to create a novel implementation of the concepts of anomaly detection and object classification to assist search-and-rescue (SAR) teams in rescue missions. SAR teams continually suffer from a lack of resources and volunteers, which decrease their ability to efficiently search the hundreds of miles of trails in the potential search area. My project aims to address this issue by creating an autonomous system that would be able to detect objects and anomalies on the trail using object classification and anomaly detection. This system would be used in conjunction with a quadrotor or other autonomous vehicle and would enormously increase efficiency in search missions. The research done in this project can also be applied in other areas such as cybersecurity and medical imaging.
  Anomaly detection is the ability of a machine to learn what is normal for a system, and then detect outliers from the norm for that system in the future. Object classification is the ability of a machine to learn features differentiating between objects and then use this information to classify objects in a new image. In this project, a 2-layer convolutional auto-encoder was constructed and tested against a set of images with an accuracy of 87.5% for detecting anomalies. In conjunction, a pre-existing object classifier called MobileNet was re-trained to classify common hiker items with an accuracy of 93%. An autonomous implementation of the model was also created. The contributions of this project include performing real time object classification and anomaly detection that do not require Wi-Fi or cellular service. 
  
## Results

Autoencoder (Anomaly Detection Stage):  87.5%
Object Detection (retrained MobileNet): 93.0%

