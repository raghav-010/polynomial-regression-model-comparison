# Polynomial Regression Model Comparison

Machine Learning project demonstrating Polynomial Regression using a Scikit-Learn Pipeline. This project compares multiple polynomial degrees using Mean Squared Error (MSE) and R² Score to analyze model complexity, underfitting, overfitting, and generalization.

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
      PolynomialFeatures
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
|:------:|---------:|---------:|-------------|
| 1 | 2.2551 | 0.5252 | Underfitting |
| 2 | 0.5571 | 0.8827 | Good Fit |
| 5 | 0.5551 | 0.8831 | Best Model |
| 10 | 0.7649 | 0.8389 | Beginning to Overfit |

## Key Learnings

- Built a complete Machine Learning pipeline
- Applied PolynomialFeatures to capture nonlinear relationships
- Used StandardScaler for feature scaling
- Trained and evaluated Linear Regression models
- Compared multiple polynomial degrees
- Understood underfitting, good fit, and overfitting
- Selected the best model based on generalization rather than training performance

## Future Improvements

- Perform Cross-Validation for more reliable evaluation
- Visualize fitted regression curves
- Apply the workflow to real-world datasets
- Experiment with additional regression algorithms
