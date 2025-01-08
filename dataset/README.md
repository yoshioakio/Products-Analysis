# Penjelasan Dan Rincian Data Set Yang Digunakan

## 📑 Kebutuhan Data Set

Analisis ini menggunakan algoritma K-Means untuk clustering produk berdasarkan harga, ongkos kirim, dan ulasan. Prediksi produk potensial dilakukan dengan membandingkan performa Logistic Regression dan SVM guna mendukung strategi bisnis yang efektif.

## 🌐 Sumber Data Set

Dataset yang digunakan dalam analisis ini diambil dari Dataset [Kaggle Brazilian E-Commerce (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)], yang mencakup informasi terkait produk, pengiriman, dan ulasan pelanggan dan lain sebagainnya.

## 🛢️ Tabel Data Set Yang Digunakan

1. olist_products_dataset.csv
2. olist_orders_dataset.csv
3. olist_order_items_dataset.csv
4. olist_order_reviews_dataset.csv
5. olist_order_payments_dataset.csv
6. product_category_name_translation.csv
7. olist_sellers_dataset.csv

Data set tersebut dilakukan eksplorasi dan pembersihan data, hasil akhirnya disimpan dalam file final_dataset.csv yang siap digunakan untuk tahap clustering data.

## 🫧 Pemilihan Fitur/Kolom

1. price (Harga Produk)
2. freight_value (Biaya Ongkos Pengiriman)
3. review_score (Skor Penilaian Produk)
4. shipping_duration_days (Durasi Waktu Pengiriman)
5. product_complexity (Informasi Keterangan Produk)
6. delivery_accuracy_days (Akurasi Waktu Pengiriman)
7. payment_made (Pembayaran Yang Sudah Dilakukan)
8. product_volume_cm3 (Volume Ukuran Produk)
9. order_status_encoded (Status Pengiriman Produk)

Dari pemilihat dan penaganan fitur/kolom pada proses clustering inih lah menghasilakan fitur/kolom cluster_category yang siap digunakan untuk lanjut ke tahap klasifikasi prediksi data.
