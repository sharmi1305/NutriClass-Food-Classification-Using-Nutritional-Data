# NutriClass-Food-Classification-Using-Nutritional-Data
🍽️ Food Classification Using Nutritional Data
📌 Overview
This project aims to classify foods based on their nutritional attributes and preparation methods.
By using machine learning models, it predicts categories such as meal type (breakfast, lunch, dinner, snack), preparation method (raw, baked, fried, etc.), and dietary tags (vegan, gluten-free).

The system can be useful in health applications, dietary planning, and food delivery apps to automatically identify foods or recommend healthier alternatives.

📊 Dataset
The dataset contains nutritional and categorical attributes for different food items.

Features:

Nutritional values: Calories, Protein, Fat, Carbs, Sugar, Fiber, Sodium, Cholesterol, Glycemic Index, Water Content, Serving Size

Meal attributes: Meal Type (breakfast/lunch/dinner/snack), Preparation Method (raw/baked/fried/etc.)

Dietary restrictions: Is_Vegan, Is_Gluten_Free

Food_Name: Actual food label (Pizza, Burger, Donut, etc.)

⚙️ Project Workflow
Data Preprocessing

Handling categorical variables (Label Encoding / One-Hot Encoding)

Normalizing/scaling continuous features

Encoding boolean features

Exploratory Data Analysis (EDA)

Distribution of calories, carbs, fat, and other nutrients

Correlation heatmaps between nutrients

Class imbalance check for food categories

Model Building

Machine Learning Models: Logistic Regression, Random Forest, SVM, etc.

Neural Networks (optional extension)

Model Evaluation

Metrics: Accuracy, Precision, Recall, F1-score

Confusion Matrix to analyze misclassifications

Cross-validation & Hyperparameter Tuning (GridSearchCV)

Applications

Diet recommendation systems

Health apps for patients (diabetic, heart risk)

Food delivery platforms (auto-tagging meals)

📈 Results
Random Forest showed the highest accuracy due to its ability to handle non-linear relationships.

Balanced performance in classifying meal type and preparation method.

Some challenges remain for overlapping food groups (e.g., baked vs. fried items with similar nutritional profiles).

🚀 Future Improvements
Use deep learning models for better pattern recognition.

Apply dimensionality reduction (PCA/Autoencoders) to handle correlated features.

Integrate food image recognition with nutritional classification for multimodal learning.

Deploy the model as a REST API or integrate into a mobile diet planner app.

🛠️ Technologies Used
Language: Python

Libraries:

Data Processing: Pandas, NumPy, Scikit-learn

Visualization: Matplotlib, Seaborn

Modeling: Scikit-learn, TensorFlow/Keras (if extended)

Notebook: Jupyter
👨‍💻 Author
This project was developed as part of a Machine Learning assignment/project to apply classification techniques to real-world nutritional data.

