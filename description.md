# Judul Project

## Repository Outline
1. assignment-rubrics.png -> berisi rubriks penilaian dari milestone
2. description.md -> Penjelasan gambaran spesifik project analisis penjualan dari sebuah restaurant dari tahun 2022 sampai 2023
3. P0M1_Nugroho_wicaksono_dataset.csv -> dataset dari restaurant yang ingin dianalisis
4. P0M1_Nugroho_wicaksono.ipynb -> notebook yang berisi analisa dari dataset yang diambil


## Problem Background
### topik permasalahan

topik dari dataset yang saya ambil membahas tentang penurunan penjualan dari restaurant X

### Problem Staement 

Restoran X mengalami penurunan kinerja penjualan yang ditandai dengan menurunnya jumlah transaksi dan frekuensi pembelian ulang dari pelanggan. Untuk mengatasi hal ini, diperlukan pendekatan berbasis data guna mengidentifikasi item menu yang diminati, waktu penjualan tertinggi, serta perilaku pelanggan. Dengan analisis tersebut, restoran dapat merancang strategi promosi yang lebih personal dan tepat sasaran untuk meningkatkan pengalaman pelanggan, mendorong loyalitas, serta meningkatkan jumlah transaksi hingga 15% dalam kurun waktu 90 hari.

### Latar Belakang

Restoran X telah menghadapi penurunan pendapatan yang konsisten, yang menandakan penurunan kinerja penjualan secara keseluruhan. Meskipun restoran menawarkan berbagai macam item menu, data menunjukkan bahwa lalu lintas pelanggan dan pembelian berulang menurun. Untuk mengatasi hal ini, bisnis berencana untuk memanfaatkan data transaksional yang tersedia - yang mencakup atribut utama seperti detail pesanan, jenis barang, harga, jumlah yang terjual, nilai transaksi, waktu penjualan, dan staf yang terlibat - untuk mendorong retensi pelanggan, meningkatkan frekuensi pembelian, dan meningkatkan keberlanjutan bisnis secara keseluruhan.


## Project Output
1. Statistik Deskriptif
    Menampilkan metrik seperti mean, standar deviasi untuk variabel utama

2. Statistik Inferensial (ANOVA)
    Analisis ANOVA satu arah dan dua arah untuk menguji ada perbedaan signifikan dari ketiga jenis transaksi terhadap jumlah penjualan

3. Visualisasi Interaktif
- Heatmap Puncak Transaksi Penjualan Berdasarkan Hari dan Waktu
- Bar chart untuk melihat item yang paling laris dan tidak diminati
- double line chart untuk melihat tren total transaksi dan pendapatan dalam 6 bulan terkahir

4. Insight Bisnis
Fokus pada produk dengan margin tinggi untuk memaksimalkan keuntungan, bukan hanya volume.
Mengoptimalkan jadwal staf dan jam operasional berdasarkan pola waktu transaksi tertinggi.
Mengevaluasi efektivitas promo secara berkala untuk memastikan kontribusinya terhadap cashflow.
Melakukan pelatihan staf berdasarkan kinerja individu untuk meningkatkan pelayanan dan produktivitas.

## Data
### Dataset sales restaurant
#### Kolom Numerikal:
1.	order_id 		 
2.	item_price		
3.	quantity 		
4.	transaction_amount 	
#### Kolom Kategorikal:
1.	item_name 		   
2.	item_type 		    
3.	transaction_type 	
4.	received_by 	
5. time_of_sale


## Method
Project ini menggunakan pendekatan Exploratory Data Analysis (EDA) dan Statistik Inferensial untuk menggali insight dari data penjualan Walmart periode 2019–2023. Adapun metode yang digunakan meliputi:

1. Statistik Deskriptif
- Menghitung ukuran pemusatan data seperti mean, median
- Mengukur sebaran data menggunakan standar deviasi

2. Visualisasi Data
- Digunakan bar chart, heatmap, dan double line chart 
- Visualisasi interaktif dibangun menggunakan Tableau untuk memudahkan interpretasi data.

3. Statistik Inferensial (ANOVA)
    Analisis ANOVA satu arah ]untuk menguji ada perbedaan signifikan dari ketiga jenis transaksi terhadap jumlah penjualan

## Stacks
1. Bahasa Pemrograman
    Python: Digunakan untuk pengolahan data, analisis statistik, visualisasi data, dan perhitungan statistik inferensial.

2. Library Python
- pandas: Untuk manipulasi data, agregasi, transformasi, dan analisis statistik deskriptif.
- numpy: Untuk perhitungan numerik, distribusi warna gradasi, dan array numerik.
- matplotlib & seaborn: Untuk visualisasi data seperti bar chart, heatmap, dan double line chart.
- scipy.stats: Untuk uji statistik inferensial seperti One-Way ANOVA dan Two-Way ANOVA.

3. Tools Visualisasi
    Tableau Public / Tableau Desktop
    Untuk membuat dashboard interaktif yang menampilkan insight eksploratif dari data 

## Reference
restauran dataset: https://www.kaggle.com/datasets/rajatsurana979/fast-food-sales-report?resource=download

---

**Referensi tambahan:**
- [Basic Writing and Syntax on Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Contoh readme](https://github.com/fahmimnalfrzki/Swift-XRT-Automation)
- [Another example](https://github.com/sanggusti/final_bangkit) (**Must read**)
- [Additional reference](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)