# **Implementasi K-Means Berbasis Kelas S4 untuk Evaluasi Kapasitas Kesehatan dan Risiko Penyakit di Sumatera Bagian Selatan**
Repositori ini berisi implementasi algoritma K-Means berbasis sistem objek S4 di R untuk memetakan risiko penyakit menular serta mengevaluasi kapasitas fasilitas kesehatan di wilayah Sumatera Bagian Selatan (Sumbagsel).
Data yang digunakan meliputi 32 kabupaten/kota di Provinsi Lampung dan Sumatera Selatan.

## 👥 Team Members (Komstat_2_RC)

| NIM       | Nama              | Email               |
|-----------|------------------|---------------------|
| 123450040 | Aprilia Dewi Hutapea | aprilia.123450040@student.itera.ac.id | 
| 123450037 | Labo Napitupulu | labo.123450037@student.itera.ac.id | 
| 123450028 | Donna Maya Puspita | Donna.123450028@student.itera.ac.id  | 

## 🏥 Business Domain
Masalah kesehatan di Sumbagsel menunjukkan variasi dan ketidakseimbangan antara kebutuhan (beban penyakit) dan kapasitas layanan (fasilitas kesehatan).
Analisis berbasis data membantu:
- Mengidentifikasi zona wabah
- Mengetahui area dengan kekurangan fasilitas
- Menentukan wilayah prioritas intervensi kesehatan
Proyek ini menggabungkan epidemiologi, data mining, dan pemrograman R berbasis S4 untuk mendukung pemetaan risiko dan perencanaan kebijakan.

## 🎯 Objectives
1. Mengembangkan fungsi K-Means menggunakan sistem objek S4 dengan struktur yang lebih formal, modular, dan mudah diperluas.
2. Melakukan clustering wilayah berdasarkan indikator beban penyakit menular.
3. Mengevaluasi kecukupan fasilitas kesehatan (RS, Puskesmas, Klinik, Posyandu) pada tiap cluster.
4. Menyediakan insight kebijakan berbasis data untuk mendukung penanganan penyakit menular lintas wilayah.
   
## 📝 Project Description
Proyek ini mencakup:
🔹 1. Pengolahan Data
- Integrasi data penyakit menular (TBC, HIV, Kusta, Malaria, DBD)
- Integrasi data fasilitas kesehatan (RS, Puskesmas, Klinik, Posyandu)
- Standardisasi, normalisasi, dan imputasi missing value
- Penyatuan dataset Lampung + Sumsel menjadi satu dataframe final
🔹 2. Pengembangan Sistem S4
- Pembuatan class S4 kmeansSumbagselS4
- Slot: data, scaled data, k, centroid, labels, dll.
- Definisi method: initialize, summary, plot, dan fungsi K-Means
- Enkapsulasi data asli & hasil clustering dalam satu objek
🔹 3. Analisis Clustering
- Pemilihan variabel input: indikator beban penyakit
- K-Means dengan k=3
- Evaluasi pusat cluster & karakteristik risikonya
🔹 4. Evaluasi Kapasitas Fasilitas
- Analisis perbandingan “Risk vs Supply”
- Gap analysis antar wilayah
- Identifikasi mismatch antara kebutuhan & layanan
🔹 5. Visualisasi
- Histogram distribusi penyakit & fasilitas
- Peta risiko (scatter Kusta vs DBD)
- Visualisasi centroid cluster
  

