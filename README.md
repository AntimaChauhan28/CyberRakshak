# 🛡️ CyberRakshak – Intelligent Cyber Threat Detection System

## 📌 Project Overview

CyberRakshak is a Machine Learning-based Cybersecurity project designed to identify and detect potential cyber threats using intelligent detection techniques.

The project focuses on three major cybersecurity areas: Network Threat Detection, SMS Spam Detection, and Malicious URL Detection.

It aims to improve digital safety by identifying suspicious activities, detecting fraudulent messages, and recognizing potentially harmful URLs.

## 🎯 Project Objectives

- Detect suspicious network activities.
- Identify spam and fraudulent SMS messages.
- Detect malicious and suspicious URLs.
- Apply Machine Learning techniques to cybersecurity problems.
- Promote safe internet usage and cybersecurity awareness.

## 🚀 Project Modules

### 1. Network Detection

**Notebook:** `Network_Detection/Network_detector.ipynb`

- Analyze network traffic data.
- Identify suspicious network activities.
- Apply Machine Learning techniques for network threat detection.

### 2. SMS Spam Detection

**Notebook:** `SMS_detection/SMS_detector.ipynb`

- Classify SMS messages as Spam or Normal (Ham).
- Clean and preprocess text messages.
- Extract text features using TF-IDF Vectorization.
- Train a Logistic Regression classification model.
- Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix.

**Dataset:** SMS Spam Collection Dataset (UCI Machine Learning Repository)

**Model Performance:**

| Metric | Result |
|---|---:|
| Accuracy | 98.03% |
| Spam Precision | 92% |
| Spam Recall | 93% |
| Spam F1-score | 93% |

*Results are based on the current 80:20 train-test split.*

### 3. URL Detection

**Notebook:** `URL_detector/CyberRakshak_Data_Exploration.ipynb`

- Explore URL-related datasets.
- Analyze URL characteristics and patterns.
- Prepare URL features for malicious URL detection.

## 🛠️ Technologies Used

- Python
- Google Colab
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib
- Seaborn
- Joblib

## 📂 Project Structure

```text
CyberRakshak/
│
├── Network_Detection/
│   └── Network_detector.ipynb
│
├── SMS_detection/
│   └── SMS_detector.ipynb
│
├── URL_detector/
│   └── CyberRakshak_Data_Exploration.ipynb
│
└── README.md
```

## ⚙️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/AntimaChauhan28/CyberRakshak.git
```

### Step 2: Open the Project Folder

```bash
cd CyberRakshak
```

### Step 3: Open Google Colab

Visit: https://colab.research.google.com/

### Step 4: Open the Required Notebook

Upload or open the required `.ipynb` notebook in Google Colab.

### Step 5: Install Required Libraries

```python
!pip install pandas numpy scikit-learn matplotlib seaborn joblib ucimlrepo
```

### Step 6: Run the Notebook

Execute the notebook cells sequentially to perform data preprocessing, model training, testing, and evaluation.

## 📊 Key Features

- Machine Learning-based threat detection.
- SMS spam and scam identification.
- Network traffic analysis.
- URL data exploration.
- Model performance evaluation.
- Reusable trained SMS detection model.

## 🔮 Future Enhancements

- Develop a real-time cyber threat detection system.
- Build an interactive web application.
- Integrate all three detection modules into one platform.
- Improve malicious URL classification.
- Add real-time alerts for suspicious activities.
- Deploy the system for practical cybersecurity applications.

## 👩‍💻 Authors

### 1. Fatema Kapadia

Project Contributor

### 2. Antima Singh Chauhan

B.Tech – Electronics & Telecommunication Engineering  
Institute of Engineering and Technology (IET DAVV), Indore

GitHub: [AntimaChauhan28](https://github.com/AntimaChauhan28)

## 🙏 Acknowledgement

- UCI Machine Learning Repository for the SMS Spam Collection Dataset.
- Open-source Python and Machine Learning libraries.
- Google Colab for notebook development and experimentation.

---

## ⭐ Support

If you find this project useful, please give this repository a star ⭐.

**CyberRakshak – Making the Digital World Safer, One Detection at a Time! 🛡️**

