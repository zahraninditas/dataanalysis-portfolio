
# 💳 FinanKu Credit Card Late Payment Prediction

## 📌 Problem Statement
Terdapat kekhawatiran mengenai keterlambatan pembayaran kartu kredit di FinanKu, yang dapat berdampak negatif pada bisnis.
Oleh karena itu, diperlukan prediksi terhadap nasabah dengan risiko tinggi terlambat bayar untuk merancang strategi yang tepat dalam mengurangi risiko di masa mendatang.

## 🎯 Objective
Membangun model machine learning yang dapat memprediksi setidaknya 60% nasabah yang berpotensi mengalami keterlambatan pembayaran kartu kredit
(Target: Akurasi & Recall di atas 60%).

## 📂 Dataset & Variables
Dataset terdiri dari informasi nasabah dengan variabel sebagai berikut:
1. **Customer ID**: ID unik nasabah  
2. **Branch**: Lokasi cabang nasabah terdaftar 
3. **City**: Kota domisili nasabah  
4. **Age**: Usia nasabah pada periode observasi  
5. **Avg. Annual Income/Month**: Rata-rata penghasilan bulanan dalam satu tahun  
6. **Balance (Q1–Q4)**: Saldo akhir per kuartal  
7. **Num of Products (Q1–Q4)**: Jumlah produk yang dimiliki di akhir kuartal  
8. **HasCrCard (Q1–Q4)**: Status kepemilikan kartu kredit  
9. **Active Member (Q1–Q4)**: Status keaktifan nasabah 
10. **Unpaid Tagging**: Status keterlambatan pembayaran nasabah
    
## 🔬 Experiment Setup
- **Observation Period**:  
  - 12 bulan terakhir
  - 6 bulan terakhir

- **Feature Engineering**:
  - Rata-rata saldo selama periode observasi, serta perubahan saldo antara awal & akhir periode
  - Kepemilikan produk: rata-rata, maksimum, dan minimum
  - Keaktifan nasabah dihitung dalam bulan

## 🛠 Tools & Skills
- **Python (Jupyter Notebook)** → Data cleaning, preprocessing, modeling  
- **Pandas, NumPy, Scikit-learn** → Feature engineering & machine learning  
- **Matplotlib, Seaborn** → Exploratory Data Analysis (EDA)  
- **Classification Models** → Logistic Regression, Gradient Boosting, Random Forest  

## 📈 Expected Outcome
- Model prediksi dengan Akurasi & Recall > 60%
- Identifikasi faktor utama yang memengaruhi keterlambatan pembayaran
- Insight untuk mendukung pengambilan keputusan bisnis terkait manajemen risiko kredit 
