## Prediksi Diabetes Menggunakan Regresi
Proyek ini merupakan implementasi algoritma regresi untuk memprediksi apakah seseorang menderita diabetes berdasarkan data medis. Proyek ini disusun untuk memenuhi tugas mata kuliah Data Mining.

## Coba di Google Colab
Notebook proyek ini bisa langsung dijalankan di Google Colab melalui tautan berikut:
 [**Buka di Google Colab**](https://colab.research.google.com/drive/1ZRLdA--k6Yt009dUTP8FbbHUAS-q26kg?authuser=1)
Atau klik tombol di bawah:
[![Buka di Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZRLdA--k6Yt009dUTP8FbbHUAS-q26kg?authuser=1)

## Deskripsi Dataset

Dataset yang digunakan adalah dataset kesehatan dari Pima Indians, yang sangat sering digunakan dalam pembelajaran dan penelitian di bidang data science dan machine learning.
Dataset ini berisi informasi medis dari 768 perempuan keturunan Pima Indian dan bertujuan untuk memprediksi apakah seseorang menderita diabetes berdasarkan beberapa fitur klinis, yaitu:
- Pregnancies (Jumlah kehamilan)
- Glucose (Kadar glukosa darah puasa)
- BloodPressure (Tekanan darah diastolik)
- SkinThickness (Ketebalan lipatan kulit)
- Insulin (Kadar insulin serum)
- BMI (Indeks massa tubuh)
- DiabetesPedigreeFunction (Riwayat keluarga)
- Age (Usia)
- Outcome (Label: 0 = tidak diabetes, 1 = diabetes)
- 
### Detail Dataset:
- **Jumlah Data**: 768 entri
- **Fitur**: 8 atribut + 1 target (Outcome)
- **Format**: CSV
- **Ukuran File**: ±23KB

---

## Eksperimen Model Regresi dan Evaluasi

Dalam proyek ini dilakukan eksperimen dan perbandingan antara dua model regresi:
- ✅ **Support Vector Regression (SVR)**
- ✅ **Decision Tree Regressor**

Keduanya dievaluasi menggunakan metrik berikut:
- **MSE** (Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **MAPE** (Mean Absolute Percentage Error)
- **R² Score** (Koefisien Determinasi)
Hasil dari eksperimen ini digunakan untuk menentukan model yang paling akurat dalam memprediksi data diabetes.

## Sumber Dataset
Dataset ini diambil dari Kaggle:
 [https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)

- **Pembuat Dataset**: Akshay Dattatray Khare  
- **Lisensi**: Tersedia secara publik di Kaggle untuk keperluan pembelajaran, mengikuti [Kaggle Terms of Use](https://www.kaggle.com/terms)

## Teknologi yang Digunakan
- Python 3.13.2
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Scatter (visualisasi)
- Scikit-learn (Regresi dan evaluasi model)

## Proyek ini dibuat oleh :
  **1. Septi Amalia**
  **2. Vebronia Bikolo**
