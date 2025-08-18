# Restaurant sales analysis
project 1

# 📊 Analisis Penurunan Penjualan Restoran X (2022-2023)

## 📌 Overview
Repositori ini berisi analisis data penjualan Restoran X periode 2022-2023 untuk mengidentifikasi penyebab penurunan penjualan dan memberikan rekomendasi strategis.

## 🚀 Problem Statement
**"Bagaimana Restoran X dapat meningkatkan jumlah transaksi sebesar 15% dalam 90 hari melalui analisis pola penjualan dan perilaku pelanggan?"**

### Latar Belakang Masalah:
- Penurunan konsisten dalam pendapatan restoran
- Menurunnya frekuensi pembelian ulang pelanggan
- Kebutuhan optimasi menu dan jam operasional

## 🎯 Project Objectives
1. Mengidentifikasi item menu paling menguntungkan
2. Menganalisis pola waktu penjualan tertinggi
3. Memberikan rekomendasi strategi peningkatan penjualan

## 📂 Repository Structure
```
├── P0M1_Nugroho_wicaksono_dataset.csv # Dataset penjualan
└── P0M1_Nugroho_wicaksono.ipynb # Notebook analisis

```

# 🔍 Key Insights (Temuan Utama)
### 📈 Analisis Performa Penjualan:
- Tren penurunan transaksi sebesar X% pada semester kedua 2023
- Produk dengan margin tinggi tapi volume rendah: [Produk A, B]
- Jam sibuk: 12.00-14.00 (weekdays), 19.00-21.00 (weekends)

### 📊 Hasil Statistik:
- One-Way ANOVA menunjukkan perbedaan signifikan (p < 0.05) antar jenis transaksi
- Standar deviasi tinggi pada transaksi weekend menunjukkan fluktuasi besar

## 🛠️ Methodology
### 🔧 Teknik Analisis:
1. **Exploratory Data Analysis (EDA)**
   - Statistik deskriptif (mean, median, distribusi)
   - Korelasi antar variabel
2. **Statistik Inferensial**
   - One-Way ANOVA
3. **Visualisasi Data**
   - Heatmap pola penjualan
   - Double line chart tren penjualan
   - Interactive dashboard

### 🧰 Tech Stack:
| Category       | Tools/Libraries |
|---------------|----------------|
| Programming   | Python 3.9+    |
| Data Processing | pandas, numpy |
| Visualization | matplotlib, seaborn, Tableau |
| Statistics    | scipy.stats    |

## 💡 Business Recommendations
1. **Optimasi Menu**:
   - Bundle produk high-margin dengan best-seller
   - Fase-out produk low-margin
2. **Strategi Operasional**:
   - Penambahan staf pada jam sibuk
   - Promosi khusus weekday siang
3. **Loyalty Program**:
   - Reward sistem untuk pembelian berulang
   - Personalisasi promo berdasarkan riwayat order

## 📊 Sample Visualization
![Heatmap Penjualan](https://via.placeholder.com/600x400?text=Sample+Heatmap+Visualization)
*Pola penjualan per jam dan hari*

## 📚 References
- Dataset: [Fast Food Sales Report on Kaggle](https://www.kaggle.com/datasets/rajatsurana979/fast-food-sales-report)
- Analisis ANOVA: [SciPy Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html)
- Best Practice Visualisasi: [Seaborn Gallery](https://seaborn.pydata.org/examples/index.html)

## ✨ Contributors
[Nugroho Wicaksono](https://github.com/HexDamar/Restaurant-sales-analysis-with-pandas-tableu) - Data Analyst

---

🔹 *Last Updated: August 2025*  