1️⃣ Data Loading
2️⃣ Descriptive Data Analysis
3️⃣ Missing Value Analysis
4️⃣ Outlier Detection & Treatment
5️⃣ Feature Engineering
6️⃣ Exploratory Data Analysis (EDA)
Distribution of variables analyzed using:
Boxplots
Histograms
Relationships explored between variables
Kolmogorov-Smirnov test used to check normality
7️⃣ Correlation Analysis
Used Spearman correlation to measure relationship with target (LGD)
Identified:
Strong predictors
Weak predictors
8️⃣ Feature Selection
Step 1: Target Correlation
Selected features with significant correlation with LGD
Step 2: Intercorrelation Removal
Removed highly correlated independent variables
Step 3: Multicollinearity Check (VIF)
Applied Variance Inflation Factor (VIF)
Removed variables with high VIF values
9️⃣ Data Transformation
 Encoding
Applied One-Hot Encoding for categorical variables
 Scaling
Applied StandardScaler to normalize numerical features
🔟 Train-Test Split
1️⃣1️⃣ Model Building
1️⃣2️⃣ Model Evaluation
Performance evaluated using:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score

Additionally:

Feature-wise analysis performed to evaluate impact of individual variables
1️⃣3️⃣ Final Model Optimization
1️⃣4️⃣ Deployment Simulation

