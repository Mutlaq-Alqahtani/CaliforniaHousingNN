# CaliforniaHousingNN

This repository contains my work on developing and evaluating a neural network model to predict housing prices using the California Housing dataset.

## **Project Overview**
I created a complex neural network model to predict median house values based on various features like median income, house age, average rooms, and more. The model includes advanced features such as batch normalization, dropout, and multiple hidden layers to enhance its learning capability and generalization.

## **Model Architecture**
- **Input Layer:** 8 input features
- **Hidden Layers:**
  - **Layer 1:** 128 neurons, Batch Normalization, ReLU activation, Dropout (30%)
  - **Layer 2:** 256 neurons, Batch Normalization, ReLU activation, Dropout (30%)
  - **Layer 3:** 128 neurons, ReLU activation
  - **Layer 4:** 64 neurons, ReLU activation
- **Output Layer:** 1 output neuron for the predicted house value

## **Evaluation Metrics**
The model's performance was evaluated using the following metrics:

- **Test Loss:** 0.3663
- **R-squared:** 0.7230
- **Mean Squared Error (MSE):** 0.3663
- **Mean Absolute Error (MAE):** 0.4186

These metrics indicate that the model explains about 72.30% of the variance in the test data, with a low error rate.

## **Conclusion**
This project demonstrates the effectiveness of using a neural network with advanced techniques like batch normalization and dropout for predicting housing prices. The results are promising and show the model's capability to learn from and generalize to new data.
