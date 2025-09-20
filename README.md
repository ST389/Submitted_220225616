
Final Year Project – CM3070, BSc Computer Science
University of London, April - Sep 2025

## Project Title

Hybrid NLP and Time-Series Model for S&P 500 Forecasting Using News Headlines

Overview

This project explores the integration of Natural Language Processing (NLP) and time-series forecasting for predicting short-term movements of the S&P 500 index.

The pipeline combines sentiment analysis of financial news headlines using transformer-based models (RoBERTa and BERT) with historical OHLCV stock data modeled via Long Short-Term Memory (LSTM) neural networks.

The core hypothesis: financial news sentiment provides predictive signals that improve forecasting performance compared to numerical stock data alone.

## Key libraries used:

transformers (Hugging Face)

tensorflow / keras

scikit-learn

pandas, numpy

matplotlib, seaborn

## Evaluate Models

Evaluation metrics include:

Sentiment Classifier → Accuracy, Precision, Recall, F1

LSTM Forecaster → RMSE, MAE, Directional Accuracy

├── All_Headlines_data/               # Raw & processed datasets
│   ├── guardian_headlines.csv
│   ├── reuters_headlines.csv
│   ├── cnbc_headlines.csv
│   ├── combined.csv
│   ├── combined2.csv
│   ├── SPX.csv
│   ├── SPX_clean.csv
│
├── notebooks/                     # Development & experiments
│   ├── Dataset Construction and Preparation.ipynb
│   ├── MY_FYP_SEP2025.ipynb
│
├── models/                        # Trained models
│   ├── lstm_model.h5
│   ├── BERTModel_Final/           # Fine-tuned BERT
│   └── RobertaModel_Final/        # Fine-tuned RoBERTa
│
│
├── report/                        # Documentation
│   ├── Final_Year_Project_Report.pdf
│   ├── Appendices
│ 
│
├── README.md


## Future Work

Human-annotated sentiment dataset for improved labeling quality.
Real-time sentiment API + live forecasting pipeline.
Explainable AI (SHAP/LIME) for interpretability.
Multi-asset and multilingual extension.
