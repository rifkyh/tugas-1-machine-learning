# Tugas 1 Machine Learning — Data Preprocessing

Repository ini berisi pengerjaan Tugas 1 mata kuliah Machine Learning yang berfokus pada proses **data preprocessing** menggunakan dataset mahasiswa.

## Dataset

Dataset berisi informasi mahasiswa dengan beberapa karakteristik seperti:

* ID mahasiswa
* Nama
* Jenis kelamin
* Program studi
* Status mahasiswa
* Nilai akhir
* Tanggal ujian
* Umur

Dataset juga memiliki beberapa permasalahan data seperti **missing value** dan **format tanggal yang tidak konsisten** yang perlu ditangani sebelum data digunakan untuk proses machine learning.

## Tahapan

Proses yang dilakukan dalam notebook meliputi:

1. **Load Dataset**

   * Memuat dataset menggunakan Pandas.

2. **Exploratory Data Analysis (EDA)**

   * Memeriksa struktur dan tipe data.
   * Mengidentifikasi missing value.
   * Melihat statistik deskriptif dan karakteristik data.

3. **Missing Values**

   * Imputasi `Umur` menggunakan median.
   * Imputasi `Nilai_Akhir` menggunakan modus.

4. **Normalisasi Tanggal**

   * Mengonversi `Tanggal_Ujian` menjadi tipe `datetime`.

5. **Label Encoding**

   * Mengubah data kategorikal menjadi representasi numerik menggunakan `LabelEncoder`.

6. **Train-Test Split**

   * Membagi dataset menjadi data training dan testing dengan rasio 80:20.

7. **Visualisasi Data**

   * Histogram distribusi umur.
   * Bar chart jumlah mahasiswa berdasarkan program studi.

8. **Kesimpulan**

   * Merangkum hasil proses preprocessing dan visualisasi dataset.

## Teknologi

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab
* Git & GitHub

## Struktur Repository

```text
tugas-1-machine-learning/
├── data/
│   └── dataset_tugas1_preprocessing.csv
├── tugas1_preprocessing.ipynb
└── README.md
```

## Notebook

Notebook utama pengerjaan tugas tersedia pada:

`tugas1_preprocessing.ipynb`
