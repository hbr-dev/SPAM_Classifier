# 📱 SMS Spam Classification

## 📖 Overview
This project aims to develop a machine learning model that classifies SMS messages as either "ham" or "spam." "Ham" messages are normal texts sent by friends, while "spam" messages are unsolicited advertisements or communications from companies. The model will be trained on a labeled dataset to identify patterns and features, enhancing message filtering.

## 🔑 Key Features
- **Text Classification:** Utilizes machine learning algorithms to classify SMS messages accurately.
- **Data Preprocessing:** Implements techniques for cleaning and preparing text data for analysis.
- **Feature Extraction:** Uses methods like TF-IDF to convert text into numerical features suitable for model training.
- **Model Evaluation:** Assesses model performance using metrics such as accuracy, precision, recall, and F1-score.

## 📊 Dataset
The project uses a dataset containing labeled SMS messages, which includes both "ham" and "spam" categories. This dataset is essential for training and validating the classification model.

### Dataset File
- `train-data.tsv`: A CSV file containing SMS messages and their corresponding labels (ham or spam).

## 📊 Model Training

The project implements various machine learning algorithms, including:
- **Logistic Regression**
- **Naive Bayes**
- **Support Vector Machines (SVM)**

You can modify the train_model.py script to experiment with different algorithms and hyperparameters.

## 💻 Installation
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/hbr-dev/SPAM_Classification.git
   cd SPAM_classification

## 🛠️ Usage

To train the SMS classification model, run the following Python script:
   ```bash
   python train_model.py
   ```

This script will preprocess the data, extract features, and train the machine learning model.

To evaluate the model's performance on a test dataset, run:
   ```bash
   python evaluate_model.py
   ```

This script will output metrics such as accuracy, precision, recall, and F1-score.

