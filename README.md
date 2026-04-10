Data Preprocessing Project
📌 Overview
This project demonstrates essential data preprocessing techniques used in machine learning, specifically Standardization and Normalization. The implementation is performed on two well-known datasets:
Iris Dataset
Wine Dataset
The goal is to transform raw data into a structured format suitable for model training by scaling features appropriately.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 Key Features
Display of original dataset (first 5 rows) for understanding raw values
Implementation of Standardization (Z-score scaling)
Implementation of Normalization (Min-Max scaling)
Comparison between raw and transformed data
Clean and structured output for analysis
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
📂 Datasets Used
1. Iris Dataset
Contains features like:
Sepal Length
Sepal Width
Petal Length
Petal Width
2. Wine Dataset
Contains chemical properties such as:
Alcohol
Malic Acid
Ash
Magnesium
Flavanoids
Color Intensity
Proline, etc.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
⚙️ Working Workflow
Step 1: Load Dataset
Import datasets using libraries like sklearn or pandas
Convert data into DataFrame format for easy manipulation
Step 2: Display Original Data
Print the first 5 rows of the dataset
Helps in understanding feature distribution and scale differences
Step 3: Standardization (Z-score Scaling)
Apply StandardScaler
Output shows:
Mean ≈ 0
Standard deviation ≈ 1
Example (from output):
Values transformed into both positive and negative ranges
Step 4: Normalization (Min-Max Scaling)
Apply MinMaxScaler
Scales values between 0 and 1
Example (from output):
Values strictly within range [0, 1]
Step 5: Output Visualization
Display transformed datasets (first 5 rows)
Compare original vs scaled data
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Sample Output Explanation
🔹 Standardized Data (Iris Dataset)
Values are centered around 0
Negative values indicate below-average features
Positive values indicate above-average features
🔹 Normalized Data (Wine Dataset)
All values are scaled between 0 and 1
Maintains relative differences while compressing the range
🛠️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
📊 Why This Project Matters
Improves model performance
Ensures fair contribution of all features
Prevents bias due to large value ranges
Essential step in machine learning pipelines
Project Output Screenshots
🖼️ 1. Iris Dataset – Original vs Standardized Data

This output shows the original Iris dataset values and their transformed standardized values centered around 0.
<img width="892" height="412" alt="Screenshot 2026-04-10 143056" src="https://github.com/user-attachments/assets/b731627b-9ac9-4729-8197-f30040b0852e" />
Explanation:
The standardized data contains both positive and negative values, indicating how far each feature is from the mean in terms of standard deviation.
2. Wine Dataset – Original vs Normalized Data

This output displays the Wine dataset before and after normalization, where all values are scaled between 0 and 1.
<img width="988" height="790" alt="Screenshot 2026-04-10 143220" src="https://github.com/user-attachments/assets/fe502b04-95c7-40f5-ab9d-4729af48f000" />
Explanation:
The normalized data ensures all features fall within the same range [0,1], making it suitable for distance-based algorithms.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
📎 Conclusion

This project highlights the importance of preprocessing techniques like Standardization and Normalization in preparing datasets for machine learning models. Proper scaling ensures better accuracy, faster convergence, and improved model reliability.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
