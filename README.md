SVM Classification - Breast Cancer Dataset 🩺
This project applies Support Vector Machine (SVM) classification on the Breast Cancer Wisconsin dataset to predict whether a tumor is **malignant** or **benign**.

✅ Objectives
1. Load and prepare the dataset
2. Encode target and scale features
3. Train SVM with:
   - Linear kernel
   - RBF kernel
4. Visualize decision boundaries (2D)
5. Tune hyperparameters using `GridSearchCV`
6. Evaluate performance using cross-validation

🛠 Tools & Libraries
- `pandas`, `numpy`, `matplotlib`
- `sklearn` (SVC, PCA, GridSearchCV, cross_val_score)

🖼 Visuals
- 2D decision boundary using `radius_mean` and `texture_mean`
- Accuracy reports for both kernels
- Elbow method for hyperparameter tuning

🧪 Evaluation
- Accuracy Score
- Classification Report
- Cross-Validation (5-fold)
- GridSearchCV to find best `C` and `gamma`
