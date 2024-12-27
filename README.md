# Blood Donation Prediction Analysis 🩸

## Overview
This project analyzes blood donation patterns using historical donor data to predict future donation behavior. The analysis includes comprehensive data visualization and statistical analysis to understand donor patterns and behaviors.

## Project Highlights ✨
- Analysis of 748 blood donation records
- Detailed statistical analysis of donor behavior
- Comprehensive visualization of donation patterns
- Focus on predicting March 2007 donations

## Dependencies 📚
```python
pandas
numpy
matplotlib
seaborn
```

## Dataset Description 📊
The dataset contains information about blood donation history with 748 entries and 5 features:

### Features:
- **Recency (months)**: Last time since donation
- **Frequency (times)**: Total number of donations
- **Monetary (c.c. blood)**: Total blood donated in c.c.
- **Time (months)**: Months since first donation
- **Donated Blood**: Whether they donated in March 2007 (DB: Donated, NDB: Not Donated)

## Data Quality Analysis 🔍
- No missing values in the dataset
- 215 duplicate entries identified
- Imbalanced dataset:
  - Not Donated Blood (NDB): 570 samples
  - Donated Blood (DB): 178 samples

## Statistical Analysis 📈

### Overall Statistics
- Mean donation recency: 9.51 months
- Average donation frequency: 5.51 times
- Mean blood quantity: 1378.68 c.c.
- Average donation timespan: 34.28 months

### Donor Group Analysis
#### Donated Blood (DB) Group:
- Mean recency: 5.46 months
- Average frequency: 7.80 times
- Mean monetary value: 1949.44 c.c.
- Standard deviation (recency): 5.16 months

#### Not Donated Blood (NDB) Group:
- Mean recency: 10.77 months
- Average frequency: 4.80 times
- Mean monetary value: 1200.44 c.c.
- Standard deviation (recency): 8.42 months

## Visualization Insights 📊

### Distribution Analysis
1. **PDF (Probability Density Function)**
   - Separate distributions for DB and NDB groups
   - All features show distinct patterns between groups

2. **CDF (Cumulative Distribution Function)**
   - Clear separation in recency patterns
   - Different accumulation rates between groups

### Box Plots and Violin Plots
- Show distribution differences between DB and NDB groups
- Highlight outliers in each feature
- Reveal density patterns in the data

### Scatter Plots and Joint Plots
- Demonstrate relationships between features
- Show clustering patterns of donor groups
- Reveal density distributions of combined features

## Key Findings 🔑
1. Recent donors (lower recency) are more likely to donate again
2. Frequent donors show higher probability of continued donation
3. Clear separation in donation patterns between DB and NDB groups
4. Time since first donation shows less influence on donation probability

## Future Improvements 🚀
1. Feature engineering to create more meaningful variables
2. Implementation of machine learning models for prediction
3. Cross-validation analysis
4. Handling of duplicate entries
5. Addressing class imbalance

