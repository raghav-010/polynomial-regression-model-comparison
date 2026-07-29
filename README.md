# polynomial-regression-model-comparison

Machine Learning project that demonstrates Polynomial Regression using the Scikit-Learn Pipeline. The project compares different polynomial degrees using Mean Squared Error (MSE) and R² Score to understand model complexity, underfitting, overfitting, and generalization.

## Project Highlights

- Generated a synthetic quadratic dataset with Gaussian noise
- Visualized the dataset using a scatter plot
- Split the dataset into training and testing sets
- Built a Polynomial Regression pipeline
- Applied PolynomialFeatures and StandardScaler
- Trained Linear Regression models
- Evaluated model performance using MSE and R² Score
- Compared polynomial degrees (1, 2, 5, and 10)
- Identified underfitting, good fit, and overfitting
- Selected the best model based on test performance

## Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow

```text
          Generate Dataset
                 │
                 ▼
        Data Visualization
                 │
                 ▼
        Train-Test Split
                 │
                 ▼
        Create Pipeline
                 │
                 ▼
      Polynomial Features
                 │
                 ▼
       StandardScaler
                 │
                 ▼
      Linear Regression
                 │
                 ▼
        Model Training (fit)
                 │
                 ▼
      Model Prediction
                 │
                 ▼
    Model Evaluation (MSE & R²)
                 │
                 ▼
 Compare Polynomial Degrees
                 │
                 ▼
        Select Best Model
```

## Model Comparison

| Degree | Test MSE | Test R² | Observation |
|---------|---------:|---------:|-------------|
| 1 | 2.2551 | 0.5252 | Underfitting |
| 2 | 0.5571 | 0.8827 | Good Fit |
| 5 | 0.5551 | 0.8831 | Best Model |
| 10 | 0.7649 | 0.8389 | Beginning to Overfit |

## What I Learned

- Creating a complete Machine Learning pipeline
- Polynomial feature engineering
- Feature scaling using StandardScaler
- Training and evaluating regression models
- Comparing multiple models
- Understanding underfitting and overfitting
- Selecting models based on generalization instead of training performance

## Future Improvements

- Perform Cross-Validation
- Visualize fitted regression curves
- Apply the workflow to real-world datasets
