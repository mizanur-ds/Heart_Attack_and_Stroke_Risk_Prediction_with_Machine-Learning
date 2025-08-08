## 📄 Abstract
This project predicts the risk of heart attack or stroke using a synthetic UK primary care dataset. After data analysis, preprocessing, and testing multiple machine learning models, **Logistic Regression** was chosen for its accuracy and interpretability. The model is deployed as a **Streamlit web app**, enabling users to enter health data and instantly receive a personalized risk probability — all while maintaining privacy through synthetic data.

---

## 🌐 Live App
You can try the interactive prediction tool here:  
**[Heart Attack and Stroke Risk Prediction App](https://heartattackandstrokeriskprediction.streamlit.app/)**

Enter your health details step-by-step and instantly see your estimated risk probability.

---

## 📊 Dataset
- **Source**: NIHR ARC Wessex – Synthetic dataset for cardiovascular event prediction  
  🔗 [ARC Wessex Datasets](https://www.arc-wx.nihr.ac.uk/data-sets?utm_source=chatgpt.com)
- **Description**: Mimics real UK primary care patient records, incorporating realistic complexities such as missingness, noise, and feature interactions.
- **Files Used**:  
  - `cvd_synthetic_dataset_v0.2.csv` → Raw dataset used in `1_data_analysis_preprocessing.ipynb`  
  - `final_df.csv` → Processed dataset used in modeling and Streamlit app

---

## 📂 Repository Structure
```plaintext
📦 Heart-Stroke-Prediction
│
├── 1_data_analysis_preprocessing.ipynb   # Data cleaning, EDA, feature engineering
├── 2_data_modeling_prediction.ipynb      # Model training, evaluation
├── Attack_or_Stroke_prediction.py        # Streamlit app
├── cvd_synthetic_dataset_v0.2.csv        # Raw dataset
├── final_df.csv                          # Processed dataset ready for modeling
├── requirements.txt                      # Dependencies
└── README.md                             # Project documentation
```

## ⚙️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Heart-Stroke-Prediction.git
cd Heart-Stroke-Prediction
```

### 2️⃣ Install Requirements
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App Locally
```bash
streamlit run Attack_or_Stroke_prediction.py
```
Or use the hosted version:
🔗**[Heart Attack and Stroke Risk Prediction App](https://heartattackandstrokeriskprediction.streamlit.app/)**

📈 Example Plot
Example of average systolic blood pressure by age across groups:


🧠 Machine Learning Workflow
Data Loading – Import and inspect cvd_synthetic_dataset_v0.2.csv

Exploratory Data Analysis (EDA) – Missing values, feature distributions, outlier detection

Data Preprocessing – Encoding categorical variables, scaling numeric values, balancing classes

Model Training – Logistic Regression, model selection based on validation accuracy

Deployment – Interactive Streamlit app for end-user predictions

📜 License
This project uses a synthetic dataset provided by NIHR ARC Wessex and is intended for educational and research purposes.
Check the dataset license on the ARC Wessex website.

👨‍💻 Author
Developed by Mizanur Rahman – Data Science & Machine Learning Enthusiast
