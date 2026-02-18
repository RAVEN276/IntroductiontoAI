# AI Praktikum 1

## Deskripsi
Repository ini berisi notebook untuk praktikum pertama mata kuliah Introduction to AI. Notebook ini mendemonstrasikan implementasi dasar machine learning menggunakan Python untuk klasifikasi angka tulisan tangan.

## Informasi Mahasiswa
- **Nama**: Mochammad Lintar Arya Dwiputra
- **NIM**: 2024081032

## Konten Praktikum

### 1. Import Library
Notebook menggunakan library-library berikut:
- `numpy` - untuk komputasi numerik
- `pandas` - untuk manipulasi data
- `matplotlib` - untuk visualisasi data
- `scikit-learn` (sklearn) - untuk machine learning

### 2. Load Dataset
Menggunakan dataset digits dari scikit-learn yang berisi gambar angka tulisan tangan (0-9).
- Jumlah data dan fitur ditampilkan untuk memahami dimensi dataset

### 3. Visualisasi Data
Menampilkan contoh gambar angka dari dataset menggunakan matplotlib untuk memahami struktur data.

### 4. Training Model
Melatih model Logistic Regression sederhana untuk klasifikasi angka:
- Model: Logistic Regression dengan max_iter=10000
- Training menggunakan seluruh dataset

### 5. Prediksi
Melakukan prediksi pada 10 data pertama dan membandingkan dengan label asli untuk evaluasi model.

## Cara Menjalankan

1. Pastikan Python sudah terinstall (disarankan Python 3.8+)

2. Install dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn
```

3. Buka notebook menggunakan Jupyter Notebook atau VS Code:
```bash
jupyter notebook AI_Praktikum1.ipynb
```

4. Jalankan semua cell secara berurutan

## Requirements
- Python 3.8+
- numpy
- pandas
- matplotlib
- scikit-learn

## Topik yang Dipelajari
- Machine Learning dasar
- Klasifikasi dengan Logistic Regression
- Preprocessing data
- Visualisasi dataset
- Evaluasi model sederhana

## Lisensi
Project ini dibuat untuk keperluan akademik.
