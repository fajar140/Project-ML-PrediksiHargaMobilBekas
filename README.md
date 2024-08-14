# Project-ML-PrediksiHargaMobilBekas

### Judul Proyek: Model Prediksi Harga Mobil Bekas Menggunakan Metode Random Forest Regression
Nama: Fajar Ibrahim Nasry Hamdan

NPM: 51421685

Kelas: 3IA02

### Deskripsi:
Proyek ini bertujuan untuk memprediksi harga mobil bekas dengan menggunakan metode Random Forest Regression. Model ini dibangun untuk mengatasi tantangan dalam menilai harga mobil bekas, yang dipengaruhi oleh berbagai faktor seperti tahun produksi, harga beli, kilometer yang telah ditempuh, jenis bahan bakar, tipe penjual, tipe transmisi, dan jumlah pemilik sebelumnya.

### Tahapan Proyek:

1. Pengumpulan Data:
Dataset yang digunakan dalam proyek ini diambil dari platform Kaggle, yang merupakan sumber data terkenal untuk berbagai jenis analisis. Dataset ini berisi informasi mengenai mobil bekas yang mencakup fitur-fitur yang relevan untuk prediksi harga.

2. Preprocessing Data:
Data diolah dengan menghapus kolom yang tidak relevan, mengganti nilai unik di kolom yang bersifat kategorikal menjadi numerik, serta menangani outlier untuk meningkatkan kualitas data.

3. Pembangunan Model:
Model dibangun menggunakan algoritma Random Forest Regression, yang merupakan metode ensemble yang menggabungkan hasil dari beberapa pohon keputusan untuk meningkatkan akurasi dan mengurangi overfitting. Data dibagi menjadi data pelatihan dan data pengujian untuk mengevaluasi performa model.

4. Evaluasi Model:
Model dievaluasi menggunakan metrik Mean Absolute Error (MAE) dan Root Mean Squared Error (RMSE). Hasilnya menunjukkan bahwa model ini memiliki performa yang unggul dengan nilai MAE sebesar 0.7436 dan RMSE sebesar 1.256, yang lebih rendah dibandingkan penelitian sebelumnya.

5. Implementasi Prediksi:
Model ini kemudian diimplementasikan dalam aplikasi interaktif menggunakan ipywidgets. Pengguna dapat memasukkan detail mobil dan menerima prediksi harga jual berdasarkan input tersebut.

### Kesimpulan:
Model prediksi harga mobil bekas yang dikembangkan berhasil menunjukkan akurasi yang lebih baik dibandingkan penelitian sebelumnya. Ini menunjukkan bahwa metode Random Forest Regression dapat memberikan prediksi yang akurat dan bermanfaat untuk penentuan harga jual mobil bekas di pasaran.

### Referensi:
1. Kriswantara, B. & Sadikin, R., 2022. Used Car Price Prediction with Random Forest Regressor Model. Journal of Information Systems, Informatics and Computing, 6(1), pp. 40-49.
2. Dataset: https://www.kaggle.com/datasets/pushpakhinglaspure/used-car-price-prediction
