# Dynamic Real Estate Valuation

## Overview

This project employs time series algorithms and recurrent neural networks (RNNs) to leverage stock market and financial indicators, including the dollar index, for predicting the post-construction prices of houses in a neighborhood. The focus is on introducing a dynamic approach to real estate valuation through advanced predictive modeling.

## Dataset

This is the dataset proposed and introduces in this paper: "House price estimation from visual and textual features"
https://arxiv.org/pdf/1609.08399.pdf

Link to github repository:
https://github.com/emanhamed/Houses-dataset

This is a benchmark dataset for houses prices that contains both visual and textual information. Each house is represened by four images for bedroom, bathroom, kitchen and a frontal image of the house. This is the first dataset that contains images to be used for houses prices estimation. The dataset folder contains 2140 images, 4 images for each house. Also, it contains a text file that contains the textual metadata of the dataset. Each row in the file respesents the number of house in order. The numbers represent number of bedrooms, number of bathrooms, area of the house, zipcode and the price. 

## Features

- **Time Series Analysis:** Utilizes time series algorithms for forecasting post-construction house prices.
- **Financial Indicators:** Incorporates stock market and financial indicators, such as the dollar index, in the predictive modeling process.
- **Recurrent Neural Networks (RNNs):** Implements RNNs for capturing temporal dependencies in real estate data.

## Objectives

- Apply time series algorithms to predict the dynamic post-construction prices of houses.
- Integrate financial indicators to enhance the accuracy of real estate valuation models.
- Implement recurrent neural networks for capturing and leveraging temporal patterns in real estate data.

## Getting Started

### Prerequisites

- Check requirements.txt

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/dynamic-real-estate-valuation.git
   ```

2. Install dependencies:

   ```bash
   pip install requirements.txt
   ```

## Contributors

- SMBH

## License

This project is licensed under the MIT - see the LICENSE file for details.
