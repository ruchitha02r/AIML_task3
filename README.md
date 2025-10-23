# AIML_task3

## 🚀 Implementation Highlights

### 1. Data Analysis & Visualization
- Correlation heatmap analysis
- Feature-target relationship exploration
- Multicollinearity check using VIF

### 2. Model Implementation
- **Simple Linear Regression**: Using MedInc (median income) as single predictor
- **Multiple Linear Regression**: Using all 8 features
- Train-test split (80-20) with random state for reproducibility

### 3. Model Evaluation
| Model Type | MAE | MSE | R² Score |
|------------|-----|-----|----------|
| Simple LR | 0.6391 | 0.7097 | 0.4757 |
| Multiple LR | 0.5332 | 0.5559 | 0.5758 |

### 4. Key Findings
- **Multiple regression improved R² by 21%** over simple regression
- **MedInc** is the strongest predictor (correlation: 0.688)
- **AveOccup** has the weakest correlation with price (-0.024)
- No severe multicollinearity detected in features

## 📈 Visualizations
- Correlation heatmap with feature relationships
- Regression line plots for simple linear regression
- Actual vs Predicted scatter plots
- Residual analysis plots
- Feature importance charts
