
# Agriculture Crop Production Prediction

## About
This project explores agricultural crop data using Python,
data analysis, visualization, and machine learning.

The current experiment predicts the 2010-11 production
value using historical production, area, and yield features
from 2006-07 to 2009-10.

## Tools
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Workflow
1. Load and inspect the dataset.
2. Clean column names.
3. Visualize crop trends.
4. Prepare features and prediction target.
5. Train a Linear Regression model.
6. Evaluate predictions using MAE, RMSE, and R².
7. Compare against a mean baseline.
8. Perform five-fold cross-validation.

## Initial Results

| Metric | Result |
|---|---:|
| Test MAE | 35.84 |
| Test RMSE | 49.81 |
| Test R² | 0.697 |
| Average CV MAE | 33.29 |
| Average CV R² | 0.535 |

## Limitations
- The dataset contains only 55 crop records.
- Cross-validation scores vary across folds.
- Measurement units need confirmation from the original source.
- Results are preliminary, not production-ready predictions.

## Files
The Jupyter Notebook contains the code, visualizations,
model training, and evaluation.
