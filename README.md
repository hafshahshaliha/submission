Halo Reviewer! 
Projek akhir Data Science yang saya buat untuk memenuhi kriteria kelulusan kelas Data Science ini berjudul 'Espana Warehouse'.
Dataset yang saya gunakan adalah E-commerce Public Dataset (Kriteria 1: Menggunakan Salah Satu dari Dataset yang Telah Disediakan), saya mengambil 4 dataset dari 9 dataset yang tersedia di folder E-commerce.
Dataset yang saya pakai untuk projek ini adalah Customers, Orders, Order Items dan Product. 
Projek di github ini berisi 4 file, yaitu all_data.csv, app.py, requirement.txt dan espana_warehouse.png. File all_data.csv berisi pengolahan data di awal yang mencakup Data Wrangling dan Exploratory Data, file app.py berisi bahan-bahan visualisasi data di streamlit dan file requirement.txt berisi requirement yang perlu di unggah ke github bersamaan dengan file app.py dan file png untuk men-deploy visualisasi dari projek yang saya kerjakan di web-app streamlit. 
Tahap awal sebelum mengolah data adalah menentukkan pertanyaan bisnis (Kriteria 2: Melakukan Seluruh Proses Analisis Data). 2 pertanyaan bisnis yang saya coba pecahkan menggunakan analisa ini adalah ; 
1. Bagaimana kostumer Espana Warehouse tersebar secara geografis? Tujuannya adalah untuk membuat pabrik cabang di state yang memiliki pelanggan paling banyak sehingga Espana Warehouse dapat menekan biaya distribusi
2. Produk apa yang memiliki penjualan terbaik dan terburuk? Dengan ini Espana Warehouse dapat melakukan analisa dan lebih lanjut mengenai kebutuhan pelanggan terhadap produk kami.

Setelah menentukan petanyaan bisnis, saya mulai menyiapkan dataset dan mengolahnya di google colab. Dalam file all_data.csv saya telah membagi dengan rapi olahan data saya menjadi Data Wrangling dan Exploratory Data. Dalam tahapan Data Wrangling saya mengumpulkan, menilai dan membersihkan data, sedangkan dalam tahapan Exploratory Data saya mengeksplorasi data sesuai dengan kebutuhan saya, sebagai contoh saya menggunakan kode 'customers_df.describe(include="all")' untuk mengeksplor frekuensi transaksi dan membaca segmentasi geografis pelanggan.
Untuk mempermudah analisa, saya juga mengelompokkan 4 dataset awal menjadi 1 dataset yang padu (Kriteria 3: Proses Analisis Dibuat dalam Notebook yang Rapi) untuk menjadi dataset dalam pembuatan dashboard (app.py).
Dan tahapan terakhir 
