# 🛡 AI-Enhanced Intrusion Detection System (IDS)  
### Cybersecurity Threat Detection Using Machine Learning

---

## 📌 Project Description

In an increasingly interconnected digital landscape, the security of organizational networks and sensitive data is of paramount importance. This project focuses on the development of an *AI-Enhanced Intrusion Detection System* that leverages machine learning to detect, classify, and respond to network intrusions with high accuracy.

By combining advanced *Random Forest Classification* with cybersecurity domain knowledge, the system empowers organizations to proactively combat evolving threats.

---





## 🛠 *Technologies Used*

- *Python 3.10+*
- *Flask (Backend Web Framework)*
- *HTML / CSS (Frontend UI)*
- *Pandas / NumPy (Data Manipulation)*
- *Scikit-learn (Machine Learning)*
- *Imbalanced-learn (SMOTE for Class Balancing)*
- *Joblib (Model Serialization)*

---

## 🧠 *Model Details*

The Intrusion Detection System uses a *Random Forest Classifier* trained on a preprocessed and balanced network intrusion dataset. The model is enhanced with *SMOTE* to handle class imbalance.

The final model is saved as:

bash
```
random_forest_model_4_features.joblib
```

---

## 🗂 *Project Directory Structure*

```bash
AI-ENHANCED-INTRUSION-DETECTION/
├── CYBER_PROJECT/
│ ├── templates/
│ │ └── index.html                             # Web interface template
│ ├── app.py                                   # Flask application entry point
│ ├── random_forest_model_4_features.joblib      
│ ├── web_attacks_balanced.csv                   # Preprocessed dataset
│ ├── requirment.txt                             # Python dependencies
│ ├── Untitled.ipynb                             # Data analysis / experimentation notebook
│ └── README.md                                  # Project documentation
├── Documentation...
└── README.md 
```

---

## ⚙ *Installation & Setup*

### Using Conda (Recommended)

```bash
conda create -n cyber_ids python=3.10


cd CYBER_PROJECT
pip install -r requirment.txt
```

### Using Python venv

```bash
python -m venv ids_env

# Windows:
ids_env\Scripts\activate

# macOS/Linux:
source ids_env/bin/activate

pip install -r requirment.txt
```
---

## *Running the Application*

```bash
cd Flask
python app.py
```

Open your browser and go to:  
  [http://127.0.0.1:5000/]

