# Task 13 — PCA Dimensionality Reduction (AI & ML Internship)

## Objective
To understand how PCA reduces dimensionality while preserving maximum variance and how it affects model accuracy.

## Dataset
Used sklearn Digits dataset (8x8 images → 64 features)

## Steps Performed
1. Loaded and scaled dataset using StandardScaler
2. Applied PCA with 2, 10, 30, 50 components
3. Measured explained variance ratio
4. Trained Logistic Regression on original and reduced data
5. Compared accuracy
6. Visualized cumulative explained variance
7. Visualized 2D PCA scatter plot

## Results
- Original accuracy: (add your value)
- PCA (10/30 components) achieved similar accuracy with fewer features
- PCA (2 components) showed visible class separation but lower accuracy

## Conclusion
PCA effectively reduces features while maintaining performance. Around 30 components preserved most variance with minimal accuracy drop.


