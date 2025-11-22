# Workflow:-


1. Load Dataset & Display Basic Statistics (describe())
Goal: Understand the structure and summary of numerical features.
Workflow:
Import dataset (from UCI or sklearn.datasets.load_wine()).
Convert to a DataFrame for easier manipulation.

Use:
.head() → quick look
.info() → data types & missing values
.describe() → mean, std, min, max, quartiles

Identify:
range of features
skewness
potential outliers

2. Boxplot by Output Labels / Classes
Goal: Check how each chemical feature differs across wine classes.
Workflow:
Group data by target (Class 0, 1, 2).
Create boxplots feature-wise, separated by class.

Observe:
which features show high separation among classes
presence of outliers
variability inside each class
This helps understand discriminative features before modeling.

3. Scatterplot Using Two Variables
Goal: Visualize relationships between two selected features.
Workflow:
Select two important features such as:
Alcohol vs. Malic Acid
Color intensity vs. Hue
Plot a scatterplot and color points by class labels.

Observe:
clustering behaviour of classes
whether the two features show natural separation
feature correlation visually
Helps in understanding suitability for classification.

4. Plot Co-Variance / Correlation Matrix
Goal: Understand linear relationships among features.
Workflow:
Compute correlation matrix (df.corr()).
Plot using a heatmap.

Interpret:
strong positive correlations (close to +1)
strong negative correlations (close to –1)
features that are redundant or highly related
Useful for PCA and dimensionality reduction steps.

5. Data Scaling
Goal: Normalize features to similar scales before using PCA or distance-based algorithms.
Workflow:
Use Standardization (Recommended):
Mean = 0
Std = 1
e.g., StandardScaler
Apply scaling only on feature variables, not on class label.
Re-check scaled feature distribution (optional).
Scaling is crucial because PCA and KNN are sensitive to magnitude differences.

6. PCA for Better Class Separation
Goal: Reduce dimensionality & visualize if classes separate better in PCA space.
Workflow:
Apply PCA on the scaled data.
Keep:
First 2 principal components for visualization,
Or analyze explained variance ratio.

Plot:
PC1 vs PC2 scatterplot, colored by class.

Interpret:
PCA clusters → better separation compared to raw features.
Which components carry most variance.
PCA helps reveal hidden structure and simplifies classification tasks.
