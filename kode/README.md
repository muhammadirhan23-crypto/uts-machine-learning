Panduan Reproduksi Kode (UTS Machine Learning)

1. Lingkungan Komputasi & Versi Library
Seluruh eksperimen dijalankan pada Google Colab (Python 3.10+) menggunakan library dan versi berikut:
- numpy: 1.26.4
- pandas: 2.2.2
- scikit-learn: 1.5.2
- lightgbm: 4.5.0
- shap: 0.46.0
- matplotlib: 3.8.4
- seaborn: 0.13.2

Random Seed: 42 (diterapkan pada seluruh proses sampling, split data, pelatihan model, PCA, dan K-Means).

2. Cara Menjalankan Ulang (One-Command Execution)
1. Buka file kode/uts_ml_pipeline.ipynb di Google Colab.
2. Unggah dataset data_uts_ml.zip ke folder utama Colab (/content/data_uts_ml.zip).
3. Klik menu Runtime -> Run all untuk menjalankan seluruh sel secara otomatis dan menghasilkan angka evaluasi serta file prediksi.