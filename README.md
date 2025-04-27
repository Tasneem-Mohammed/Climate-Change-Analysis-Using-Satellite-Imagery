# Deep Learning Project | Climate Change Analysis Using Satellite Imagery: Temperature Time-Series and Forecasting

## Project Objective
Forecast temperature changes across **Africa, South America, Europe, and Asia** using satellite imagery and deep learning models.
![download](https://github.com/user-attachments/assets/bf285242-6f0a-4e85-a7aa-6a15830c2293)

## Features
- Multi-continent analysis using Google Earth Engine data
- 40+ years of ERA5 daily temperature data (1979-2020)
- Three deep learning architectures compared (TCN, RNN, GRU)
- Best model achieved 0.0000654 MSE on test data
- Interactive visualizations of predictions vs actuals

## Results Summary
Model | Training MSE | Test MSE (South America)
--- | --- | ---
TCN | 0.00021 | 0.00018
RNN | **0.0000654** | **0.0000418**
GRU | 0.0000681 | 0.0000507

![download (1)](https://github.com/user-attachments/assets/21fc7e9a-4867-4fbd-857b-ae039a6aae28)
## Installation
```bash
pip install -r requirements.txt
