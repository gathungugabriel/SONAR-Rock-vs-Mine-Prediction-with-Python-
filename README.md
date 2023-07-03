# Random Forest Classification Prediction System

This project demonstrates the implementation of a prediction system using Random Forest classification. It utilizes the scikit-learn library in Python to train a Random Forest classifier on a given dataset and make predictions on new samples.

## Project Overview

The main goal of this project is to showcase the usage of the Random Forest classifier for classification tasks. The project consists of the following components:

1. Dataset: The dataset used for training and evaluation. It should contain a set of features and corresponding target values for classification.

2. Model Training: The Random Forest classifier is trained on the provided dataset using the scikit-learn library.

3. Prediction System: A prediction system is implemented to make predictions on new samples using the trained Random Forest classifier.

## Requirements

- Python 3.x
- scikit-learn library

## Installation

1. Clone the repository:

```shell
git clone https://github.com/your-username/random-forest-prediction.git

Navigate to the project directory:
cd random-forest-prediction

Install the required dependencies:
pip install -r requirements.txt

Usage
Prepare your dataset: Replace the file dataset.csv with your own dataset file. Ensure that the dataset contains the appropriate features and target values for classification.

Train the Random Forest classifier: Run the train_model.py script to train the classifier on the provided dataset. The trained model will be saved as random_forest_model.pkl.

Make predictions: Use the predict_sample.py script to make predictions on new samples. Modify the sample variable in the script with your desired sample data, and run the script. The predicted class for the sample will be displayed.

Inspiration
This project was inspired by Siddhardhan's YouTube video tutorial on building a using Logistic Regression Model classifier. You can find the tutorial [here](https://www.youtube.com/watch?v=fiz1ORTBGpY&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6). We implemented the concepts and techniques discussed in the tutorial to create this prediction system.

Contributing
Contributions to this project are welcome. If you have any ideas or suggestions, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
