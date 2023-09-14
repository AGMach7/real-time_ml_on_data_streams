# Streaming Intelligence: Real-time Machine Learning on Data Streams

<!-- [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/AGMach7/real-time_ml_on_data_streams/blob/main/LICENSE) -->

<!-- ## Project Overview -->

The project embodies our mission at [3D Smart Factory](https://3dsmartfactory.csit.ma/) to harness real-time data analysis for a critical financial challenge - predicting the closing value of the IBM stock market. In today's fast-paced financial landscape, informed investment decisions demand access to the most current data. Our project leverages cutting-edge machine learning algorithms to predict the IBM stock's closing value in real-time, empowering investors, traders, and financial analysts with a dynamic decision-making tool.

## Key Objectives

The primary objectives of this project include:

- Real-time Predictions: Develop a system capable of providing real-time predictions for the closing value of the IBM stock market, enabling users to stay ahead of market trends.

- Machine Learning Integration: Utilize advanced machine learning algorithms to analyze historical data, identify patterns, and generate accurate predictions.

- Data Stream Processing: Implement efficient data stream processing techniques to handle continuous and high-velocity data from the stock market.

- Performance Evaluation: Rigorously assess the accuracy and reliability of the prediction model through comprehensive performance evaluation.

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
   python3 C:\path\to\your\project\3D\main.py

## What's Next

Our vision extends beyond this project. We're looking to build a user-friendly interface and explore predictions for additional stock symbols, extending our reach beyond IBM's daily stock market data.

## Acknowledgments

First and foremost, I want to express my heartfelt gratitude to Mr. Bertin for guiding our team throughout this journey with his invaluable expertise, patience, and unwavering support. I'd also like to extend my thanks to each member of my team for their dedication, teamwork, and passion, which created an exceptional work environment. Lastly, a big thank you to the entire 3D Smart Factory family for giving us the opportunity to contribute to such innovative and exciting projects. Your support has enriched our professional knowledge and skills.

## Let's Connect

If you're interested in learning more about our project or discussing potential collaborations, please don't hesitate to reach out. I'm always eager to connect with fellow professionals who share our passion for innovation.