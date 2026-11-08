# 🛒 Segmentasi Pelanggan Berbasis Perilaku Pembelian (RFM) Menggunakan Unsupervised Machine Learning

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/machine--learning-scikit--learn-orange.svg)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/project--status-UTS%20Completed-success.svg)](#)

---

## 📌 Identification & Team

* **Project ID:** A17
* **Nama Kelompok:** ASIK
* **Daftar Anggota Kelompok:**
  1. **231111759** – Nurihsan Febrianto
  2. **23111350** – Ryan Rafly Tanjung
  3. **231112853** – Muhammad Alfisyahrin

---

## 🎯 Deskripsi Masalah

Pelanggan pada industri ritel daring memiliki karakteristik transaksi yang sangat beragam dan tidak seimbang. Temuan awal analisis menunjukkan bahwa **20% pelanggan teratas menyumbang sekitar 77% dari total nilai transaksi (*Monetary*)**. Memperlakukan seluruh pelanggan dengan strategi pemasaran yang seragam berisiko memboroskan anggaran serta tidak efektif.

Proyek ini menerapkan pendekatan *classical unsupervised machine learning* pada dataset transaksi ritel *Online Retail II* untuk mengelompokkan pelanggan berdasarkan perilaku pembelian *Recency, Frequency, dan Monetary* (RFM). Hasil segmentasi ini bertujuan membantu perancangan strategi pemasaran yang presisi, efisien, dan berbasis data tanpa mengandalkan label *ground truth*.

---

## 📁 Struktur Repositori

```text
.
├── assets/
│   ├── rfm_distribution.png       # Distribusi RFM skala asli & transformasi log1p (Gambar 2)
│   ├── elbow_silhouette.png       # Evaluasi penentuan nilai K optimal (Gambar 5)
│   └── pca_clusters.png           # Proyeksi 2D PCA & t-SNE hasil klusterisasi K=4 (Gambar 13)
├── data/
│   └── online_retail_II.csv        # Berkas dataset transaksi ritel
├── notebooks/
│   └── UTS_RFM_Customer_Segmentation.ipynb  # Notebook Colab / Jupyter eksperimen utama
├── README.md                       # Dokumentasi utama repositori
└── requirements.txt                # Dependensi pustaka Python