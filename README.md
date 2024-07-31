# Sentiment-Analysis-on-Amazon-Reviews-with-LSTM

---

## Overview

This project involves building a Long Short-Term Memory (LSTM) neural network to perform sentiment analysis on social media posts, customer reviews, or similar text data. By leveraging LSTM networks, which are adept at handling sequential data, the goal is to accurately classify text into sentiment categories such as positive or negative. The project Amazon Reviews to train and evaluate the model, focusing on capturing the context and nuances of sentiment in the text.

## Usage

1. **Setup:**
   - Install the necessary libraries using:
     ```bash
     pip install numpy pandas tensorflow scikit-learn
     ```
   - Ensure TensorFlow is installed. Refer to the [TensorFlow installation guide](https://www.tensorflow.org/install) for setup instructions.

2. **Data Preparation:**
   - Download and load the dataset.
   - Preprocess the data by splitting it into training and testing sets, tokenizing text, and padding sequences to a uniform length.

3. **Model Building:**
   - Construct an LSTM model using TensorFlow.
   - Experiment with different configurations, including network layers, activation functions, and learning rates, to optimize the model’s performance.

4. **Model Training and Evaluation:**
   - Train the LSTM model on the training data and evaluate its performance on the test set.
   - Assess the model using metrics such as accuracy, precision, recall, and F1 score, and use confusion matrices to visualize performance across sentiment classes.

## Contributors
**This project was made by**

[Omar (Ven)](https://github.com/VenStudio)

*This project was made for a course from [ElectoPI](https://alcamp.electropi.ai/)*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
