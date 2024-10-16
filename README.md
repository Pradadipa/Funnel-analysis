# Funnel Analysis

Funnel Analysis adalah teknik analisis yang digunakan untuk memantau dan mengevaluasi langkah-langkah yang dilalui pengunjung (users) dalam perjalanan mereka dari tahap awal hingga akhirnya mencapai tujuan konversi, seperti pembelian atau pendaftaran. Analisis ini berguna untuk memahami di mana pengunjung meninggalkan proses dan di mana terjadi penurunan konversi, memungkinkan kita untuk mengidentifikasi area yang perlu diperbaiki dalam pengalaman pengguna.

## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan analisis funnel pada data e-commerce untuk memahami perjalanan pengguna dari saat mereka mengunjungi **homepage** hingga melakukan **pembelian (purchase)**. Analisis ini membantu mengidentifikasi tahapan mana yang memerlukan perhatian lebih lanjut untuk meningkatkan tingkat konversi dan memperbaiki pengalaman pengguna.

## Tahapan Funnel Analysis

### 1. **Homepage**
   Pengunjung pertama kali tiba di **homepage** dari berbagai saluran pemasaran seperti iklan, media sosial, atau referral. Halaman ini memberikan gambaran umum tentang produk dan layanan yang ditawarkan oleh situs e-commerce. Di sinilah keberhasilan awal kampanye pemasaran diukur.

### 2. **Product Page**
   Setelah berada di homepage, pengunjung dapat melanjutkan untuk melihat lebih dalam produk yang ditawarkan melalui **product page**. Di tahap ini, pengunjung mengeksplorasi produk yang mereka tertarik, melihat detail, gambar, harga, dan ulasan produk.

### 3. **Purchase**
   Jika pengunjung merasa tertarik dengan produk, mereka kemudian memutuskan untuk melakukan **purchase** dan memasukkan produk ke dalam **cart**. Ini adalah tahap penting, karena konversi dari **product page** ke **purchase** menunjukkan minat yang lebih mendalam terhadap produk.

### 4. **Checkout**
   Setelah memasukkan produk ke dalam cart, pengunjung harus mengisi informasi pengiriman dan pembayaran pada halaman **checkout**. Ini adalah tahap yang menentukan apakah mereka akan menyelesaikan transaksi atau tidak.

### 5. **Cart**
   Terakhir, setelah menyelesaikan checkout, pengunjung yang berhasil akan memproses **cart** dan melakukan pembayaran akhir. Halaman **cart** menunjukkan konversi terakhir dari pengunjung yang berhasil menyelesaikan pembelian.

## Tujuan Analisis Funnel

1. **Identifikasi Hambatan**: Menyediakan wawasan tentang di mana pengunjung kehilangan minat dan berhenti pada setiap tahapan.
2. **Optimasi Konversi**: Mengidentifikasi area yang dapat diperbaiki untuk meningkatkan tingkat konversi dan pengalaman pengguna.
3. **Meningkatkan Pengalaman Pengguna**: Memahami perjalanan pengguna dan merancang ulang strategi pemasaran dan desain antarmuka pengguna untuk mengurangi tingkat pengabaian.
4. **Menentukan Prioritas**: Memberikan wawasan untuk memprioritaskan perubahan atau optimasi di tahapan funnel yang paling kritis.

## Dataset yang Digunakan

Analisis ini menggunakan data dari log pengunjung e-commerce, yang mencakup informasi mengenai:

- Jumlah pengunjung yang mengunjungi **homepage**.
- Jumlah pengunjung yang melanjutkan ke **product page**.
- Jumlah pengguna yang melakukan **purchase**.
- Jumlah pengguna yang menyelesaikan **checkout**.
- Jumlah pembelian yang dilakukan di **cart**.

## Metodologi

- **Penghitungan Konversi**: Menghitung rasio konversi antara setiap tahapan funnel untuk menentukan tingkat keberhasilan pengunjung melanjutkan ke langkah berikutnya.
- **Identifikasi Drop-off**: Menilai persentase penurunan antara setiap tahapan untuk mengidentifikasi area yang memerlukan perhatian.
- **Analisis Faktor Penyebab**: Mengidentifikasi faktor-faktor yang mungkin menyebabkan penurunan konversi, seperti ketidakpuasan dengan pengalaman pengguna, harga yang tidak menarik, atau masalah dalam proses checkout.

## Langkah-langkah Analisis

1. **Data Collection**: Kumpulkan data dari setiap tahapan funnel.
2. **Data Processing**: Bersihkan dan transformasikan data untuk siap dianalisis.
3. **Analysis**: Lakukan analisis funnel dengan menghitung rasio konversi dan persentase penurunan pada setiap tahapan.
4. **Visualization**: Visualisasikan hasil analisis funnel untuk memberikan gambaran yang jelas tentang perjalanan pengunjung.

## Cara Menggunakan

1. Clone repository ini:
   ```bash
   git clone https://github.com/Pradadipa/Funnel-analysis.git
   
