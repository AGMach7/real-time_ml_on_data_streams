# Streaming Intelligence: Real-time Machine Learning on Data Streams

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/AGMach7/real-time_ml_on_data_streams/blob/main/LICENSE)

## Project Overview

### 1. Introduction

The project, titled "*Real-time Machine Learning on Data Streams*", embodies the pursuit of harnessing the power of real-time data analysis and predictive modeling to address a crucial financial challenge - predicting the closing value of the IBM stock market.

In today's fast-paced financial landscape, making informed investment decisions requires access to the most current and relevant data. The project is driven by the mission to provide investors, traders, and financial analysts with a cutting-edge tool that leverages machine learning to predict the closing value of the IBM stock, thus facilitating better decision-making in the dynamic world of stock trading.

### 2. Objectives

The primary objectives of this project include:

- Real-time Predictions: Develop a system capable of providing real-time predictions for the closing value of the IBM stock market, enabling users to stay ahead of market trends.

- Machine Learning Integration: Utilize advanced machine learning algorithms to analyze historical data, identify patterns, and generate accurate predictions.

- Data Stream Processing: Implement efficient data stream processing techniques to handle continuous and high-velocity data from the stock market.

- Performance Evaluation: Rigorously assess the accuracy and reliability of the prediction model through comprehensive performance evaluation.

### 3. Background Information

In the age of big data and rapid technological advancements, financial markets are increasingly influenced by vast volumes of data generated in real-time. Accurately predicting stock prices, especially for a significant player like IBM, presents both a challenge and an opportunity.

This project builds upon previous work in real-time data analytics, machine learning, and financial forecasting. It seeks to apply and extend these concepts to the domain of stock market prediction, providing investors with an intelligent tool to make informed decisions.

As we delve into the main steps of this project, including data collection, analysis, and model building, we will explore the methodologies and techniques employed to achieve our objectives. The subsequent sections will provide detailed insights into each aspect of the project, aiming to deliver not only predictions but also a deeper understanding of the underlying dynamics of the IBM stock market.

## Requirements

- confluent_kafka
- matplotlib
- numpy
- pandas
- pmdarima
- requests
- scikit-learn
- scipy
- statsmodels
- urllib3

To install all project dependencies, you can run the following command:

```bash
pip install -r requirements.txt
```

This will ensure that all the necessary libraries and packages are installed for your project.

## Prerequisites and Installations

To use this program, carefully follow these steps:

### 1. Installation and Configuration of Confluent Cloud Kafka

For detailed instructions on how to install and configure Confluent Cloud Kafka, please refer to [readme.txt](readme.txt) or [resources/resources.txt](resources/resources.txt).

### 2. Installation and Configuration of Jenkins

For a step-by-step guide on installing and configuring Jenkins, please consult [readme.txt](readme.txt) or [resources/resources.txt](resources/resources.txt).

### 3. Running a Test

- Make sure you have configured the configuration files, and that you have defined the "path" variable in the main.py and sendMail.py files.
- To run a test, click "Build Now" from the Jenkins dashboard. You can then click on the build number or date to view details, or click "Console Output" to see the launch details in the console.
- You can also run a test from a terminal (Windows cmd, etc.) using the following command:

   ```bash
   python3 C:/path/to/your/project/3D/main.py
   ```

Make sure to keep this guide handy for future reference, and keep all API keys and sensitive information secure.

## Contributing

If you welcome contributions from other developers, explain how they can contribute to your project. Include guidelines for pull requests and code style.

## License

This project is licensed under the MIT License

## Acknowledgments

Acknowledge and thank your team, mentors, or anyone who contributed to the project's success.