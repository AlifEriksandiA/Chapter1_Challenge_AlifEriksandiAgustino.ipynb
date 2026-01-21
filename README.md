# GDGoC ML Study Jam - Chapter 1 Challenge: The Smartphone Analyst 📱🕵️‍♂️

Repository ini berisi solusi pengerjaan tantangan **Machine Learning Study Jam Chapter 1**. Dalam proyek ini, saya berperan sebagai *Lead Data Analyst* di sebuah toko gadget untuk memecahkan masalah bisnis menggunakan manipulasi data dengan **Pandas**.

## 📝 Deskripsi Proyek

Tujuan dari notebook ini adalah melakukan analisis eksploratif (EDA) sederhana terhadap dataset spesifikasi smartphone (dummy data). Tantangan ini mencakup pembersihan data, pemfilteran, pengelompokan (*grouping*), hingga deteksi anomali.

**Skenario:**
Mengolah dataset berisi 150 data smartphone dengan variabel: `Brand`, `Model`, `RAM_GB`, `Storage_GB`, `Rating`, dan `Price_Juta` untuk menjawab 10 pertanyaan strategis.

## 🛠️ Tech Stack

* **Python**
* **Pandas** (Data Manipulation)
* **NumPy** (Numerical Operations)
* **Google Colab** (Development Environment)

## 🔍 Daftar Misi (Quests)

Berikut adalah 10 analisis yang dilakukan dalam notebook ini:

1.  **Cek Ombak (Overview)**: Memeriksa dimensi data, nama kolom, dan statistik dasar (`describe`).
2.  **Raja Pasar**: Menentukan brand dengan jumlah model terbanyak (`value_counts`).
3.  **Storage Wars**: Mencari HP dengan kapasitas penyimpanan terbesar.
4.  **Budget vs Premium**: Mengidentifikasi rentang harga (Termurah & Termahal).
5.  **The Gaming Beast**: Filtering HP Gaming (RAM > 12GB & Storage ≥ 512GB).
6.  **Sobat Mahasiswa**: Rekomendasi HP *worth it* (Harga < 7 Juta & Rating > 4.5).
7.  **Fanboy Apple**: Sorting produk Apple dari termahal ke termurah.
8.  **Rata-Rata Harga per Brand**: Grouping data untuk melihat rata-rata harga setiap brand.
9.  **Value for Money (Feature Engineering)**: Membuat metrik baru (`Value_Skor`) untuk mencari HP dengan performa terbaik dibanding harganya.
10. **The Detective (Anomaly Detection)**: Mencari data error/pencilan (Outliers) seperti harga tidak masuk akal atau spesifikasi mustahil.

## 📂 Struktur Dataset

Dataset dibuat secara *random/dummy* menggunakan script Python di awal notebook, mencakup:
* **Total Baris**: 150
* **Kolom**: Brand, Model, RAM, Storage, Rating, Price.
* **Anomali**: Terdapat data "Prototype X" dan "Nokia 3310 Reborn" sebagai jebakan analisis.

## 🚀 Cara Menjalankan

1.  Buka file `.ipynb` di repository ini.
2.  Anda dapat menjalankannya langsung di GitHub (Static View) atau membukanya menggunakan **Google Colab**.
3.  Pastikan menjalankan sel (cell) pertama terlebih dahulu untuk men-generate dataset dummy.

---

## 👤 Author

**Alif Eriksandi Agustino**
* **Program**: GDGoC ML Study Jam
* **GitHub**: [AlifEriksandiA](https://github.com/AlifEriksandiA)

---
