# TaxiFarePrediction

This repository contains the TaxiFarePrediction project, which uses machine learning to predict taxi fares based on various trip features. The model is built with ML.NET and is trained on historical taxi trip data.

## Project Overview

The goal of this project is to accurately predict the fare of a taxi ride based on features like vendor ID, rate code, passenger count, trip distance, and payment type. The model is trained using the FastTree regression algorithm.

## How It Works

1. **Data Loading**: The dataset is loaded from CSV files containing historical taxi trip data.
2. **Model Training**: The model is trained using a regression pipeline that includes feature transformations such as one-hot encoding.
3. **Model Evaluation**: The model's accuracy is evaluated on test data using metrics like RSquared and Root Mean Squared Error.
4. **Prediction**: The model is used to predict the fare for new taxi trips based on the provided features.

## Getting Started

### Prerequisites

- .NET Core SDK
- ML.NET
- A dataset containing historical taxi trip data

### Running the Code

1. Clone this repository.
2. Place your training and test data in the `Data` folder.
3. Run the project to train the model and make predictions.

### Future Work

- Explore additional features such as time of day, traffic conditions, and weather data.
- Experiment with different machine learning models to improve accuracy.
- Deploy the model as a web service for real-time predictions.

## License

This project is licensed under the MIT License.
