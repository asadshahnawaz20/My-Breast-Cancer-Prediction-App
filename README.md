# 🩺 Breast Cancer Prediction Model  

## 📌 Project Overview  
This project builds a **Machine Learning model** that predicts whether a breast tumor is **Malignant (Cancerous)** or **Benign (Non-Cancerous)**.  
It uses the **Breast Cancer Wisconsin dataset** and provides predictions through a simple **Flask web application** with a clean interface.  

---

## ⚙️ Tech Stack  
- **Python**  
- **Flask** (for web app backend)  
- **Pandas & NumPy** (data handling)  
- **Scikit-learn** (machine learning)  
- **Matplotlib & Seaborn** (visualization)  
- **HTML, CSS** (frontend UI)  

---

## 📊 Model Performance  
- **Accuracy:** `97.36%`  
- Evaluated with:  
  - Confusion Matrix  
  - Precision, Recall  
  - F1-score  

---

## 🖥️ Screenshots  

### 🔹 Negative (Not Cancerous)
!(screenshots/Negative.png)  

### 🔹 Positive (Cancerous)  
!(screenshots/Positive.png)  

---

## 🚀 Getting Started  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction

---

2️⃣ Create a Virtual Environment

python -m venv venv
venv\Scripts\activate     # for Windows
source venv/bin/activate  # for Linux/Mac

---

3️⃣ Install Dependencies
pip install -r requirements.txt


(if requirements.txt is missing, install manually)

pip install numpy pandas scikit-learn matplotlib seaborn flask

---

4️⃣ Run the Flask App
python app.py

The app will run at http://127.0.0.1:5000/

---

📌 Features

✔️ Predicts Malignant (Cancerous) vs Benign (Non-Cancerous)
✔️ Easy-to-use Flask web interface
✔️ High accuracy (~97%)
✔️ Preprocessed clean dataset

---

## 🚀 How to Run the Project
1. Clone the repo: `git clone <repo-url>`
2. Create virtual environment: `python -m venv venv`
3. Activate venv and install dependencies: `pip install -r requirements.txt`
4. Run Flask app: `python app.py`
5. Open browser: `http://127.0.0.1:5000/`