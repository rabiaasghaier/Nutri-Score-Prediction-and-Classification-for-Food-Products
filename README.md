# Nutri-Score-Prediction-and-Classification-for-Food-Products
This project focused on developing a data-driven system to classify food products based on their nutritional quality using the Nutri-Score labeling system
🥗 Nutri-Score Prediction and Classification for Food Products

🎯 Goal: Predict the Nutri-Score (A to E) of food products using nutritional data and machine learning models.

# 🔍 Project Overview
This project focused on developing a data-driven system to classify food products based on their nutritional quality using the Nutri-Score labeling system. The Nutri-Score, adopted in several European countries, helps consumers make healthier food choices by providing an easy-to-understand score (from A to E) based on a product’s nutritional content.

# 🛠️ Methodology
To create a robust classification model, the following steps were taken:

Data Collection:
Nutritional data was sourced from Open Food Facts, a free and open database of food products from around the world. Thousands of product entries were collected across multiple categories (snacks, beverages, meals, etc.).

Data Preprocessing:

Cleaned missing and inconsistent values.

Standardized units (e.g., grams, kilocalories).

Filtered products with sufficient and relevant nutritional information.

Feature Engineering:

Extracted key nutritional indicators such as energy (kcal), sugar, saturated fat, salt, fiber, and protein.

Constructed new features to reflect the balance between “positive” and “negative” nutrients influencing the Nutri-Score.

Modeling:

Implemented multiple classification models including Logistic Regression, Random Forest, and Gradient Boosting Classifier using scikit-learn.

Used cross-validation and grid search to tune hyperparameters and prevent overfitting.

Evaluation:

Assessed model performance using accuracy, precision, recall, and confusion matrix.

Achieved strong classification performance, particularly with the Gradient Boosting model, which provided the best balance across all score categories (A to E).

Visualization:

Used Matplotlib and Seaborn to generate insightful visualizations showing the distribution of nutrients per Nutri-Score and the classification performance of each model.

# 🔧 Technologies Used
Python (Pandas, NumPy, Scikit-learn)

Matplotlib & Seaborn for data visualization

Open Food Facts API for data extraction

Jupyter Notebook for analysis and documentation

# 📈 Key Insights
Most products rated Nutri-Score C represented an average balance of nutrients, while scores A and E reflected extremes in health quality.

Sugars and saturated fats were strong predictors of lower Nutri-Scores, while fibers and proteins influenced higher scores.

Machine learning models can effectively replicate public health labeling systems and be used to audit, compare, or recommend food products at scale.

# 🎓 Key Learnings
Practical implementation of a real-world classification problem with public health impact.

Importance of thoughtful feature engineering and data preprocessing.

Experience in model evaluation and selection based on interpretable metrics.

Using open data sources to build scalable and meaningful applications.
