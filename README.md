# 🌊 Analisis Kualitas Air Sungai Menggunakan Statistika Multivariat

Penelitian ini bertujuan untuk menganalisis data kualitas air sungai guna mengidentifikasi parameter-parameter utama yang memengaruhi perubahan kualitas air secara **temporal** dan **spasial**. Mengingat kompleksitas dan volume besar data kualitas air, digunakan pendekatan **statistik multivariat** untuk mengekstraksi informasi penting sebagai dasar pengambilan keputusan dalam pengelolaan pencemaran sungai.

---

## 🔍 Tahapan Analisis

### 1. 📦 Data Preprocessing
- Menangani data hilang
- Normalisasi data (standardisasi z-score)
- Transformasi variabel jika diperlukan (log/sqrt)
- Pembuatan variabel kategorik jika dibutuhkan

### 2. 📊 Exploratory Data Analysis (EDA)
- Statistik deskriptif
- Visualisasi distribusi variabel (histogram, boxplot)
- Heatmap korelasi antar variabel

### 3. 🔗 Analisis Klaster
- Tujuan: Mengelompokkan titik pengamatan berdasarkan kemiripan kualitas air
- Metode: Hierarchical Clustering dan K-Means
- Output: Visualisasi dendrogram dan plot klasterisasi

### 4. ✂️ Analisis Diskriminan
- Tujuan: Menentukan variabel paling berpengaruh dalam membedakan antar klaster
- Evaluasi: Wilks' Lambda, Confusion Matrix

### 5. 📉 Principal Component Analysis (PCA)
- Tujuan: Mereduksi dimensi data
- Hasil: Mengetahui komponen utama yang menjelaskan sebagian besar variasi

### 6. 🧩 Analisis Faktor
- Tujuan: Mengidentifikasi struktur laten dalam variabel
- Hasil: Faktor-faktor utama dan loading-nya yang merepresentasikan sumber pencemaran

---


