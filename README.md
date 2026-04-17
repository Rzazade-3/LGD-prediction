1️⃣ Data Loading
Dataset was loaded using Pandas
2️⃣ Descriptive Data Analysis
Summary statistics analyzed using .describe()
Key metrics reviewed:
Mean
Median
Standard deviation
Min / Max values
3️⃣ Missing Value Analysis
Missing values checked using .isnull().sum()
Columns with missing data identified for further processing
4️⃣ Outlier Detection & Treatment
Outliers detected using IQR (Interquartile Range) method
Applied capping technique:
Lower bound = Q1 − 1.5 × IQR
Upper bound = Q3 + 1.5 × IQR
5️⃣ Feature Engineering
Created new features to improve model performance
Captured group-based behavioral patterns
6️⃣ Exploratory Data Analysis (EDA)
Distribution of variables analyzed using:
Boxplots
Histograms
Relationships explored between variables
Kolmogorov-Smirnov test applied to check normality
7️⃣ Correlation Analysis
Used Spearman correlation to measure relationship with target (LGD)
Identified:
Strong predictors
Weak predictors
8️⃣ Feature Selection
🔹 Step 1: Target Correlation
Selected features with significant correlation with LGD
🔹 Step 2: Intercorrelation Removal
Removed highly correlated independent variables
🔹 Step 3: Multicollinearity Check (VIF)
Applied Variance Inflation Factor (VIF)
Removed variables with high VIF values
9️⃣ Data Transformation
🔸 Encoding
Applied One-Hot Encoding for categorical variables
🔸 Scaling
Applied StandardScaler to normalize numerical features
🔟 Train-Test Split
Dataset split into training and testing sets (80/20)
1️⃣1️⃣ Model Building
Built Linear Regression model
Trained using training dataset
1️⃣2️⃣ Model Evaluation

Model performance evaluated using:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score

Additionally:

Feature-wise analysis performed to evaluate impact of individual variables
1️⃣3️⃣ Final Model Optimization
Model refined using selected high-quality features
Improved overall performance and stability
1️⃣4️⃣ Deployment Simulation
New dataset used for prediction
Applied same preprocessing pipeline:
Feature engineering
Encoding
Outlier handling
Generated final predictions
