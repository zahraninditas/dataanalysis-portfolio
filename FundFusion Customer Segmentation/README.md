# 🏦 FundFusion Customer Segmentation using Clustering

## 📌 Problem Statement
Belum memiliki strategi yang tepat untuk menawarkan jenis produk yang sesuai dengan segmen calon nasabah yang akan direkrut. Hal ini membuat pemasaran kurang efektif dan tidak tepat sasaran.

## 🎯 Objective
Membangun model **clustering** untuk mengetahui kepemilikan produk berdasarkan demografi nasabah yang saat ini sudah menggunakan layanan FundFusion, dengan target **Silhouette Score > 0.7**.

## 📂 Dataset & Variables
Dataset berisi informasi nasabah yang mencakup data demografi, saluran akuisisi, pendapatan, serta kepemilikan produk finansial. Variabel yang digunakan antara lain:

1. **GCIF** : Unique Identifier Nasabah  
2. **Area** : Lokasi Nasabah (Jakarta, Bogor, Bandung, Surabaya, Jogja, Solo)  
3. **Jalur_Pembukaan** : Touch Points Nasabah membuka produk → Cabang, Telemarketing, Aplikasi Digital, Internet Banking  
4. **Vintage** : Durasi Menjadi Nasabah (Sejak membuka akun)  
5. **Usia** : Usia Nasabah  
6. **Jenis_Kelamin** : Laki-laki (1) & Perempuan (0)  
7. **Status_Perkawinan** : Belum Menikah (0), Menikah (1), Cerai (2), Janda/Duda (3)  
8. **Jumlah_Anak** : Jumlah anak nasabah  
9. **Pendidikan** : Pendidikan terakhir (0–6: Tidak sekolah → Doktor)  
10. **Produk_Tabungan** : Kepemilikan tabungan (1 = Ya, 0 = Tidak)  
11. **Produk_Deposito** : Kepemilikan deposito  
12. **Produk_Kartu_Kredit** : Kepemilikan kartu kredit  
13. **Produk_Kredit_Rumah** : Kepemilikan kredit rumah  
14. **Produk_Kredit_Kendaraan** : Kepemilikan kredit kendaraan  
15. **Produk_Kredit_Dana_Tunai** : Kepemilikan kredit dana tunai  
16. **Total_Kepemilikan_Produk** : Jumlah total produk finansial yang dimiliki  
17. **Pendapatan_Tahunan** : Rata-rata pendapatan tahunan  
18. **Total_Relationship_Balance** : Total aset nasabah dalam cutoff bulan observasi  

## 🧪 Experiment
Model clustering dilakukan dengan dua perspektif:
1. **Berdasarkan Demografi** → mencari pola kepemilikan produk.  
2. **Berdasarkan Kepemilikan Produk** → mencari pola demografi nasabah.  

Pendekatan ini memungkinkan pemetaan segmen nasabah yang lebih presisi, sehingga perusahaan dapat menentukan strategi penawaran produk sesuai dengan karakteristik segmen.

## 🛠 Tools & Methods
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Techniques**: Clustering (K-Means, Hierarchical, DBSCAN), Feature Engineering, Silhouette Analysis, Data Visualization  

## 📊 Expected Outcome
- Segmentasi nasabah yang jelas berdasarkan demografi & kepemilikan produk.  
- Identifikasi produk yang relevan untuk ditawarkan pada masing-masing segmen.  
- Model clustering dengan **Silhouette Score > 0.7**.  

---
