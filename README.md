# 📊 Analisis Data COVID-19 di Indonesia

## 🎯 Tujuan
Membangun model prediktif yang dapat mengklasifikasikan wilayah-wilayah ke dalam klaster dampak COVID-19 (hasil dari proses clustering sebelumnya) berdasarkan fitur-fitur tertentu. Model ini diharapkan dapat mempermudah proses identifikasi wilayah baru yang memiliki karakteristik serupa, serta membantu dalam pengambilan keputusan berbasis data.

## 🧰 Library yang Digunakan
- `pandas`
- `numpy`
- `scikit-learn`
- `time`
- `scipy`
- `matplotlib`
- `seaborn`
- `math`

## 📁 Struktur Folder

## ⚙️ Cara Menjalankan Proyek

### 1. Menyiapkan Lingkungan Virtual
Sebelum memulai, disarankan untuk menggunakan virtual environment agar dependensi proyek terisolasi dengan baik.

- **Untuk Windows:**
  ```bash
  python -m venv venv
  .\venv\Scripts\activate

- **Untuk Linux/mac:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  
### 2. Instalasi Dependensi
 pip install -r requirements.txt

 ### 3. Jalankan proyek
 - Jalankan proyek Clustering lalu gunakan data covid_19_indonesia.csv
 - Hasil clustering yaitu data covid_inverse.csv
 - Jalankan proyek Klasifikasi lalu gunakan covid_inverse.csv
