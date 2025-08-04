# 🌸 Iris Flower Classification

This project performs machine learning classification on the **Iris flower dataset** using full **EDA**, **label encoding**, and **multiple ML models** including **Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Decision Tree**. Models are compared using **cross-validation accuracy**.

---

## 📂 Dataset Information

- **Total Samples:** 150  
- **Classes:** Setosa, Versicolor, Virginica  
- **Features:**  
  - Sepal Length (cm)  
  - Sepal Width (cm)  
  - Petal Length (cm)  
  - Petal Width (cm)

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Steps Performed:

- Checked for **null values** and **duplicates**
- Used **histograms** for feature distribution
- Created **scatter plots** to visualize class separability
- Generated **correlation heatmap** to identify strong feature relationships

### 📌 Key Observations:

- No missing or null values in the dataset
- **Petal length** and **petal width** are strongly correlated and help in distinguishing flower species
- Classes are well-separated visually in scatter plots

---

## 🧪 Data Preprocessing

- Applied **Label Encoding** to convert target classes to numeric values (Setosa = 0, Versicolor = 1, Virginica = 2)
- Split dataset into **training and testing sets** (70/30 split)
- No feature scaling needed due to simple range of values

---

## 🧠 Model Training and Selection

### Trained Models:

- ✅ Logistic Regression  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Decision Tree Classifier  

### Model Evaluation:

- Used **cross_val_score** from `sklearn` for **robust accuracy evaluation**
- Accuracy evaluated with **5-fold cross-validation**

### 📈 Accuracy Results (CV Mean Scores):

| Model                | Cross-Validation Accuracy |
|---------------------|----------------------------|
| Logistic Regression | 100%                       |
| KNN                 | 100%                       |
| Decision Tree       | 100%                       |

✔️ All models performed **perfectly**, which is expected due to the simplicity and clean structure of the Iris dataset.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (sklearn)

