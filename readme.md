***# 🌲 Forest Cover Type Prediction***



***## 📌 Project Overview***



***This project uses Machine Learning to predict the \*\*forest cover type\*\* based on cartographic and environmental features.***



***The objective is to build a classification system that can identify one of \*\*7 forest cover types\*\* using geographical and environmental measurements.***



***---***



***## 🎯 Problem Statement***



***Forest ecosystems contain different types of vegetation depending on factors such as elevation, slope, soil characteristics, sunlight, and geographical conditions.***



***The goal of this project is to develop a Machine Learning model that can predict the \*\*Cover Type (1–7)\*\* from these environmental and cartographic features.***



***---***



***## 🎯 Objectives***



***- Perform exploratory data analysis (EDA)***

***- Clean and prepare the dataset***

***- Analyze relationships between features and forest cover types***

***- Apply feature scaling where required***

***- Train multiple Machine Learning classification models***

***- Compare model performance***

***- Select a suitable model for prediction***

***- Generate forest cover type predictions***

***- Prepare results for visualization and business-style reporting***



***---***



***## 📊 Dataset***



***The dataset contains \*\*15,120 records\*\* and \*\*54 input features\*\* after removing the `Id` column.***



***### Target Variable***



***`Cover\_Type`***



***The target contains \*\*7 forest cover classes\*\*:***



***- Cover Type 1***

***- Cover Type 2***

***- Cover Type 3***

***- Cover Type 4***

***- Cover Type 5***

***- Cover Type 6***

***- Cover Type 7***



***Each class contains approximately \*\*14.29%\*\* of the observations, making the dataset balanced across the target classes.***



***### Features***



***The dataset contains environmental and cartographic variables such as:***



***- Elevation***

***- Aspect***

***- Slope***

***- Horizontal Distance to Hydrology***

***- Vertical Distance to Hydrology***

***- Horizontal Distance to Roadways***

***- Hillshade measurements***

***- Wilderness Area indicators***

***- Soil Type indicators***

***- Other geographical features***



***---***



***## 🔎 Exploratory Data Analysis***



***The following analyses were performed:***



***- Dataset structure and shape***

***- Data types***

***- Missing-value analysis***

***- Statistical summary***

***- Target-class distribution***

***- Feature distributions***

***- Mean and median analysis by cover type***

***- Correlation analysis***

***- Correlation heatmap***

***- Feature importance analysis***



***### Data Quality***



***- Missing values: \*\*0\*\****

***- All model features are numerical***

***- Target variable contains 7 classes***



***---***



***## ⚙️ Data Preprocessing***



***The following preprocessing steps were performed:***



***1. Loaded the dataset***

***2. Checked the dataset structure***

***3. Removed the `Id` column***

***4. Separated features and target***

***5. Checked missing values***

***6. Performed train-test split***

***7. Applied feature scaling***

***8. Prepared the data for Machine Learning models***



***### Dataset Split***



***- Training data: \*\*12,096 records\*\****

***- Testing data: \*\*3,024 records\*\****

***- Features: \*\*54\*\****



***---***



***## 🤖 Machine Learning Models***



***Multiple classification models were explored:***



***### 1. Logistic Regression***



***Used as a \*\*baseline model\*\* to establish an initial performance benchmark.***



***### 2. Decision Tree Classifier***



***Used to model non-linear relationships between environmental features and forest cover types.***



***### 3. Random Forest Classifier***



***An ensemble learning model consisting of multiple decision trees.***



***Random Forest was selected for further prediction because it can capture complex non-linear relationships and interactions between features.***



***---***



***## 📈 Model Evaluation***



***The models were evaluated using classification performance metrics such as:***



***- Accuracy***

***- Confusion Matrix***

***- Classification Report***

***- Precision***

***- Recall***

***- F1-score***



***Model comparison was performed to understand the differences between the baseline and tree-based approaches.***



***---***



***## 💾 Model \& Prediction Files***



***The trained model and preprocessing objects were saved using Joblib:***



***```text***

***forest\_cover\_model.pkl***

***scaler.pkl***

