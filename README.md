# Lotto-Max-Number-Predictor-RNN

## Precliam

***Just For FUN!!!***

## Introduction
This Python code uses a neural network with an LSTM layer to predict the next set of Lotto Max numbers based on past draws. The code is designed to work with data formatted as a list of dictionaries, where each dictionary corresponds to a single draw and contains the keys 'date' and 'values'.

## Installation
To use the code, you will need to have Python 3 installed, as well as the following libraries:

- [ ] NumPy
- [ ] TensorFlow
- [ ] Keras

## Usage
To use the code, follow these steps:

- Load your data into a list of dictionaries, where each dictionary corresponds to a single draw and contains the keys 'date' and 'values'.
- Preprocess the data by splitting it into input and output sequences and reshaping it for input to the LSTM layer.
- Train the LSTM model using the mean squared error (MSE) loss function and the Adam optimizer, with a customizable learning rate.
- Make a prediction for a future draw by inputting the last draw into the trained model and using the output to generate a list of predicted numbers.

## Contributing
If you would like to contribute to this project, please feel free to fork the repository and submit a pull request with your changes.

## License
This project is licensed under the Apache 2.0 or later License - see the LICENSE file for details.

## Author
Zeyong Jin
February 17, 2023
