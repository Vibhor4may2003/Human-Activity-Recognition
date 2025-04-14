# 📱 Human Activity Recognition (HAR) Using Smartphones

This project focuses on recognizing human activities using data collected from smartphone sensors (accelerometer and gyroscope). The dataset used is the [Human Activity Recognition with Smartphones Dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones), which contains labeled data for activities performed by 30 subjects.

## 📊 Dataset Overview

- **Source:** [Kaggle: Human Activity Recognition with Smartphones Dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)
- **Participants:** 30 volunteers aged between 19 and 48 years
- **Activities:** Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying
- **Sensors:** Embedded accelerometer and gyroscope of a Samsung Galaxy S II smartphone
- **Sampling Rate:** 50Hz
- **Features:** 561 time and frequency domain variables
- **Total Records:** 10,299

## 📁 Project Structure

har-smartphone/ ├── data/ # Dataset files ├── notebooks/ # Jupyter notebooks for EDA and modeling ├── models/ # Trained models ├── src/ # Source code │ ├── preprocess.py # Data preprocessing │ ├── train.py # Model training │ └── evaluate.py # Evaluation metrics ├── requirements.txt # Python dependencies └── README.md # Project documentation


## 🛠️ Features

- Data preprocessing and normalization
- Exploratory Data Analysis (EDA)
- Machine learning models (Random Forest, SVM, KNN)
- Model evaluation (accuracy, confusion matrix, classification report)

## 📈 Results

- **Best Model:** Random Forest
- **Accuracy:** 93.8%
- **F1 Score:** 93.5%

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/har-smartphone.git
cd har-smartphone

### 2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt

### 3. Run the project
bash
Copy
Edit
python src/train.py

🧪 Tests
bash
Copy
Edit
pytest tests/



