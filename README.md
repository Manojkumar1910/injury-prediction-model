# 🏥 Sports Injury Prediction with Pose Estimation

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Pose%20Estimation-red)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 🧭 Project Overview

This project predicts **sports injury risk** by combining a structured injury dataset with **pose estimation** from real sports activity videos. Using machine learning models and computer vision techniques, it analyses movement patterns across multiple sports to identify high-risk behaviors before injuries occur.

Sports covered: **Cricket, Football, Basketball, Tennis, Gym**

---

## 🎯 Problem Statement

Sports injuries cost athletes and teams millions every year — yet many are preventable. Traditional injury analysis relies on manual observation and self-reported data. This project automates injury risk detection using:
- Structured data (training load, physical metrics, sport type)
- Pose estimation from video (joint angles, movement patterns)
- Machine learning classification models

---

## 🗂️ Project Structure

```
injury-prediction-model/
│
├── Injury Prediction Project with Pose Estimation.ipynb  # Main notebook
├── Project-Injury-Dataset.csv                            # Structured injury dataset
└── README.md
```

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas & NumPy | Data loading, cleaning, feature engineering |
| Scikit-learn | ML models (classification, evaluation) |
| OpenCV | Video frame extraction and processing |
| MediaPipe | Pose estimation and joint landmark detection |
| Matplotlib / Seaborn | Data visualization |
| Jupyter Notebook | Analysis environment |

---

## 📁 Dataset

**File:** `Project-Injury-Dataset.csv`

The dataset contains sports activity and injury records across multiple athletes and sports disciplines. Key features include:

- Sport type (Cricket, Football, Basketball, Tennis, Gym)
- Training intensity and duration
- Physical metrics (age, BMI, fitness level)
- Previous injury history
- Injury risk label (target variable)

---

## 🧠 Methodology

```
Raw Data + Sports Videos
        ↓
  Data Cleaning & EDA
        ↓
  Feature Engineering
        ↓
  Pose Estimation (MediaPipe)
  — Joint angle extraction
  — Movement pattern analysis
        ↓
  ML Model Training
  — Classification (Random Forest / SVM / Logistic Regression)
  — Train/Test Split & Cross-validation
        ↓
  Injury Risk Prediction
  — Low / Medium / High risk output
```

---

## 🔍 Key Findings

- Athletes with **higher training intensity + low recovery time** are significantly more injury-prone
- **Gym and Cricket** activities showed the highest injury risk patterns in the dataset
- Pose estimation reveals **asymmetric joint angles** as a strong predictor of lower-body injuries
- ML model achieved strong classification performance with features combining structured data and pose-derived metrics

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Manojkumar1910/injury-prediction-model.git
cd injury-prediction-model
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook "Injury Prediction Project with Pose Estimation.ipynb"
```

---

## 📊 Results Preview

> 📌 *Add a screenshot of your model evaluation (confusion matrix, accuracy score, feature importance chart) here:*
> ```markdown
> ![Model Results](images/model_results.png)
> ![Pose Estimation](images/pose_estimation.png)
> ```

---

## 🚀 Future Improvements

- [ ] Real-time injury risk monitoring using live webcam feed
- [ ] Deep learning model (LSTM) for sequential movement analysis
- [ ] Wearable sensor data integration (accelerometer, gyroscope)
- [ ] Streamlit web app for athlete risk dashboard
- [ ] Expand dataset with more sports and athlete profiles
- [ ] Export model as REST API for team management software

---

## 👤 Author

**V. Manoj Kumar**
- GitHub: [@Manojkumar1910](https://github.com/Manojkumar1910)
- Domain: AI & Data Science

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## ⭐ If you found this project useful, give it a star!
