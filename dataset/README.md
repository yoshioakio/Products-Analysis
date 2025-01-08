# Analisis K-Means Clustering dan Prediksi Produk Potensial

## 📑 Kebutuhan Dataset

Analisis ini menggunakan algoritma **K-Means** untuk mengelompokkan produk berdasarkan harga, ongkos kirim, dan ulasan pelanggan. Prediksi produk potensial dilakukan dengan membandingkan performa **Logistic Regression** dan **Support Vector Machine (SVM)** untuk mendukung strategi bisnis yang lebih efektif.

## 🌐 Sumber Dataset

Dataset yang digunakan dalam analisis ini diambil dari Kaggle Brazilian E-Commerce (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), yang mencakup informasi terkait produk, pengiriman, ulasan pelanggan, dan lainnya.

## 🛢️ Tabel Dataset yang Digunakan

Berikut adalah daftar file dataset yang digunakan dalam analisis ini:

1. `olist_products_dataset.csv`
2. `olist_orders_dataset.csv`
3. `olist_order_items_dataset.csv`
4. `olist_order_reviews_dataset.csv`
5. `olist_order_payments_dataset.csv`
6. `product_category_name_translation.csv`
7. `olist_sellers_dataset.csv`

Dataset tersebut dilakukan eksplorasi dan pembersihan data, dan hasil akhirnya disimpan dalam file `final_dataset.csv` yang siap digunakan untuk tahap **clustering data**.

## 🫧 Pemilihan Fitur/Kolom

Berikut adalah fitur/kolom yang dipilih untuk proses clustering:

1. `price`: Harga Produk
2. `freight_value`: Biaya Ongkos Pengiriman
3. `review_score`: Skor Penilaian Produk
4. `shipping_duration_days`: Durasi Waktu Pengiriman
5. `product_complexity`: Informasi Keterangan Produk
6. `delivery_accuracy_days`: Akurasi Waktu Pengiriman
7. `payment_made`: Pembayaran Yang Sudah Dilakukan
8. `product_volume_cm3`: Volume Ukuran Produk
9. `order_status_encoded`: Status Pengiriman Produk

Pemilihan dan penanganan fitur/kolom pada proses clustering ini menghasilkan kolom baru yaitu **cluster_category**, kemudian disimpan dalam file `hasil_clustering.csv` yang siap digunakan untuk tahap **klasifikasi dan prediksi data**.
