# Heart Disease Prediction

A machine learning project that predicts whether a person has heart disease based on clinical features, using Logistic Regression and Decision Tree classifiers.

---

## 📁 Project Structure

```
heart-disease-prediction/
├── data/
│   └── heart.csv
├── notebooks/
│   └── 01_EDA_and_baseline.ipynb
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The dataset contains 1025 records of patients with 14 clinical features:

- age : Age of the patient
- sex : Sex (1 = Male, 0 = Female)
- cp : Chest pain type (0–3)
- trestbps : Resting blood pressure
- chol : Cholesterol level
- fbs : Fasting blood sugar > 120mg (1 = True, 0 = False)
- restecg : Resting ECG results (0–2)
- thalach : Maximum heart rate achieved
- exang : Exercise induced angina (1 = Yes, 0 = No)
- oldpeak : ST depression induced by exercise
- slope : Slope of the peak exercise ST segment
- ca : Number of major vessels (0–4)
- thal : Thalassemia type (0–3)
- target : 1 = Heart Disease, 0 = No Heart Disease

---

## 🔍 Project Steps

1. Data Loading and Exploration — shape, info, statistics
2. Data Cleaning — checking null values, removing duplicates
3. Exploratory Data Analysis — visualizing feature distributions, correlation heatmap, age by target
4. Preprocessing — train/test split (80/20), feature scaling with StandardScaler
5. Model Training — Logistic Regression and Decision Tree Classifier
6. Evaluation — accuracy score, classification report, confusion matrix
7. Predictive System — user inputs patient data and gets a prediction

---

## 📈 Results

- Logistic Regression : ~90% accuracy
- Decision Tree : ~77% accuracy

Logistic Regression performed better and was used for the predictive system.

---

## ⚙️ How to Run

1. Clone the repository
```
git clone https://github.com/Sofyane00/heart-disease-prediction.git
cd heart-disease-prediction
```

2. Create a virtual environment and activate it
```
python3 -m venv venv
source venv/bin/activate
```

3. Install the dependencies
```
pip install -r requirements.txt
```

4. Launch Jupyter Notebook
```
jupyter notebook
```

5. Open `notebooks/01_EDA_and_baseline.ipynb` and run all cells.

---

## 🛠️ Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 👤 Author

Sofyane — https://github.com/Sofyane00
