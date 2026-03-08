# Predictive Maintenance Engine
Real-time Remaining Useful life prediction for industrial equipment using deep learning, survival analysis, and streaming pipelines.

## Project Status
In Progress

## Completed 
- Exploratory Data Analysis on NASA C-MAPSS FD001 dataset
- RUL label engineering with piecewise linear degradation
- Sensor selection (14 of 21 sensors retained based on variance analysis)
- Degradation pattern analysis and onset detection
- Operating condition analysis

## Coming Next
- Feature engineering (rolling statistics, health index, cross-sensor features)
- Model development (XGBoost, LSTM, TCN, Survival Analysis)
- Anomaly detection
- Real-time streaming pipeline
- API deployment
- Monitoring dashboard

## Dataset
NASA C-MAPSS Turbofan Engine Degradation Simulation
- Source: [NASA Prognostics Center](https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data/resource/5224bcd1-ad61-490b-93b9-2817288accb8)
- Also available on [Kaggle](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps)

## Tech Stack
Python | pandas | NumPy | matplotlib | seaborn | plotly | scikit-learn | 
XGBoost | PyTorch | lifelines | SHAP | FastAPI | Kafka | Redis | Docker | 
MLflow | Streamlit | GitHub Actions

