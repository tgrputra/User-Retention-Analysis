# User Retention Analysis

## Overview
**User Retention Analysis** merupakan metrik krusial untuk mengevaluasi *Customer Lifecycle* dan kesehatan operasional pada bisnis ritel. Proyek ini mendemonstrasikan pemrosesan data *end-to-end* dalam memetakan perilaku belanja pelanggan dari waktu ke waktu. 

Objektif utama dalam analisis ini meliputi:
1. **Data Wrangling:** Pembersihan data transaksi historis dari anomali kualitas dan pesanan yang dibatalkan.
2. **Cohort Transformation:** Restrukturisasi data transaksi historis menjadi bentuk matriks *Cohort Analysis*.
3. **Insight Extraction:** Visualisasi *Retention Rate* melalui *Heatmap* untuk mengidentifikasi pola loyalitas dan titik kritis *drop-off* pelanggan.

Hasil akhir dari proyek ini berupa matriks visual yang dapat diimplementasikan sebagai landasan data untuk merancang strategi promosi *win-back* yang lebih tepat sasaran guna menekan angka *churn*.

## Dataset
Dataset yang digunakan dalam proyek ini merupakan **dataset *dummy*** (data sintetis) (`Online Retail Data.csv`). Penggunaan data *dummy* ini ditujukan murni untuk keperluan demonstrasi portofolio analitik, tanpa memuat atau melanggar privasi data pelanggan sungguhan. Dataset ini memuat informasi mengenai ID Pesanan, Kode Produk, Nama Produk, Kuantitas, Tanggal Pesanan, Harga, dan ID Pelanggan.

## Key Insights & Business Recommendations
Berdasarkan visualisasi *Cohort Analysis* yang telah dilakukan, ditemukan beberapa *insight* bisnis sebagai berikut:

1. **Akuisisi pengguna tertinggi** terjadi pada *cohort* Januari 2010, dengan total mencapai 713 pelanggan baru.
2. *Cohort* tersebut menunjukkan performa awal yang paling impresif, mencatatkan ***retention rate* sebesar 39%** pada bulan kedua penggunaannya, tertinggi dibandingkan *cohort* lainnya.
3. Loyalitas jangka panjang juga didominasi oleh *cohort* Januari 2010, di mana kelompok pelanggan ini secara konsisten mempertahankan *retention rate* **di atas 40%** pada bulan-bulan berikutnya.
4. Secara keseluruhan, retensi pelanggan masih menjadi tantangan utama. Hal ini terlihat dari tren penurunan pada mayoritas *cohort*, di mana angka *retention rate* umumnya **tidak mampu menembus batas 50%**.
5. Terdapat penurunan *retention rate* yang sangat drastis pada bulan **Desember 2010** untuk seluruh *cohort*. Namun, perlu dicatat bahwa hal ini kemungkinan besar disebabkan oleh periode pencatatan data yang belum selesai (*incomplete month*), bukan murni karena pergeseran minat pelanggan.
