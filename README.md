# Life Expectancy Prediction

This notebook aims to predict life expectancy using a machine learning model. It utilizes a dataset containing various factors such as income, education, and healthcare to predict the average life expectancy of a country.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

In this notebook, we explore the relationship between different factors and life expectancy. We build a machine learning model to predict life expectancy based on these factors. The goal is to gain insights into the key determinants of life expectancy and create a predictive model that can be used for future predictions.

## Dataset

The dataset used in this project is sourced from [source_name]. It contains [number of samples] samples and [number of features] features. The features include [list of features]. The target variable is the average life expectancy.

## Usage

To run this notebook, you need to have [list of libraries] installed. You can install them using `pip`:

```bash
pip install numpy pandas matplotlib scikit-learn
```

You can run the notebook using Jupyter:

```bash
jupyter notebook  life_expectancy_prediction.ipynb
```

## Results

The results show that we have successfully built a linear regression model to predict life expectancy based on various factors.  
The model achieved an RMSE of 3.833 on the test set, indicating that it can predict life expectancy with reasonable accuracy.  
Despite trying polynomial features, they did not improve the model's performance. However, k-fold cross-validation showed consistent performance across different folds.  
This project provides valuable insights into the factors influencing life expectancy and demonstrates the effectiveness of linear regression models in predicting life expectancy.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
