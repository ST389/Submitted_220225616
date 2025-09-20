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


## Future Work

Human-annotated sentiment dataset for improved labeling quality.
Real-time sentiment API + live forecasting pipeline.
Explainable AI (SHAP/LIME) for interpretability.
Multi-asset and multilingual extension.
