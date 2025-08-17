# Diabetes Prediction Project

A simple machine learning project that predicts if someone has diabetes or not using health data.

## What does this project do?

This project uses 4 different AI models to predict diabetes. It compares which model works best.

## Dataset

- **768 patients** with health information
- **8 health features** like age, glucose level, BMI
- **Goal**: Predict if someone has diabetes (Yes/No)

## Models Used

1. XGBoost
2. Random Forest  
3. Logistic Regression
4. SVM

## How to run

### Step 1: Install required packages
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

### Step 2: Run the code
1. Download the notebook file
2. Open in Jupyter Notebook
3. Run all cells from top to bottom

## Results

All models get around **75-80% accuracy**. XGBoost usually performs best.

## What the code does

1. **Load data** - Gets patient health information
2. **Clean data** - Fixes missing values
3. **Train models** - Teaches AI to predict diabetes
4. **Compare models** - Shows which one works best
5. **Make predictions** - Predicts for new patients

## Example Usage

```python
# Predict diabetes for a new patient
patient = [2, 120, 70, 25, 100, 25.0, 0.5, 30]
result = "Diabetes" or "No Diabetes"
```

## Files Needed

- `diabetes_prediction.ipynb` - Main code file
- Internet connection (to download data)

## Important Features

- Glucose level is the most important predictor
- Age and BMI also matter a lot
- All models work pretty well (80%+ accuracy)

## For Beginners

This project is perfect for learning:
- How to clean messy data
- How to compare different AI models
- How to make predictions with machine learning
- How to create charts and graphs

---

**Note**: This is for learning purposes only. Always ask a doctor for real medical advice!
