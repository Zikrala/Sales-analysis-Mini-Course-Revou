# Sales-analysis-Mini-Course-Revou
Mini Project : Sales Analysis using Python

Project ini merupakan mini project dari mini course **Data Analytics RevoU**.  
Analisis dilakukan menggunakan dataset penjualan (source: [RevoU mini course dataset]) untuk menjawab beberapa pertanyaan bisnis.

![Tabel Dataset](images/example-dataset.jpg)

---

## Questions to be Answered

1. **Which product lines have the highest and lowest sales?**  
   - Analisis: menentukan penjualan produk tertinggi dan terendah
   - Visualisasi: bar chart.
   - **Insight:** Product "Classic Cars" memiliki penjualan tertinggi, sedangkan produk "Trains" yang paling rendah. Penjualan kendaraan dipengaruhi oleh segmen pasar dan fungsi produk. Classic Cars mendominasi karena daya tarik koleksi dan nilai prestise. sedangkan Trains termasuk pada barang dengan nilai tinggi dimana konsumen utama biasanya adalah institusi besar, pola pembeliannya cenderung berbasis proyek besar bukan berulang di setiap bulannya. Perusahaan dapat memanfaatkan seasonality dan event khusus untuk memaksimalkan penjualan, terutama pada produk high demand seperti Classic Cars.

![Penjualan tertinggi dan terendah](images/bar-chart-highest&lower-sales)

2. **Show sales performance over time, is there any pattern?**  
   - Analisis: membuat tren penjualan bulanan/harian.  
   - Visualisasi: line chart.  
   - **Insight:** Pola data menunjukan fluktuatif, terdapat pola kenaikan penjualan pada bulan Oktober–November, setelah puncak penjualan terlihat adanya penurunan drastis di bulan Desember. Ada beberapa kemungkinan yang dapat mempengaruhi yaitu musim liburan, adanya event tertentu atau adanya promo akhir tahun.

![Tren Penjualan Per Bulan](images/line-chart-sales-performance)

3. **How does deal size (small, medium, large) correlate with total sales?**  
   - Analisis: menghitung kontribusi (%) setiap deal size.  
   - Visualisasi: pie chart atau stacked bar chart.  
   - **Insight:** Deal size "Medium" menyumbang persentase terbesar terhadap total penjualan yaitu sebesar 59.83%. Meskipun Deal Size Large memberikan dampak signifikan sesekali, tetapi keberlanjutan pendapatan justru banyak didorong oleh Deal Size Medium yang terjadi secara konsisten. Hal ini menunjukkan bahwa strategi bisnis sebaiknya fokus menjaga dan memperbanyak Deal Size Medium. karena segmen inilah yang menjadi pendorong utama dalam penjualan.

![Kontribusi Deal Size](images/table-deal-size)

---

## Tools
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab

---

## Analysis Process

1. **Data Cleaning**
- Mengahapus data duplikat.
- Menangani data kosong (missing value).
- Menstandarkan format kolom.

2. **Exploratory Data Analysis (EDA)**
- Mengidentifikasi produk dengan penjualan tertinggi dan terendah.
- Menganalisis pola tren penjualan per bulan.
- Menganalisis kontribusi setiap kategori Deal Size terhadap total penjualan.

3. **Data Visualization**
- Bar chart --> menampilkan produk dengan penjualan tertinggi dan terendah.
- Line chart --> menampilkan tren penjualan per bulan.
- Table --> menampilkan kontribusi masing-masing Deal Size dalam persentase.

---

## Key Findings
- Product line paling laris: **Classic Cars**  
- Product line dengan penjualan terendah: **Trains**  
- Pola penjualan cenderung meningkat di bulan **Oktober-November**.  
- Deal size **Medium** menyumbang kontribusi tertinggi terhadap total sales **[59.83 %]**.  

---

