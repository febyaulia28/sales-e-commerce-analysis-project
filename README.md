# 📊 E-Commerce Customer Segmentation & Revenue Analysis

## 📌 Deskripsi Proyek

Proyek ini merupakan analisis data e-commerce yang bertujuan untuk memahami **perilaku pelanggan**, **kontribusi revenue**, serta **pola penggunaan diskon** melalui pendekatan **RFM (Recency, Frequency, Monetary)**. Hasil analisis divisualisasikan dalam bentuk **dashboard interaktif menggunakan Power BI** untuk mendukung pengambilan keputusan bisnis berbasis data.

---

## 🎯 Tujuan Analisis

* Mengidentifikasi segmen pelanggan berdasarkan perilaku transaksi
* Mengetahui segmen pelanggan dengan kontribusi revenue terbesar
* Menganalisis tren pendapatan dari waktu ke waktu
* Mengevaluasi penggunaan diskon terhadap performa bisnis

---

## 🗂️ Dataset

Dataset yang digunakan merupakan data transaksi e-commerce yang telah melalui proses pembersihan data (data cleaning).

Atribut utama:

* Order Date
* Customer ID
* Quantity Ordered
* Revenue (Net)
* Discount
* Category

---

## 🔍 Metodologi Analisis

1. **Data Cleaning & Preparation**

   * Menghapus data duplikat dan tidak valid
   * Menyesuaikan format tanggal dan numerik

2. **Exploratory Data Analysis (EDA)**

   * Analisis tren revenue bulanan
   * Distribusi order dan revenue per kategori
   * Analisis penggunaan diskon

3. **Customer Segmentation (RFM Analysis)**

   * Recency: jarak waktu transaksi terakhir
   * Frequency: jumlah transaksi pelanggan
   * Monetary: total revenue pelanggan
   * Segmentasi pelanggan berdasarkan skor RFM

4. **Dashboarding (Power BI)**

   * KPI Total Revenue, Total Order, dan Total Customer
   * Tren pendapatan bulanan
   * Distribusi revenue dan quantity per kategori
   * Segmentasi pelanggan dan penggunaan diskon

---

## 📈 Insight Utama

* Segmen **Champion** memberikan kontribusi revenue terbesar dibandingkan segmen lainnya
* Sebagian besar transaksi menggunakan diskon, menunjukkan ketergantungan terhadap promosi
* Terdapat perbedaan signifikan antara kategori dengan volume penjualan tinggi dan kategori dengan revenue tertinggi
* Tren pendapatan menunjukkan fluktuasi bulanan yang mengindikasikan adanya faktor musiman

---

## 💡 Kesimpulan & Rekomendasi

**Kesimpulan:**

* Segmentasi RFM efektif untuk mengidentifikasi pelanggan bernilai tinggi
* Diskon berperan penting dalam mendorong transaksi, namun berpotensi menekan margin

**Rekomendasi:**

* Fokus pada strategi retensi pelanggan di segmen Champion dan Loyal
* Optimalisasi strategi diskon agar lebih tepat sasaran berdasarkan segmen pelanggan

---

## 🛠️ Tools & Teknologi

* Python (Pandas, NumPy, Matplotlib)
* Google Colab
* Power BI
* Git & GitHub

