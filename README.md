# Proyek Analisis Data Abalone

## Deskripsi
Proyek ini bertujuan untuk menganalisis dataset Abalone dari UCL Repository menggunakan dua model: klasifikasi dan regresi. Dataset ini digunakan untuk memprediksi usia abalone berdasarkan berbagai fitur fisik.

## Dataset
Dataset ini terdiri dari berbagai fitur abalone, termasuk:
- **Length**: Panjang abalone
- **Diameter**: Diameter abalone
- **Height**: Tinggi abalone
- **Whole_weight**: Berat keseluruhan
- **Shucked_weight**: Berat bagian dalam
- **Viscera_weight**: Berat organ dalam
- **Shell_weight**: Berat cangkang
- **Rings**: Jumlah cincin, yang dapat digunakan untuk memperkirakan usia abalone

### Sumber Dataset
Dataset dapat diunduh dari [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Abalone).

## Model
### 1. Klasifikasi
Model klasifikasi digunakan untuk memprediksi kelas (usia abalone) berdasarkan fitur fisik. Evaluasi model dilakukan dengan menggunakan metrik seperti akurasi, precision, recall, dan F1-score. Hasil evaluasi menunjukkan bahwa model berhasil mencapai akurasi tinggi (0.98) dan menunjukkan performa baik pada semua kelas.

#### Metodologi
- Pembagian dataset menjadi data pelatihan dan pengujian.
- Pemodelan menggunakan algoritma klasifikasi.
- Evaluasi kinerja model dengan confusion matrix.

### 2. Regresi
Model regresi digunakan untuk memprediksi nilai numerik (jumlah cincin) yang berhubungan dengan usia abalone. Evaluasi model dilakukan dengan menghitung metrik seperti mean squared error (MSE) dan R-squared.

#### Metodologi
- Pembagian dataset menjadi data pelatihan dan pengujian.
- Pemodelan menggunakan algoritma regresi.
- Evaluasi kinerja model dengan metrik regresi.

## Hasil
- Klasifikasi: Model berhasil memprediksi kelas abalone dengan akurasi 98% dan performa baik di semua metrik evaluasi.
- Regresi: Model memberikan prediksi yang cukup akurat dengan metrik evaluasi yang menunjukkan performa yang memuaskan.

## Cara Menjalankan
1. Clone repository ini:
   ```bash
   git clone https://github.com/fazza=abouui/repo.git
   cd repo
