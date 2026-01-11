# 🏠 Regression: House Price Prediction App

A simple machine learning web app built with **Streamlit** to predict house prices based on selected features.  
This project demonstrates regression modeling, model persistence, and interactive deployment.

---

## 📘 Dokumentasi Project Machine Learning dengan Streamlit

### 1. Persiapan Lingkungan Lokal
- Buat virtual environment:  
  python3 -m venv venv
- Aktifkan venv:  
  source venv/bin/activate   # Mac/Linux
  venv\Scripts\activate      # Windows
- Install library:  
  pip install streamlit pandas scikit-learn joblib

---

### 2. Menjalankan Aplikasi Lokal
- Gunakan perintah:  
  streamlit run ml.py
- Aplikasi terbuka di browser http://localhost:8501

---

### 3. Version Control dengan Git
- Inisialisasi repo:  
  git init
- Buat .gitignore berisi:
  venv/
  __pycache__/
  *.pyc
  *.pkl
  .DS_Store
  *.env
- Tambahkan file:  
  git add .
- Commit:  
  git commit -m "Initial commit"

---

### 4. Upload ke GitHub
- Buat repo di GitHub.  
- Hubungkan remote:  
  git remote add origin <URL>
  git branch -M main
  git push -u origin main

---

### 5. Requirements File
- Buat requirements.txt minimal:
  streamlit==1.52.2
  pandas==2.3.3
  scikit-learn==1.6.1
  joblib==1.5.3
- Commit & push:
  git add requirements.txt
  git commit -m "Add requirements.txt with minimal dependencies"
  git push

---

### 6. Deploy ke Streamlit Cloud
- Login ke https://share.streamlit.io  
- Hubungkan akun GitHub  
- Pilih repo Regression  
- Pilih file ml.py  
- Deploy  

Streamlit Cloud akan otomatis install dependency dari requirements.txt dan menjalankan aplikasi.

---

### 7. Troubleshooting
- ModuleNotFoundError → tambahkan library ke requirements.txt  
- Warning versi scikit-learn → samakan versi dengan saat training  
- File besar (.pkl) → simpan di cloud storage (misalnya S3, GDrive) lalu load dari sana  

---

### 8. Best Practices
- Gunakan .gitignore untuk menjaga repo tetap bersih  
- Buat requirements.txt minimal agar environment stabil  
- Tambahkan README.md untuk dokumentasi project  
- Gunakan branch untuk pengembangan fitur baru  

---

## 📂 Project Structure
Regression/
│
├── ml.py                  # Main Streamlit app
├── house_price_model.pkl  # Trained regression model
├── feature_columns.pkl    # Saved feature columns
├── requirements.txt       # Project dependencies
└── .gitignore             # Git ignore rules

---

## ⚙️ Installation & Setup

### 1. Clone the repository
git clone https://github.com/aurielridho/Regression.git
cd Regression

### 2. Create virtual environment
python3 -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

### 3. Install dependencies
pip install -r requirements.txt

### 4. Run the app locally
streamlit run ml.py
Open http://localhost:8501 in your browser

---

## ☁️ Deployment
This app can be deployed easily on Streamlit Cloud:
1. Push your code to GitHub
2. Go to https://share.streamlit.io
3. Connect your GitHub repo
4. Select ml.py as the entry point
5. Deploy and share the public URL

---

## 🛠 Dependencies
- streamlit
- pandas
- scikit-learn
- joblib

---

## 📌 Notes
- Ensure requirements.txt is up-to-date before deploying  
- Large model files (.pkl) may be better stored in cloud storage if size exceeds GitHub limits  
- Add more features or retrain the model to improve accuracy  

---

Data dari colab regression
