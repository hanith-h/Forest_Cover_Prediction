# 🌲 Forest Cover Type Prediction

A machine learning project that predicts the **type of forest cover** using environmental and geographical data from the Roosevelt National Forest (Colorado, USA).

---

## 📁 Files in This Repository

- **forest_cover.ipynb** – Jupyter notebook containing data preprocessing, feature selection, model training, and evaluation.  
- **train.xls** – Dataset used for model training.  

---

## 🧠 What the Project Does

This project builds a classification model to identify the **forest cover type** based on features like elevation, slope, soil type, and more.  

### Steps Included:
1. **Data Loading & Exploration** – Read and analyze the dataset.  
2. **Outlier Handling** – Used the IQR method to treat outliers.  
3. **Feature Selection** – Selected top 13 features using `SelectKBest (f_classif)`.  
4. **Model Training** – Trained multiple models:
   - Logistic Regression  
   - Support Vector Machine (SVM)  
   - Random Forest  
   - Gradient Boosting  
5. **Model Comparison** – Compared accuracy of all models.  
6. **Model Saving** – Saved the best model using `joblib`.  

---

## 📊 Results

Each model’s accuracy is calculated, and the best-performing one is automatically saved as:

BestModelName_best_model.pkl

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/Forest_Cover_Prediction.git
cd Forest_Cover_Prediction
```

2. **Open the notebook**
```bash
jupyter notebook forest_cover.ipynb
```

3. **Run all cells to:**
- ✅ Preprocess data
- 🤖 Train models
- 📊 Evaluate accuracy
- 💾 Save the best model

4. **Future Improvements**
- 🔍 Add hyperparameter tuning for better performance
- 🔁 Apply cross-validation for more robust evaluation
- 🌟 Visualize feature importance and confusion matrices
- 🌐 Deploy the model as a simple web app (Streamlit / Flask)
