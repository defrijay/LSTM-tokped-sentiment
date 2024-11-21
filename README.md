# Sentiment Analysis using LSTM and Bidirectional LSTM

Proyek ini adalah implementasi analisis sentimen menggunakan model LSTM (Long Short-Term Memory) dengan arsitektur Bidirectional. Data yang digunakan merupakan kumpulan ulasan pelanggan dengan label sentimen untuk melatih dan mengevaluasi model.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Creator](#project-creator)

## Overview

Analisis sentimen adalah proses pengolahan teks untuk memahami opini atau perasaan dari teks tertentu. Dalam proyek ini, model LSTM digunakan untuk memprediksi sentimen berdasarkan ulasan pelanggan.

### Tahapan Utama

1. **Prapemrosesan Data**: Membersihkan teks, tokenisasi, dan padding.
2. **Modeling**: Membangun dan melatih model LSTM menggunakan embedding layer.
3. **Evaluasi**: Menggunakan metrik seperti classification report dan confusion matrix.

## Features

- **Visualisasi Data**: Distribusi sentimen dan WordCloud untuk melihat kata-kata populer.
- **Text Preprocessing**: Normalisasi teks untuk meningkatkan kualitas data.
- **Tokenization & Padding**: Mengonversi teks menjadi angka dengan panjang konsisten.
- **LSTM Model**: Menggunakan arsitektur Bidirectional untuk menangkap konteks teks.
- **Evaluasi Model**: Metrik akurasi, confusion matrix, dan classification report.

## Dataset

Dataset yang digunakan adalah dataset `sentiment.csv` yang memuat ulasan pelanggan dengan kolom:
- **Customer Review**: Ulasan pelanggan dalam bentuk teks.
- **Sentiment**: Label sentimen (misalnya, positif, negatif, netral).

### Contoh Data

| Customer Review                             | Sentiment |
|---------------------------------------------|-----------|
| Produk ini sangat bagus dan berkualitas.    | Positif   |
| Saya kecewa dengan pelayanan yang diberikan.| Negatif   |

### Instalasi

```python

pip install numpy pandas matplotlib seaborn nltk tensorflow googletrans wordcloud scikit-learn

```