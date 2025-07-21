# Judul Project
Menganalisa Aplikasi Swiggy Untuk Menentukan Makanan, Kota, dan Area Untuk Membuka Resto

## Repository Outline
1. *P0M1_Putra_Fisabil_Muhammad_dataset.csv* - dataset dari kaggle dalam bentuk CSV [Link](https://www.kaggle.com/datasets/abhijitdahatonde/swiggy-restuarant-dataset)
2. *description.md* - penjelasan tugas
3. *P0M1_Putra_Fisabil_Muhammad.csv* - Data yang sudah di cleaning untuk digunakan pada tableau
4. *P0M1_Putra_Fisabil_Muhammad.ipynb* - Proses persiapan, analisis dan visualisasi data didalam notebook ini
5. *P0M1_Putra_Fisabil_Muhammad.twb* - hasil visualisasi menggunakan tableau

## Problem Background
anda merupakan konsultan resto yang ingin membuatkan client anda produk makanan/minuman yang cocok untuk di jual secara online dan menentukan lokasi mana yang cocok untuk membuat restonya. akan tetapi kamu masih bingung ingin membuat makanan apa dan lokasi mana yang cocok, jadi kamu ingin menganalisa makanan apa yang paling tinggi rating dan peringkat paling cepat untuk disajikan serta lokasi mana yang memiliki potensi besar untuk membuat resto menggunakan data aplikasi swiggy online.

## Project Output
dapat membuat keputusan dalam menentukan makanan lokasi dan area serta harga yang pas untuk client disertakan visualisasi kepada client

## Data
Data columns (total 10 columns):
 #   Column         Non-Null Count  Dtype  
---  ------         --------------  -----  
 0   ID             8680 non-null   int64  untuk id restoran
 1   Area           8680 non-null   object distrik kota
 2   City           8680 non-null   object nama kota
 3   Restaurant     8680 non-null   object nama restoran
 4   Price          8680 non-null   float64 rata2 harga resto
 5   Avg ratings    8680 non-null   float64 rata rata rating
 6   Total ratings  8680 non-null   int64  jumlah rating
 7   Food type      8680 non-null   object tipe makanan pada restoran
 8   Address        8680 non-null   object alamat
 9   Delivery time  8680 non-null   int64 waktu pengiriman

## Method
pada tugas ini saya menggunakan **pearson korelasi** untuk menganalisa hubungan harga dengan rating dan waktu pengiriman dengan rating. dan  **anova one way** untuk menganalisa apakah Tipe Makanan Memiliki Pengaruh Terhadap Rating

## Stacks
- pandas – Digunakan untuk manipulasi dan analisis data. Ini memungkinkan pemuatan dataset, pembersihan data, dan melakukan operasi seperti pengelompokan, penyaringan, dan agregasi.

- numpy – Digunakan untuk fungsi matematika yang mendukung perhitungan numerik secara efisien.

- scipy – Digunakan untuk analisis ilmiah dan statistik, dalam proyek ini digunakan untuk melihat korelasi antara tingkat bunuh diri dan PDB.

- matplotlib – Merupakan dasar dari pustaka visualisasi untuk seaborn.

- seaborn – Dibangun di atas matplotlib, digunakan untuk membuat plot dan grafik statis seperti grafik garis, diagram batang, dan histogram untuk memvisualisasikan tren dan perbandingan.

- plotly – Digunakan untuk membuat visualisasi choropleth.

## Reference
Link Online Tableau [Link](https://public.tableau.com/views/P0M1_Putra_Fisabil_Muhammad/StatistikAnalis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Referensi tambahan:**
- Referensi Tableau[Link](https://docs.google.com/presentation/d/1jeytAm8tbs-TF5XilBohYu7hJWByUfS7WaWumzGdzeA/edit?slide=id.g2e28296a2f6_0_135#slide=id.g2e28296a2f6_0_135)
- Pandas [Link](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html)
