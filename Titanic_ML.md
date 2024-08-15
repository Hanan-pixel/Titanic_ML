# Titanic Machine Learning Project

## Overview

This project involves building a machine learning model to predict the survival of passengers on the Titanic using the dataset provided. We will explore the data, preprocess it, and train a Logistic Regression model to make predictions.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Loading](#data-loading)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Model Building](#model-building)
6. [Model Evaluation](#model-evaluation)
7. [Conclusion](#conclusion)

## Introduction

The Titanic dataset contains information about passengers on the Titanic, including features such as age, sex, class, and whether they survived. The goal is to build a model to predict survival based on these features.

## Data Loading

Load the data using Pandas:

```python
import pandas as pd

# Load the Titanic dataset
data = pd.read_csv('path/to/train.csv')

