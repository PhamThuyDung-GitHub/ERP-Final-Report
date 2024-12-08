# Big Mart Sales Analysis and Forecasting Report

## Objective

The primary objective of this report is to effectively manage and track sales data for individual items at **Big Mart**, a prominent retail chain. By analyzing historical sales data, we aim to:
- Forecast future client demand.
- Optimize inventory management strategies.
- Enhance competitiveness and maximize profitability.

## Approach

To achieve the above objectives, we plan to develop a sophisticated model that utilizes machine learning and deep learning techniques to accurately predict future sales patterns. By leveraging Big Mart's historical dataset, the model will provide actionable insights into:
- **Consumer Behavior**: Understanding purchasing patterns and preferences.
- **Market Trends**: Identifying key trends and shifts in demand.

## Key Benefits

The results of this analysis will:
- Help anticipate customer demands.
- Streamline inventory management.
- Improve overall business performance.

## Report Highlights

Forecasting accuracy is critical in predictive modeling. This project evaluates several machine learning models to determine which provides the most accurate predictions. Models tested include:
- **XGB** (Extreme Gradient Boosting)
- **ANN** (Artificial Neural Networks)
- **DNN** (Deep Neural Networks)
- **NAM** (Neural Additive Models)

## Evaluation Metrics

The following metrics were used to assess the performance of each model:
- **R²**: Coefficient of determination
- **MSE**: Mean Squared Error
- **RMSE**: Root Mean Squared Error
- **MAE**: Mean Absolute Error
- **MDAE**: Median Absolute Error

## Results

| Model | R² | MSE | RMSE | MAE | MDAE |
|-------|-----|---------|---------|---------|---------|
| **XGB** | 0.5191 | 77241828 | 1484501.750 | 1484501.750 | 774029 |
| **ANN** | 0.3382 | 64239938 | 0.0115 | 856.8717 | 576.9437 |
| **DNN** | 0.5923 | 89302618 | 1108193.969 | 1108193.969 | 750.2957 |
| **NAM**   | 0.6111 | 68539286 | 1056897.482 | 1028.0552 | 728.6470 |

## Conclusion

Based on the prediction error metrics, **ANN** is the best model with the smallest error values across all forecasting metrics.
