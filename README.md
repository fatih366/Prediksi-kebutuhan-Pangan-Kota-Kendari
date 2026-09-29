# Project Machine Learning - SDGs 2: Mengakhiri Kelaparan

## Penerapan Artificial Intelligence untuk Memprediksi Kebutuhan Beras dalam Mendukung SDGs 2: Mengakhiri Kelaparan di Kota Kendari

Proyek ini dikembangkan untuk memenuhi tugas mata kuliah Kecerdasan Buatan (Artificial Intelligence). Fokus penelitian adalah membangun model Machine Learning untuk memprediksi kebutuhan beras masyarakat Kota Kendari berdasarkan data historis jumlah penduduk dan konsumsi beras.

---

## 👥 Anggota Kelompok

- Fatih Maulana (F1G125031)
- Cinta Aprianti Hartono Haris (F1G125028)
- Waode Nur Aisya (F1G125019)

**Program Studi:** Ilmu Komputer

**Fakultas:** Matematika dan Ilmu Pengetahuan Alam

**Instansi:** Universitas Halu Oleo

---

## 📌 Latar Belakang & Keterkaitan SDGs

### SDGs 2: Mengakhiri Kelaparan

Pertumbuhan jumlah penduduk menyebabkan kebutuhan pangan, khususnya beras, terus meningkat setiap tahun. Oleh karena itu diperlukan metode prediksi yang dapat membantu perencanaan kebutuhan pangan secara lebih efektif.

Melalui penerapan Artificial Intelligence dan Machine Learning, kebutuhan beras masyarakat dapat diprediksi berdasarkan data historis sehingga dapat membantu pengambilan keputusan dalam perencanaan pangan.

---

## 🎯 Tujuan Proyek

1. Membangun model Machine Learning untuk memprediksi kebutuhan beras Kota Kendari.
2. Menganalisis pengaruh jumlah penduduk terhadap kebutuhan beras.
3. Membandingkan performa algoritma Decision Tree dan Random Forest.
4. Menghasilkan prediksi kebutuhan beras pada tahun berikutnya.

---

## 📊 Dataset

### Sumber Data

- Badan Pusat Statistik (BPS)
- Kaggle

### Variabel Dataset

| Variabel | Keterangan |
|-----------|------------|
| Tahun | Tahun Pengamatan |
| Penduduk (Ribu Jiwa) | Jumlah Penduduk Kota Kendari |
| Produksi Beras (Ton) | Produksi Beras Tahunan |
| Konsumsi Beras per Kapita | Konsumsi Beras Per Orang |
| Konsumsi Beras (Ton) | Target Prediksi |

### Periode Data

2018 – 2024

---

## 🔍 Tahapan Penelitian

1. Import Dataset
2. Data Cleaning
3. Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Pemodelan Machine Learning
8. Evaluasi Model
9. Prediksi Kebutuhan Beras

---

## 🤖 Algoritma yang Digunakan

### Decision Tree Regressor

Digunakan untuk memprediksi kebutuhan beras berdasarkan pola hubungan antara tahun dan jumlah penduduk.

### Random Forest Regressor

Menggunakan kumpulan Decision Tree untuk meningkatkan stabilitas dan akurasi prediksi.

---

## 📈 Hasil Evaluasi Model

| Metrik | Decision Tree | Random Forest |
|---------|---------:|---------:|
| MAE | 1316.14 | 1529.40 |
| MSE | 2263596.27 | 2870420.63 |
| RMSE | 1504.53 | 1694.23 |
| R² Score | -3.26 | -4.40 |

### Kesimpulan Evaluasi

- Decision Tree menghasilkan nilai MAE dan RMSE yang lebih rendah.
- Random Forest memiliki tingkat kesalahan yang lebih besar dibanding Decision Tree.
- Berdasarkan hasil evaluasi, Decision Tree memberikan performa yang lebih baik pada dataset yang digunakan.

---

## 📊 Prediksi Kebutuhan Beras

| Tahun | Prediksi Decision Tree | Prediksi Random Forest |
|---------|---------:|---------:|
| 2025 | 32530.62 Ton | 32317.37 Ton |
| 2026 | 32530.62 Ton | 32317.37 Ton |
| 2027 | 32530.62 Ton | 32317.37 Ton |

---

## 🛠️ Teknologi dan Library

### Bahasa Pemrograman

- Python

### Library

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Platform

- Google Colab
- GitHub

---

## 📚 Referensi

1. Badan Pusat Statistik (BPS)
2. Dataset Kaggle
3. Scikit-Learn Documentation
4. Pandas Documentation
5. Sustainable Development Goals (SDGs)
