<h1 align="center">📬 Spam Email Detector using Machine Learning</h1>

<p align="center">
  A simple yet effective spam email classifier built using <strong>scikit-learn</strong>.<br>
  Easily detect unwanted messages and keep your inbox clean ✨
</p>

---

## 📧 Introduction

This project demonstrates a machine learning-based approach to detecting spam emails. It uses classical algorithms from `scikit-learn` to analyze and classify emails as either spam or legitimate (ham).

## 🔍 Features

✅ Classical ML model for spam detection  
✅ Lightweight and easy to run locally  
✅ Pre-trained model for instant predictions

## 🧰 Requirements

- Python 3.8 (recommended)
- `scikit-learn==0.22.1`
- `numpy`
- `scipy`
- `joblib`

## 🚀 Setup & Installation

Follow the steps below to get started:

```bash
# 1. Clone the repository
git clone https://github.com/your-username/spam-mail-detector.git
cd spam-mail-detector

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# Or manually if requirements.txt is not available
pip install scikit-learn==0.22.1 numpy scipy joblib

# 4. Run the project
python spam.py
