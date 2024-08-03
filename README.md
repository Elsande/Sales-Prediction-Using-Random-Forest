# Sales-Prediction-Using-Random-Forest

Data yang digunakan dalam penelitian ini adalah data penjualan harian toko roti. Data ini mencakup berbagai atribut seperti tanggal, waktu, antrian pembeli, produk, jumlah, dan harga satuan.

### Prapemrosesan Data
Prapemrosesan data adalah langkah penting untuk memastikan bahwa data yang digunakan untuk pelatihan model berkualitas tinggi dan relevan. Setelah prapemrosesan data, dataset yang dihasilkan mengandung informasi tentang total penjualan harian, serta fitur tambahan yang digunakan sebagai input untuk model.

### Pembagian Data
Data dibagi menjadi data pelatihan (80%) dan data pengujian (20%) tanpa pengacakan untuk mempertahankan urutan waktu. Pembagian data ini dilakukan untuk memastikan bahwa model dilatih pada data historis dan diuji pada data yang tidak terlihat sebelumnya untuk mengevaluasi kinerja prediktifnya.

### Modeling
Modelling yang di gunakana adalah Random Forest. Random Forest merupakan  algoritma yang sangat fleksibel dan mampu menangkap kompleksitas dalam data dengan sangat baik. Algoritma ini bekerja dengan membangun banyak pohon keputusan pada sub-sampel dari dataset dan menggunakan rata-rata untuk meningkatkan akurasi prediksi dan mengontrol overfitting.

### Evaluasi
Metode evaluasi yang digunakan adalah Root Mean Squared Error (RMSE). RMSE merupakan matrik yang umum di gunakan untuk mengukur seberapa dekat nilai prediksi dengan nilai aktual. Matrik ini memberikan penalty yang lebih besar unttuk kesalahan yang lebih besar, sehingga sangat cocok untuk mengukur kinerja model prediksi penjualan yang harus sangat akurat


