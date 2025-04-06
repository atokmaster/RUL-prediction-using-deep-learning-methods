# RUL Prediction Using Deep Learning Methods

This project presents a deep learning-based approach to predict the **Remaining Useful Life (RUL)** of **Electrical Submersible Pump (ESP)** machines. By leveraging various neural network architectures and their combinations, the model aims to support predictive maintenance strategies and reduce unexpected machine failures in industrial operations.

## 📌 Project Overview

This repository includes:
- Time-series data preprocessing tailored to ESP operations
- Implementation of deep learning models including:
  - CNN
  - LSTM
  - CNN + LSTM
  - CNN + CBAM
  - CNN + Transformer
  - CNN + CBAM + Transformer
  - LSTM + Transformer
  - CNN + LSTM + Transformer
- Evaluation based on standard regression metrics (MAE, MSE, RMSE, R²)
- Comparison of model performance

## 🔍 Best Model Performance

| Metric | Value |
|--------|-------|
| **Model** | CNN + LSTM + Transformer |
| MAE    | 35,076.42 |
| MSE    | 119.24 |
| RMSE   | 10.92 |
| R²     | 0.9286 |

## 📊 Model Comparison Summary

| Model                      | MAE         | MSE        | RMSE    | R²     |
|---------------------------|-------------|------------|---------|--------|
| CNN                       | 144,999.34  | 243.60     | 15.61   | 0.7049 |
| LSTM                      | 257,172.95  | 339.39     | 18.42   | 0.4766 |
| CNN + LSTM                | 84,681.89   | 185.18     | 13.61   | 0.8277 |
| CNN + CBAM                | 151,270.50  | 252.11     | 15.88   | 0.6922 |
| CNN + Transformer         | 176,275.06  | 299.81     | 17.31   | 0.6413 |
| CNN + CBAM + Transformer  | 53,985.09   | 161.28     | 12.70   | 0.8901 |
| LSTM + Transformer        | 69,928.02   | 181.30     | 13.46   | 0.8577 |
| **CNN + LSTM + Transformer** | **35,076.42** | **119.24** | **10.92** | **0.9286** |

## 📂 Dataset Information

The dataset used in this project is **classified** due to confidentiality and cannot be shared publicly. It contains operational time-series data from **Electrical Submersible Pump (ESP)** machines used in an industrial setting.

If you're interested in the dataset for **academic or research collaboration purposes**, feel free to contact me:

📧 Email: atokmaster128@gmail.com

*Note: Access may be subject to restrictions or institutional approval.*


## 📁 Repository Contents

- `rul-prediciton.ipynb`: The main notebook containing preprocessing, model training, and evaluation.
- `README.md`: Overview and documentation of the project.


