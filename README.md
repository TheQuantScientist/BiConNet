## Introduction

This repository introduces an advanced model, termed BiConNet, employing a unique integration of Convolutional Neural Networks (CNN) and Bidirectional Long Short-Term Memory (BiLSTM) networks, enhanced with Time Delay Embedding, for the task of univariate stock price prediction. Designed to address the intricacies of financial time series data, our approach leverages the strength of CNNs to identify local patterns and BiLSTM to capture long-term dependencies in stock prices. Specifically tailored for univariate forecasting, this model aims to predict future stock prices using only a single variable - the historical stock prices, thereby simplifying the complex task of stock market prediction with high precision and efficiency.

## Project Overview

The complexity of stock markets, driven by numerous factors, makes them a prime target for econometric exploration and predictive analysis. The advent of Artificial Intelligence in the digital economy has spurred renewed interest in employing advanced Machine Learning models for accurate stock value predictions. This paper presents a novel approach that combines CNN-BiLSTM, a hybrid Deep Learning technique, with the Time Delay Embedding (TDE) method from Chaos Theory, to analyze stock market dynamics. Our model aims to significantly reduce forecasting errors, such as MAE and RMSE, for major technology stocks including AAPL, MSFT, and NVDA. It demonstrates that the CNN-BiLSTM framework significantly outperforms standalone models, and integrating the TDE method notably decreases MAE and RMSE by 33.47% and 31.67%, respectively, compared to conventional approaches. These results underscore TDE's remarkable efficiency in analyzing the complex, non-linear patterns of stock data, contributing to the development of more sophisticated algorithmic trading systems that  strengthens real-time analysis for future financial market analysis and forecasting.

## Features

- **Multivariate Forecasting Focus:** Specialized in predicting future stock prices using historical price data and multiple predictor variables within OHLCV datasets, simplifying data collection and preprocessing efforts.
- **CNN-BiLSTM Architecture:** Combines the pattern recognition capabilities of CNNs with the sequential data processing strength of BiLSTM networks for deep, nuanced understanding of price movements.
- **Time Delay Embedding Technique:** Utilizes embedding to enrich the model's input, enabling it to capture essential temporal patterns in a highly efficient manner.
- **Efficient and Accurate:** Designed to provide precise stock price forecasts while being computationally efficient, making it suitable for use in various computational environments.
  
## Technologies Used
- **Python:** For implementing the model and managing data processing.
- **TensorFlow and Keras:** Utilize these libraries for building and training the CNN-BiLSTM model.
- **Pandas and NumPy:** Essential for data manipulation and numerical computations.
- **Matplotlib:** For visualizing model performance and forecasting results.
- **Scikit-learn:** Used for data preprocessing, including normalization and performance metrics evaluation.

## Getting Started

To embark on using this model for your stock price prediction tasks, follow the detailed setup and training instructions provided in subsequent sections. This guide will walk you through the process of preparing your environment, processing your data, training the model, and evaluating its performance using key metrics such as MSE, MAE, and RMSE. This project has been rigorously tested on various datasets, including historical stock price data, demonstrating its capability to deliver accurate and efficient forecasts.
