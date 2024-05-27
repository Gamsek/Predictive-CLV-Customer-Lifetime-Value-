# Predictive CLV (Customer Lifetime Value)

## Problem Statement
Tim marketing dari perusahaan asuransi menghadapi masalah dalam **mengoptimalkan strategi pemasaran karena kurangnya prediksi yang akurat tentang untuk customer yang memiliki nilai yang menguntungkan bagi perusahaan**. Tim marketing kesulitan menentukan alokasi anggaran pemasaran dan retensi yang tepat karena tidak mengetahui nilai seumur hidup pelanggan secara akurat. CFO mengalami tantangan dalam mengelola anggaran secara efisien akibat pengeluaran yang tidak tepat sasaran. Masalah ini mengakibatkan tingginya biaya akuisisi pelanggan baru tanpa peningkatan signifikan dalam nilai seumur hidup pelanggan. Penyelesaian masalah ini penting **untuk meningkatkan profitabilitas perusahaan dengan mengurangi biaya pemasaran dan meningkatkan return on investment (ROI) pemasaran**.

## Tujuan
Tujuan dari proyek ini adalah untuk membangun model prediksi yang akurat untuk CLV. Model ini akan membantu bisnis dalam mengidentifikasi pelanggan dengan nilai seumur hidup tinggi, memungkinkan pengambilan keputusan yang lebih tepat dalam strategi pemasaran.

## Context
Customer Lifetime Value (CLV) adalah metrik yang memperkirakan total nilai yang akan diberikan oleh seorang pelanggan kepada bisnis selama hubungan mereka dengan bisnis tersebut. Memiliki model prediktif untuk CLV memungkinkan bisnis untuk:
- Mengidentifikasi pelanggan berharga yang harus difokuskan untuk kampanye retensi.
- Mengalokasikan anggaran pemasaran secara lebih efektif.
- Mengoptimalkan strategi penjualan dan layanan pelanggan.

## Data
| **Attribute**            | **Data Type** | **Description**                                  |
|--------------------------|---------------|--------------------------------------------------|
| Vehicle Class            | Kategorikal        | Kelas kendaraan (misal: Four-Door Car, Two-Door Car) |
| Coverage                 | Kategorikal        | Jenis cakupan asuransi (misal: Basic, Extended, Premium) |
| Renew Offer Type         | Kategorikal        | Tipe penawaran pembaruan (misal: Offer1, Offer3) |
| Employment Status        | Kategorikal        | Status pekerjaan pelanggan (misal: Employed, Retired) |
| Marital Status           | Kategorikal        | Status perkawinan pelanggan (misal: Married, Divorced) |
| Education                | Kategorikal        | Tingkat pendidikan pelanggan (misal: College, Master) |
| Number of Policies       | Numerikal         | Jumlah polis asuransi yang dimiliki pelanggan    |
| Monthly Premium Auto     | Numerikal         | Premi bulanan untuk asuransi kendaraan           |
| Total Claim Amount       | Numerikal (Kontinu)         | Total jumlah klaim yang diajukan pelanggan       |
| Income                   | Numerikal (Kontinu)         | Pendapatan tahunan pelanggan                     |
| Customer Lifetime Value  | Numerikal (Kontinu)         | Nilai umur pelanggan bagi perusahaan asuransi    |
| Location Code            | Kategorikal        | Kode lokasi tempat tinggal pelanggan (misal: Urban, Suburban, Rural) |
| Gender                   | Kategorikal        | Jenis kelamin pelanggan (misal: Male, Female) |
| Months Since Policy Inception | Numerikal         | Jumlah bulan sejak kebijakan asuransi dimulai     |
<br>
Dataset ini diolah dan digunakan untuk melatih model prediksi menggunakan berbagai teknik Machine Learning seperti regresi linear, Random Forest, dan lainnya.

## File Notebook
Notebook ini berisi langkah-langkah berikut:
1. **Import Data dan Libraries:** Melakukan import data dan library yang dibutuhkan.
2. **Exploratory Data Analysis (EDA):** Menganalisis data untuk memahami distribusi dan hubungan antar fitur.
3. **Preprocessing Data:** Melakukan pembersihan dan transformasi data sebelum dimasukkan ke dalam model.
4. **Modeling:** Melatih beberapa model prediksi dan memilih model terbaik berdasarkan metrik evaluasi.
5. **Evaluasi Model:** Mengevaluasi performa model menggunakan data validation dan unseen data.
6. **Finalisasi Model:** Menyimpan model terbaik untuk digunakan dalam prediksi masa depan.

## Usage
Untuk menjalankan proyek ini, pastikan Anda memiliki environment yang sesuai dengan instalasi library yang diperlukan. Anda dapat mengikuti langkah-langkah dalam notebook untuk memuat data, melatih model, dan membuat prediksi.

