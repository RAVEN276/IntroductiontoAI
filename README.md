# Introduction to Artificial Intelligence - Academic Repository

## Ringkasan Proyek

Repository ini merupakan kumpulan materi pembelajaran dan praktikum untuk mata kuliah **Introduction to Artificial Intelligence**. Proyek ini mencakup teori fundamental kecerdasan buatan, implementasi machine learning, serta analisis data menggunakan Python. Setiap modul dirancang untuk memberikan pemahaman komprehensif tentang konsep AI dan aplikasinya secara praktis.

---

## Informasi Penulis

| Item | Keterangan |
|------|-----------|
| **Nama** | Mochammad Lintar Arya Dwiputra |
| **NIM** | 2024081032 |
| **PRODI** | Sistem Informasi |
| **Institusi** | Universitas |
| **Tahun** | 2024/2025 |

---

## Struktur Direktori

```
IntroductiontoAI/
├── README.md                          # Dokumentasi proyek
├── Tugas1/                            # Tugas pemahaman dasar AI
├── Tugas2/                            # Tugas praktikum lanjutan
├── AIPraktikum1/
│   └── AI_Praktikum1.ipynb           # Notebook praktikum 1: Klasifikasi Logistic Regression
└── AIPraktikum2/
    └── AI_Pertemuan2.ipynb           # Notebook praktikum 2: Pertemuan kedua
```

---

## Deskripsi Modul

### 📚 Tugas1 - Dasar-dasar Artificial Intelligence
- **Tujuan**: Memberikan pemahaman fundamental tentang konsep AI, sejarah perkembangan, dan aplikasinya dalam industri modern
- **Materi**: Teori dasar AI, jenis-jenis Machine Learning, dan use case praktis

### 🔬 AIPraktikum1 - Klasifikasi Digit dengan Logistic Regression
**File**: [AIPraktikum1/AI_Praktikum1.ipynb](AIPraktikum1/AI_Praktikum1.ipynb)

#### Ringkasan Konten:
1. **Library Setup** - Konfigurasi lingkungan dengan dependencies esensial
2. **Dataset Loading** - Menggunakan MNIST digits dari scikit-learn
3. **Exploratory Data Analysis (EDA)** - Visualisasi dan analisis karakteristik data
4. **Model Training** - Implementasi Logistic Regression untuk klasifikasi multi-kelas
5. **Evaluation** - Validasi model dengan metrik performa
6. **Prediction** - Prediksi pada data baru dan interpretasi hasil

#### Library yang Digunakan:
| Library | Fungsi |
|---------|--------|
| `numpy` | Komputasi numerik dan manipulasi array |
| `pandas` | Analisis dan manipulasi data terstruktur |
| `matplotlib` | Visualisasi data statis dan dinamis |
| `scikit-learn` | Machine learning algorithms dan preprocessing |
| `jupyter` | Interactive notebook environment |

### 🧠 AIPraktikum2 - Pertemuan Kedua
**File**: [AIPraktikum2/AI_Pertemuan2.ipynb](AIPraktikum2/AI_Pertemuan2.ipynb)

- Topik lanjutan dalam machine learning dan deep learning
- Pengembangan model dengan performa yang ditingkatkan
- Teknik validasi dan hyperparameter tuning

### 📋 Tugas2 - Praktikum Lanjutan
- Aplikasi konsep yang sudah dipelajari pada dataset dunia nyata
- Solving real-world problems menggunakan machine learning

---

## Persyaratan Sistem

### Minimum Requirements:
- **Python**: 3.8 atau lebih baru
- **pip**: Package manager untuk Python

### Dependencies:

```
numpy>=1.20.0
pandas>=1.3.0
matplotlib>=3.4.0
scikit-learn>=0.24.0
jupyter>=1.0.0
```

---

## Panduan Instalasi & Menjalankan

### 1. Setup Environment

```bash
# Clone atau download repository
cd IntroductiontoAI

# (Opsional) Buat virtual environment
python -m venv venv
.\venv\Scripts\activate  # Windows
# source venv/bin/activate  # Linux/Mac
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# atau
pip install numpy pandas matplotlib scikit-learn jupyter
```

### 3. Jalankan Notebook

```bash
# Menggunakan Jupyter
jupyter notebook AIPraktikum1/AI_Praktikum1.ipynb

# atau menggunakan VS Code
code .
# Kemudian buka notebook dengan VS Code Jupyter extension
```

---

## Learning Outcomes

Setelah menyelesaikan repository ini, Anda akan mampu:

- ✓ Memahami konsep dan sejarah Artificial Intelligence
- ✓ Mengimplementasikan algoritma klasifikasi dasar
- ✓ Melakukan preprocessing dan exploratory data analysis
- ✓ Melatih dan mengevaluasi model machine learning
- ✓ Menggunakan tools industri seperti scikit-learn dan Jupyter
- ✓ Menginterpretasi hasil prediksi model
- ✓ Mengatasi masalah real-world dengan machine learning

---

## Best Practices

### Menjalankan Notebook
1. Jalankan semua cell secara berurutan dari atas ke bawah
2. Pastikan output cell sebelumnya sudah dieksekusi sebelum melanjutkan
3. Gunakan "Restart Kernel" jika terjadi error atau state yang tidak konsisten

### Modifikasi & Eksperimen
- Modifikasi hyperparameter untuk melihat pengaruhnya terhadap model
- Coba dataset berbeda untuk validasi model
- Dokumentasikan perubahan yang dilakukan

---

## Referensi & Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Jupyter Project](https://jupyter.org/)

---

## Catatan Penting

- Repository ini dibuat untuk tujuan akademik dan pembelajaran
- Semua kode bebas dimodifikasi dan digunakan untuk keperluan pendidikan
- Pastikan Anda memahami setiap konsep sebelum melanjutkan ke modul berikutnya

---

## Lisensi

This project is created for academic purposes. Feel free to use and modify for educational needs.

---

**Terakhir diperbarui**: 25 Februari 2026
