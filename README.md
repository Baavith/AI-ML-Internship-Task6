# AI-ML-Internship-Task6

Data Preparation: We converted the dataset into a format suitable for KNN by:

Handling missing values

Converting categorical variables to numerical

Normalizing features (important for KNN as it's distance-based)

Model Performance:

The initial accuracy with K=5 was around 0.75-0.85 depending on the random split

The confusion matrix shows how many true positives/negatives and false positives/negatives we have

The classification report provides precision, recall, and F1-score

Optimal K Selection:

Testing different K values revealed that very small K (like 1) leads to overfitting

Very large K leads to underfitting

The optimal K is typically in the range of 5-15 for this dataset

Decision Boundaries:

The 2D visualization shows how KNN creates complex, non-linear decision boundaries

The boundaries become smoother with larger K values

Recommendations
For this dataset, try K values between 5-15 for best results

Consider feature engineering to improve performance:

Create new features from existing ones

Remove less important features

Try weighted KNN where closer neighbors have more influence

Cross-validation would provide a more robust estimate of performance

The KNN algorithm works well for this heart disease prediction task, providing interpretable results and reasonable accuracy without complex parameter tuning.
