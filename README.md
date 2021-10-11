# Product-Price-Prediction-A-Tidy-Hyperparameter-Tuning-and-Cross-Validation-Tutorial

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
======================

Product price estimation and prediction is one of the skills I teach frequently – It’s a great way to analyze competitor product information, your own company’s product data, and develop key insights into which product features influence product prices. Learn how to model product car prices and calculate depreciation curves using the brand new tune package for Hyperparameter Tuning Machine Learning Models. This is an Advanced Machine Learning Tutorial.
R Packages Covered

Machine Learning
==================

    1.tune – Hyperparameter tuning framework
    2.parsnip – Machine learning framework
    3.dials – Grid search development framework
    4.rsample – Cross-validation and sampling framework
    5.recipes – Preprocessing pipeline framework
    6.yardstick – Accuracy measurements

EDA
====

    1.correlationfunnel – Detect relationships using binary correlation analysis
    2.DataExplorer – Investigate data cleanliness
    3.skimr – Summarize data by data type

Summary (Why read this?)
=========================
Hyperparameter tuning and cross-validation have previously been quite difficult using parsnip, the new machine learning framework that is part of the tidymodels ecosystem. Everything has changed with the introduction of the tune package – thetidymodels hyperparameter tuning framework that integrates:

    1.parsnip for machine learning
    2.recipes for preprocessing
    3.dials for grid search
    4.rsample for cross-validation.

This is a machine learning tutorial where we model auto prices (MSRP) and estimate depreciation curves.

Depreciation Curves
=====================
Estimate Depreciation Curves using Machine Learning

To implement the Depreciation Curve Estimation, you develop a machine learning model that is hyperparameter tuned using a 3-Stage Nested Hyper Parameter Tuning Process with 5-Fold Cross-Validation.

Nested Hyperparameter Tuning Process with 5-Fold Cross Validation

3-Stage Nested Hyperparameter Tuning Process

3 Stage Hyperparameter Tuning Process:

    Find Parameters: Use Hyper Parameter Tuning on a “Training Dataset” that sections your training data into 5-Folds. The output at Stage 1 is the parameter set.

    Compare and Select Best Model: Evaluate the performance on a hidden “Test Dataset”. The ouput at Stage 2 is that we determine best model.

    Train Final Model: Once we have selected the best model, we train on the full dataset. This model goes into production.

Need to learn Data Science for Business? This is an advanced tutorial, but you can get the foundational skills, advanced machine learning, business consulting, and web application development using R, Shiny (Apps), H2O (ML), AWS (Cloud), and tidyverse (data manipulation and visualization).
