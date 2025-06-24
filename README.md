# 🏥 AI-Driven Early Detection of Malaria, TB, and HIV

An end-to-end machine learning project for early disease detection using patient symptoms, X-ray images, and wearable device data. This project predicts the likelihood of Malaria, Tuberculosis (TB), or HIV and clusters patients for effective triage.

---

## 📌 Problem Statement

Late diagnosis of Malaria, TB, and HIV remains a critical public health issue, especially in resource-limited areas. This project aims to:

- Build classification models to detect disease presence early.
- Use clustering to group patients by symptom similarity.
- Deploy models for real-time usage via a dashboard or API.

---

## 📊 Datasets Used

- **WHO Open Data** – [https://www.who.int/data](https://www.who.int/data)
- **Kaggle Malaria Dataset** – Microscopic images of infected cells
- **TB Chest X-ray Dataset** – NIH/NIAID TB X-rays
- **Simulated EHR Data** – Synthetic health records
- **PhysioNet** – Wearable health sensor data

---

## 🛠️ Tools & Libraries

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, TensorFlow/Keras
- OpenCV for image processing
- Streamlit or Flask for deployment
- Git & GitHub for version control

---

## 🚀 Project Phases

### 1. Data Collection
Collected open datasets via Kaggle, WHO, and PhysioNet APIs.

### 2. Data Cleaning & Preprocessing
Handled missing values, outliers, encoded variables, and scaled features.

### 3. EDA
Explored feature distributions, correlations, and visualized class imbalance.

### 4. Supervised Learning
- Logistic Regression (baseline)
- CNN for X-ray classification
- XGBoost for tabular symptom data

### 5. Unsupervised Learning
- KMeans and DBSCAN for patient symptom clustering
- PCA for dimensionality reduction

### 6. Evaluation
- Classification: Accuracy, Precision, Recall, AUC
- Clustering: Silhouette Score, visual inspection

### 7. Deployment
Deployed using Streamlit and Flask API for prediction interface.

---

## 📂 Folder Structure

```

early-disease-detection/
│
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter notebooks for each step
├── models/              # Saved trained models
├── src/                 # Reusable Python modules
├── app/                 # Streamlit or Flask app
├── static/              # App assets
├── requirements.txt     # Dependencies
└── README.md            # You’re here!

````

---

## ✅ Results & Highlights

- CNN achieved **92% accuracy** on Malaria X-ray detection
- Logistic Regression baseline reached **82% accuracy**
- Cluster analysis revealed 3 major symptom-based patient groups
- Dashboard allows clinicians to input patient data and receive predictions

---

## 📌 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/early-disease-detection.git
cd early-disease-detection
````

### 2. Create Environment & Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the App (Streamlit)

```bash
cd app
streamlit run app.py
```

---

## 📈 Future Improvements

* Integrate more real-world data sources (e.g., hospital EHRs)
* Add real-time wearable data pipeline
* Expand to other infectious diseases
* Collaborate with healthcare NGOs

---

## 🤝 Contributing

Contributions are welcome! Please submit issues and PRs.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🔗 Connect

* GitHub: [@swanechi](https://github.com/swangechi)
* Email: [sgituire@gmail.com](mailto:sgituire@gmail.com)

