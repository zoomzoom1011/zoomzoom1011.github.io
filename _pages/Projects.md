---
layout: archive
title: "Projects"
permalink: /Projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

======

* Recommendation System Based on YouTube Review
  * Built a machine learning model in Spark to classify users based on their comments to YouTube videos
  * Preprocessed data by removing missing values and labeled part of users based on their comments
  * Processed user comments via RegexTokenizer and Word2Vec in SparkML
  * Trained logistic regression and random forest models and tuned hyper parameters and selected the best model based on k-cross validation
  * Extracted features with term frequency approach to obtain important topics of target users

* Amazon Prime Video View Time Exploration and Prediction

  * Worked on Amazon Prime data set and built a forecast model in Python to predict video view time.
  * Performed exploratory data analysis and preprocessed raw sales and product data via dealing with handling values, categorical feature encoding and feature scaling.
  * Built linear regression, random forest and XGBoost and evaluated the models through multiple metrics.
  * Selected the best model based on RMSE (best:8571) and identified the key factors (video position) for view time performance.



* Philadelphia Crime Analysis in Apache Spark

  * Performed spatial and time series analysis for a 6-year dataset of reported incidents from Philadelphia government website.
  * Build data processing pipeline based on Dataframe and Spark SQL for big data OLAP.
  * Trained and fine-tuned an ARIMA model to forecast the number of incidents (MSE:4199).
  * Explored and visualized the variation of the spatial distribution of incidents over time.


* Movie Recommendation Engine Development in Apache Spark

  * Built data ETL pipeline to analyze movie rating dataset and conducted online analytical processing with Spark SQL.
  * Implemented Alternative Least Square model to provide personalized movie recommendations and developed user-based approaches to handle system cold-start problems.
  * Conducted model hyper-parameters tuning with Spark ML cross-evaluation toolbox and monitored data processing performance via Spark UI on Databricks.(test RMSE: 0.87)


* Financial Anomaly Detection and Risk Analysis

  * Developed supervised and unsupervised(Isolation Forest and Distribution based) models in Python to predict loan risks.
  * Performed exploratory data analysis on large transaction dataset and preprocessed data by removing duplicates, encoding categorical features and handling imbalanced labeled data by SMOTE and Near Miss.
  * Selected the best sampling method based on recall score (best 0.99).


* Auto-Encoder-Decoder and Embedding Framework in Click Prediction

  * Performed analysis on Click-Through data and built an auto-encoder-decoder in Python to predict Click-Through rate.
  * Preprocessed data by removing missing values, data exploration and splitting data into train and test datasets on Spark.
  * Built and trained a wide and deep learning model with hidden layers and embedding layers.
  * Evaluated models(DeepFM, wide and deep) based on its performance on test datasets(best AUC 0.73).Semantic analysis for YouTube user comments dataset

* Natural Language Processing and Topic Modeling on User Review Dataset

  * Clustered customer reviews into groups and discovered the latent semantic structures using Python
  * Preprocessed review text by tokenization, stemming, removing stop words and extracted features by Term frequency - Inverse Document Frequency (TFlDF).
  * Trained unsupervised learning models of K-means clustering and Latent Dirichlet Analysis.
  * Identified latent topics and keywords of each review for clustering.
  * Visualized model training results by dimensionality reduction using Principal Component Analysis (PCA)


* Stanford Car Classification
  * Trained AlexNet, VGGNet and ResNet models for transfer learning and tuned hyper parameters and selected the best model. 
  * Tried different transformation and data augmentation for better performance.
  * Evaluated the model by test dataset accuracy and single images. 
