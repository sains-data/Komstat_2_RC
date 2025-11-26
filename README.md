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
Dataset mencakup 32 kabupaten/kota di Lampung dan Sumatera Selatan.
Proses analisis meliputi:
- Penggabungan dan preprocessing data penyakit & fasilitas
- Normalisasi & standarisasi variabel
- Implementasi K-Means dalam kelas S4
- Analisis cluster + evaluasi fasilitas di tiap cluster
- Visualisasi hasil (scatter plot & ringkasan)
