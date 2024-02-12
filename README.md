# Proyek A/B Testing: Meningkatkan Sistem Rekomendasi di Toko Online Internasional


## Pendahuluan
Pada tanggal 7 Desember 2020, toko online internasional meluncurkan sebuah uji coba A/B dengan tujuan menguji perubahan terkait pengenalan sistem rekomendasi yang ditingkatkan. Uji coba ini diberi nama "recommender_system_test" dan terbagi menjadi dua kelompok: Kelompok A sebagai kontrol dan Kelompok B dengan embel-embel rute pembayaran baru.


## Tujuan
- Tujuan Uji Coba: Menguji perubahan terkait pengenalan sistem rekomendasi yang ditingkatkan.
    - Hasil yang Diharapkan: Dalam waktu 14 hari sejak pendaftaran, pengguna akan menunjukkan peningkatan konversi ke tampilan halaman produk (event `product_page`), tampilan kartu produk (event `product_card`), dan pembelian (`event purchase`). Setiap tahap dari funnel `product_page` → `product_card` → `purchase` harus mengalami peningkatan minimal 10%.


## Tahapan
Terdapat 4 file .csv(**berada di deskripsi teknis**) untuk tahapan ini, yaitu Berikut tahapan-tahapan yang akan kita lakukan:


1. Mengeksplorasi Data:
    - Konversi Tipe Data: Memeriksa apakah perlu mengonversi tipe data pada setiap file data yang diberikan.
    - Data Duplikat dan Hilang: Menemukan adanya nilai duplikat atau hilang dalam dataset. Jika ada, menjelaskan sifat dan dampaknya terhadap analisis.

2. Analisis Data Eksploratif (EDA):
    - Distribusi Jumlah Event per Pengguna: Menyelidiki apakah jumlah event per pengguna didistribusikan secara merata di antara sampel A dan B.
    - Pengguna yang Masuk ke Dua Sampel: Mengidentifikasi apakah ada pengguna yang masuk ke kedua sampel, dan jika ada, mengevaluasi dampaknya terhadap hasil uji coba.
    - Distribusi Jumlah Event per Hari: Menganalisis cara distribusi jumlah event berdasarkan hari.

3. Menganalisis Konversi di Berbagai Tahap Funnel:
    - Mengidentifikasi dan menganalisis tingkat konversi pengguna pada setiap tahap funnel, yaitu dari tampilan halaman produk (product_page) ke tampilan kartu produk (product_card) hingga pembelian (purchase)

4. Evaluasi Hasil A/B Test:
    - Interpretasi Hasil A/B Test: Menyajikan temuan dan kesimpulan dari hasil uji coba A/B, apakah terdapat perbedaan yang signifikan di antara kelompok A (kontrol) dan B (rute pembayaran baru).
    - Penggunaan Z-Criterion: Menggunakan z-criterion untuk memeriksa perbedaan statistik antara proporsi pada kedua kelompok.


