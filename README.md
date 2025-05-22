# SaaS Sales Data Analysis

Dokumen Jupyter Notebook ini berisi analisis data penjualan SaaS (Software as a Service) untuk memahami tren bisnis, profitabilitas produk, efektivitas diskon, dan identifikasi pelanggan paling bernilai. Analisis dilakukan secara komprehensif mulai dari pembersihan data, eksplorasi, visualisasi, hingga penarikan insight dan rekomendasi bisnis.

## Dataset
- Dataset: [AWS SaaS Sales Dataset](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales)
- Jumlah kolom: 19
- Fitur penting: Order Date, Customer, Product, Sales, Discount, Profit, Segment, Industry, Region

## Struktur Notebook

1. **Data Cleaning**
    - Deteksi dan penanganan duplikat, data tidak konsisten, dan kolom redundan.
    - Konversi tipe data dan penanganan outlier.

2. **Data Analysis**
    - Analisis tren penjualan dan profit secara periodik (bulanan & tahunan).
    - Evaluasi margin keuntungan produk dan efektivitas diskon. 
    - Inferential Statistics Uji Mann-Whitney untuk menguji pengaruh signifikan diskon terhadap profit
    - Identifikasi pelanggan utama dan segmentasi profitabilitas berdasarkan segmen, industri, dan wilayah.
    
3. **Insight & Rekomendasi**
    - Penyajian insight utama dari hasil analisis.
    - Rekomendasi strategis untuk pengambilan keputusan bisnis berbasis data.

## Tools & Library

- Python (pandas, numpy, matplotlib, seaborn, scipy)
- Jupyter Notebook

## Cara Menggunakan

1. Pastikan seluruh dependensi sudah terinstal.
2. Jalankan notebook secara berurutan untuk mereplikasi analisis.
3. Output utama berupa visualisasi, tabel insight, dan rekomendasi bisnis.

## Hasil Utama

- Tren penjualan dan profit meningkat signifikan, terutama di akhir tahun.
- Produk dengan margin tinggi menjadi prioritas pengembangan.
- Diskon besar (>30%) terbukti menurunkan profit tanpa meningkatkan sales secara signifikan.
- 20% pelanggan menyumbang hampir 80% profit (prinsip Pareto berlaku).
- Rekomendasi strategis diberikan untuk optimasi penjualan, diskon, dan retensi pelanggan.

---

Notebook ini dapat digunakan sebagai referensi analisis data penjualan SaaS dan pengambilan keputusan berbasis data untuk bisnis serupa.
