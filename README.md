
# 💻 Laptop Selection and Price Prediction using Machine Learning

This project uses machine learning models to **predict laptop prices** based on key features such as RAM, processor, storage, weight, display quality, and more.  
It also includes **classification models** to help users select suitable laptops based on their preferences.

---

## ⭐ Project Features

### 🔹 1. Data Preprocessing
- Handling missing values
- Feature encoding (Label Encoding / One-hot Encoding)
- Normalization using `StandardScaler`

### 🔹 2. Machine Learning Models Used
#### **Regression Models (Price Prediction)**
- Linear Regression  
- Random Forest Regressor  
- K-Nearest Neighbors Regressor (KNN)  
- Support Vector Regressor (SVR)

#### **Classification Models (Laptop Selection)**
- Logistic Regression  
- Random Forest Classifier  

### 🔹 3. Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score
- Accuracy Score (for classification)

### 🔹 4. Visualizations
- Heatmaps  
- Correlation plots  
- Feature importance  
- Actual vs Predicted Plots  

---

## 📁 Project Structure

📦 Laptop Selection and Price Prediction
├── dataset.csv
├── DSP_PROJECT(LAPTOP SELECTION AND PRICE PREDICTION).ipynb
├── requirements.txt
└── README.md

yaml
Copy code

---

## 🚀 How to Run the Project

### **Step 1: Install dependencies**
```bash
pip install -r requirements.txt
Step 2: Open the Jupyter Notebook
bash
Copy code
jupyter notebook
Open the file:

scss
Copy code
DSP_PROJECT(LAPTOP SELECTION AND PRICE PREDICTION).ipynb
Step 3: Run the notebook
Run each cell to:

Load dataset

Train multiple ML models

Generate predictions

Visualize results

📝 Requirements
All Python libraries needed to run this project:

nginx
Copy code
pandas
numpy
matplotlib
seaborn
scikit-learn
📊 Sample Output (Highlights)
Regression model performance comparison

Best model for price prediction

Confusion matrix for classification

Predicted vs actual price graph

🙌 Author
Prameela Bevara

📌 Notes
You can replace the dataset with any laptop specification sheet.

For deployment, you may use:

Streamlit (recommended for beginners)

Flask / FastAPI

Render / Railway / HuggingFace Spaces
