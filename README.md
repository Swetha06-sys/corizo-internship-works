## Project Compilation README

# Overview
This README file covers two distinct projects:
 1. A major capstone project focused on developing a machine learning classifier for semiconductor manufacturing yield prediction.
 2. A minor project involving the analysis of the NHANES dataset using numpy and matplotlib.

1. **Semiconductor Manufacturing Yield Classifier**
**Domain:** Semiconductor Manufacturing Process
**Context:** Modern semiconductor manufacturing processes are monitored using a variety of signals collected from sensors and measurement points. Not all signals are equally valuable, and feature selection is essential to identify the most relevant signals. This project aims to use these signals to predict yield type, identify key factors affecting yield, and improve process throughput and cost efficiency.

**Data Description:**
  * Dataset: signal.csv
  * Shape: (1567, 592)
  * Features: 591 features and 1 target column. The target column has values “-1” for pass and “1” for fail.
  * Project Objective: Build a classifier to predict the pass/fail yield and analyze feature relevance to determine if all features are necessary. 