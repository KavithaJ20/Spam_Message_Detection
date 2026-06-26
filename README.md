# Spam Message Detection System using Machine Learning and Flask

## Project Overview

The Spam Message Detection System is a Machine Learning-based web application developed to classify text messages as **Spam** or **Ham (Legitimate)**. The system analyzes the content of incoming messages using Natural Language Processing (NLP) techniques and a trained Machine Learning model to provide accurate real-time predictions. A Flask web application offers a simple and interactive interface for users to test messages.

---

## Objectives

* Detect spam messages with high accuracy.
* Prevent users from receiving unwanted or fraudulent messages.
* Classify messages into Spam and Ham categories.
* Provide real-time predictions through a web application.
* Improve communication security using Machine Learning.

---

## Features

* Machine Learning-based spam detection.
* Real-time message classification.
* User-friendly Flask web interface.
* Fast and accurate prediction.
* Natural Language Processing for text preprocessing.
* Easy deployment on a local server.
* Scalable architecture for future enhancements.

---

## Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* Pandas
* NumPy

### Natural Language Processing

* NLTK
* TF-IDF Vectorizer

### Web Framework

* Flask

### Frontend

* HTML
* CSS
* Bootstrap

### Development Tools

* Visual Studio Code
* Jupyter Notebook
* Anaconda

---

## Project Structure

```
Spam-Message-Detection/
│
├── static/
│   ├── css/
│   ├── images/
│
├── templates/
│   ├── index.html
│
├── model/
│   ├── spam_model.pkl
│   ├── vectorizer.pkl
│
├── dataset/
│   ├── spam.csv
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
└── notebook.ipynb
```

---

## System Workflow

1. The user enters a text message through the web interface.
2. Flask receives the input message.
3. The message is preprocessed using NLP techniques.
4. The trained Machine Learning model analyzes the processed text.
5. The system predicts whether the message is:

   * Spam
   * Ham (Legitimate)
6. The prediction result is displayed instantly.

---

## Machine Learning Workflow

* Data Collection
* Data Cleaning
* Text Preprocessing
* Feature Extraction using TF-IDF
* Model Training
* Model Evaluation
* Model Serialization
* Flask Integration
* Real-Time Prediction

---

## Algorithms Used

The system can be trained using one or more of the following Machine Learning algorithms:

* Multinomial Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest Classifier

The best-performing model is saved and integrated into the Flask application for prediction.

---

## Installation

### Navigate to the Project

```bash
cd Spam-Message-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Input

The user enters a text message into the application.

Example:

```
Congratulations! You have won a free iPhone. Click here to claim your prize.
```

---

## Output

The system predicts one of the following:

* Spam
* Ham (Legitimate)

---

## Dataset

The project uses a labeled SMS dataset containing spam and legitimate messages. The dataset is preprocessed and converted into numerical features using TF-IDF vectorization before training the Machine Learning model.

---

## Future Enhancements

* Deep Learning-based spam detection using LSTM or BERT.
* Multi-language spam detection.
* Email spam classification.
* Real-time API integration.
* Cloud deployment.
* User authentication and message history.
* Continuous model retraining with new datasets.

---

## Requirements

* Python 3.10 or above
* Flask
* Scikit-learn
* Pandas
* NumPy
* NLTK
* Joblib

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## Conclusion

The Spam Message Detection System demonstrates the effective use of Machine Learning and Natural Language Processing to identify spam messages with high accuracy. By integrating the trained model with a Flask web application, the system provides a simple, efficient, and reliable solution for real-time spam detection.


