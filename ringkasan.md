## 🔍 Ringkasan Analisis Data

### **Tiga Temuan Utama:**
1. **Tipe data belum sepenuhnya konsisten.** Beberapa kolom numerik masih terbaca sebagai string dan perlu dikonversi untuk perhitungan statistik yang akurat.
2. **Terdapat nilai hilang dan potensi duplikasi.** Beberapa kolom memiliki missing value dan ada indikasi baris duplikat yang dapat memengaruhi analisis.
3. **Outlier dan kategori tidak seragam ditemukan.** Beberapa fitur numerik memiliki nilai ekstrem, dan kategori teks menunjukkan variasi penulisan (huruf besar/kecil, spasi).

---

### **Tiga Aksi Lanjutan:**
1. **Perbaikan tipe data dan normalisasi kategori.** Lakukan konversi tipe data numerik dan perbaiki format kategori untuk memastikan konsistensi analisis.
2. **Lakukan eksplorasi lanjutan sebelum modeling.** Visualisasikan distribusi variabel utama untuk memahami hubungan antar fitur dan target.
3. **Bangun model prediktif dasar.** Setelah data bersih, lanjutkan dengan algoritma sederhana (misalnya Logistic Regression atau Decision Tree) untuk menguji pola awal dan baseline performa.

---

### **Rekomendasi Visualisasi & Modeling Lanjutan:**
1. **Visualisasi Distribusi:** Gunakan *histogram* dan *boxplot* untuk melihat distribusi numerik serta mendeteksi outlier lebih lanjut.
2. **Visualisasi Kategori:** Terapkan *countplot* atau *pie chart* untuk meninjau proporsi kategori dan potensi imbalance.
3. **Korelasi Fitur:** Gunakan *heatmap korelasi* untuk mendeteksi fitur yang sangat berkaitan (indikasi multikolinearitas atau leakage).
4. **Modeling Awal:** Mulai dengan *Logistic Regression* untuk baseline interpretatif, lalu coba *Random Forest* atau *XGBoost* untuk peningkatan performa.
5. **Evaluasi Model:** Gunakan *confusion matrix* dan metrik seperti *precision, recall, F1-score,* serta *ROC-AUC* untuk menilai keseimbangan performa model.

