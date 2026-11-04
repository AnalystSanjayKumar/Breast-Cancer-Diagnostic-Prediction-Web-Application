# 🏥 Breast Cancer Diagnostic & Prediction System

An interactive end-to-end Machine Learning web application built using Python, Scikit-learn, and Streamlit. The application classifies clinical breast cancer tumors as **Benign** or **Malignant** with **96.49% accuracy** based on cell nuclei characteristics, providing real-time risk probabilities and automated analytical explanations.

---

## 🚀 Key Features

* **Individual Patient Prediction:** Real-time form input across 30 clinical dimensions (Mean, Standard Error, and Worst metrics) with instant risk classification and confidence probability.
* **Batch Analysis (CSV Upload):** Bulk prediction engine that processes CSV files, color-codes high-risk records, and generates interactive distribution visualizations.
* **Automated Clinical Insights:** Rule-based explanation generator translating statistical model outputs into clear risk statements for medical decision support.
* **Performance Dashboard:** Visual metrics displaying the confusion matrix, precision/recall evaluation, and feature importance rankings.

---

## 📊 Model Performance & Metrics

* **Model:** Logistic Regression with Standard Scaler normalization
* **Accuracy:** 96.49%
* **Precision:** 94.20%
* **Recall:** 96.30%
* **Key Influencing Features:** Mean Radius, Texture, Perimeter, Area, Smoothness

---

## 🛠️ Tech Stack & Libraries

* **Core Language:** Python 3.x
* **Machine Learning:** Scikit-learn, Joblib
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Plotly (Express & Graph Objects), Matplotlib, Seaborn
* **Web Framework:** Streamlit Cloud

---

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AnalystSanjayKumar/Breast-Cancer-Prediction.git
   cd Breast-Cancer-Prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

---

## 📂 Project Structure

```text
├── app.py              # Main Streamlit application with UI and batch logic
├── model.pkl           # Trained classification model
├── scaler.pkl          # Fitted StandardScaler object for feature normalization
├── Model.ipynb         # Model development, EDA, and validation notebook
├── requirements.txt    # Project dependencies and library versions
└── README.md           # Project documentation
```

---

## 👤 Author
* **Sanjaykumar D**
* **LinkedIn:** https://www.linkedin.com/in/sanjay-kumar-d003
* **Email:** sanjaykumar75221@gmail.com
