# 🤖 Social Media Fake Profile Detection

A machine learning-based system for detecting fake profiles on social media platforms. This project was the **winning solution at Smart India Hackathon 2023** (Ministry of Gujarat problem statement), aimed at improving digital trust and identifying fraudulent users using behavioral and metadata analysis.

---

## 🚀 Overview

Fake profiles are widely used for phishing, spreading misinformation, scams, and impersonation. This project uses **machine learning techniques** to detect such profiles with **94% accuracy**, while reducing **false positives by 15%** through proper feature engineering and model tuning.

---

## 🧠 Model Highlights

- **Algorithm Used:** Random Forest, Decision Tree, Logistic Regression  
- **Accuracy:** 94% (Random Forest)  
- **Optimization Techniques:**  
  - Under-sampling using SMOTE
  - GridSearchCV for hyperparameter tuning  
- **Performance Gains:**  
  - Increased fraud detection efficiency by 23%  
  - Reduced false positives by 15%

---

## 📊 Features Used

- Number of followers/following
- Profile completeness (bio, profile picture, etc.)
- Activity frequency (posts, likes)
- Account age
- Follower-following ratio
- Verified status (if available)

---

## 📂 Project Structure
Social-Media-Fake-Profile-Detection/ ├── fake_profile_detection.ipynb      # Main Jupyter Notebook with code ├── dataset.csv                       # Dataset used for training/testing ├── README.md                         # Project documentation ├── requirements.txt                  # Python dependencies

---

## 🧪 How to Run

### 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shagunjha0111/Social-Media-Fake-Profile-Detection.git
   cd Social-Media-Fake-Profile-Detection

2. Install dependencies:

pip install -r requirements.txt


3. Run the notebook:

jupyter notebook fake_profile_detection.ipynb




---

**📈 Results**

Model	Accuracy	Precision	Recall	F1 Score

Random Forest	94%	0.91	0.94	0.92
Decision Tree	89%	0.86	0.88	0.87
Logistic Regression	84%	0.82	0.85	0.83



---

🌟**Achievements**

🏆 Smart India Hackathon 2023 Winner

Selected and awarded by the Ministry of Gujarat for developing this solution

Worked in a 6-member team under real-time constraints

Presented the model to national-level evaluators and tech leaders



---

📌 **Future Improvements**

Deploy using Streamlit or Flask for real-time use

Integrate Twitter API / Instagram Graph API for live scanning

Build a browser plugin for on-the-go detection

Add deep learning models for image-based profile validation



---

👩‍💻 **Author**

Shagun Jha
