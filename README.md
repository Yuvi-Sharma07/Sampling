# Data Generation using Modelling & Simulation for Machine Learning

## Tool Used
SimPy – Python Discrete Event Simulation Library

## Simulation Description
A queue system representing a bank/call-center.

## Parameters

| Parameter     | Lower | Upper |
|--------------|--------|--------|
| arrival_rate | 1      | 10     |
| service_rate | 2      | 12     |
| servers      | 1      | 5      |
| sim_time     | 50     | 200    |

## Data
1000 simulations were run with random parameters.

## ML Models Compared
- Linear Regression  
- Ridge  
- Lasso  
- KNN  
- Decision Tree  
- Random Forest  
- Gradient Boost  
- SVR  
- XGBoost  

## Metrics
R², RMSE, MAE

## Best Model
The model with the highest R² and lowest RMSE is selected.

## Conclusion
Simulation-generated data can be effectively used to train machine learning models.
