# 🚰Water Potability EDA & Prediction (Keras Sigmoid)

## 📜 Overview
This project focuses on analyzing water quality data to predict the potability of water. The dataset contains various physicochemical properties of water samples and is used to build a deep learning model for classification.

## 📊 Dataset
The dataset used in this project is from [Kaggle](https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability). It contains the following features:

- **💧 `ph`**: pH level of the water
- **💧 `Hardness`**: Water hardness, a measure of mineral content
- **💧 `Solids`**: Total dissolved solids in the water
- **💧 `Chloramines`**: Chloramines concentration in the water
- **💧 `Sulfate`**: Sulfate concentration
- **💧 `Conductivity`**:  Electrical conductivity of the water
- **💧 `Organic_carbon`**: Organic carbon content
- **💧 `Trihalomethanes`**: Trihalomethanes concentration
- **💧 `Turbidity`**: Turbidity of the water
- **🚰 `Potability`**: Target variable; indicates water potability with values 1 (potable) and 0 (not potable).

## 📚 Libraries Used
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `tensorflow`

🛠️ Usage
Load the dataset:

df = pd.read_csv("/path/to/water_potability.csv")
Perform exploratory data analysis (EDA) to understand the dataset, visualize correlations, and check for missing values.
Preprocess the data by filling missing values and scaling features.
Split the dataset into training and testing sets.
Build and train a deep learning model using TensorFlow/Keras.
Evaluate the model's performance using accuracy, confusion matrix, and ROC curve.
📈 Results
The model achieved an accuracy of XX.XX% on the test set. The confusion matrix and ROC curve visualizations provide insights into the model's performance.

🔍 Conclusion
This project demonstrates the application of deep learning techniques to predict water potability based on physicochemical properties. Future work could involve exploring different models and hyperparameter tuning to improve accuracy.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
