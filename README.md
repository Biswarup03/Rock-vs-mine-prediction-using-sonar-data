# Rock vs Mine Prediction Dashboard

This repository contains a **Streamlit web application** that predicts whether an object detected by sonar is a **Rock (R)** or a **Mine (M)**. The app uses a **Logistic Regression** model trained on sonar data.

## Features

- **Single Prediction Mode:** Enter 60 sonar signal values manually or fill them randomly to predict Rock or Mine.
- **Bulk CSV Prediction:** Upload a CSV file with multiple samples and get predictions along with probabilities.
- **Model Evaluation:** View confusion matrix, classification report, and ROC curve for model performance analysis.
- **Dataset Overview:** Explore the sonar dataset and visualize class distribution.

## Technologies Used

- Python
- Streamlit
- scikit-learn
- pandas, numpy, matplotlib, seaborn, plotly

## How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/<your-github-username>/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction
