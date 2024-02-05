## Muhammad-Hamzah-Capstone-Modul-2-

[Transjakarta](https://transjakarta.co.id/produk-dan-layanan/layanan-bus/transjakarta/)

# Latar Belakang

Transjakarta adalah moda transportasi umum yang berfokus kepada pelayanan dalam kota. Transjakarta sudah berdiri sejak 20 tahun yang lalu dan semua element masyarakat sudah merasakan dampak baik dari moda transportasi ini, akan tetapi ada dari sebagian penumpang transjakarta ada yang tidak merasakan dampak baik dari fasilitas transjakarta diantaranya usia lanjut dan masih banyak pengamatan lainnya

# Perumusan Masalah 

1. transjakarta ingin mengetahui penumpang mana saja yang belum mendapatkan hak & prioritas yang telah di tentukan oleh transjakarta 
2. memahami pola perjalanan penumpah di berbagai koridor
3. menilai waktu sibuk dan area dengan jumlah penumpang tertinggi
4. menganalisis preferensi penumpang terhadap titik masuk dan keluar tertentu
5. megetahui fasilitas IOT yang sering missed pada tapsout berdasarkan koridor

# Goals

1. Merancang rute atau jadwal baru berdasarkan kebutuhan dan preferensi penumpang
2. Membuat rencana investasi berdasarkan data proyeksi evaluasi kapasitas saat ini
3. Menyusun strategi untuk meningkatkan efisiensi operasional secara keseluruhan
4. Menilai data untuk mengidentifikasi titik-titik potensial risiko keselamatan.
5. Memprioritaskan proyek infrastruktur untuk mendukung pertumbuhan jangka panjang

# Data Understanding

Sebelum masuk ke dalam analisis, penting untuk memahami lebih dalam dataset yang kita miliki dalam tahap pemahaman data. Dengan melakukan proses ini, kita dapat mengidentifikasi anomali-anomali yang mungkin ada dalam dataset dan perlu ditangani pada tahap pembersihan data. Setiap tindakan untuk menangani anomali akan disertai dengan justifikasi, baik berdasarkan pengetahuan domain maupun statistik.

Pertama-tama, mari kita tinjau informasi mengenai usia dalam dataset TransJakarta.

Dataset ini berisi informasi terkait perjalanan penumpang, acces card, fasilitas halte dengan sebaran lainnya, Ada 14 kolom di dalam dataset Transjakarta, yaitu:  

transID: ID transaksi unik untuk setiap transaksi.

payCardID: Identifikasi utama pelanggan yang digunakan sebagai tiket masuk dan keluar.

payCardBank: Nama penerbit kartu bank yang terkait dengan kartu pembayaran pelanggan.

payCardName: Nama pelanggan yang tertanam dalam kartu.

payCardSex: Jenis kelamin pelanggan yang tertanam dalam kartu.

payCardBirthDate: Tahun kelahiran pelanggan.

corridorID: ID koridor atau ID rute yang digunakan sebagai kunci untuk pengelompokan rute.

corridorName: Nama koridor atau nama rute yang mencakup informasi tentang awal dan akhir setiap rute.

direction: Nilai 0 untuk pergi (Go) dan 1 untuk kembali (Back), menunjukkan arah perjalanan rute.

tapInStops: ID titik masuk (entrance) yang digunakan untuk mengidentifikasi nama-nama titik masuk.

tapInStopsName: Nama titik masuk (entrance) di mana pelanggan melakukan tap in.

tapInStopsLat: Garis lintang (latitude) dari titik masuk.

tapInStopsLon: Garis bujur (longitude) dari titik masuk.

stopStartSeq: Urutan dari titik-titik perhentian, berkaitan dengan arah perjalanan.

tapInTime: Waktu tap in, termasuk tanggal dan waktu.

tapOutStops: ID titik keluar (exit) yang digunakan untuk mengidentifikasi nama-nama titik keluar.

tapOutStopsName: Nama titik keluar (exit) di mana pelanggan melakukan tap out.

tapOutStopsLat: Garis lintang (latitude) dari titik keluar.

tapOutStopsLon: Garis bujur (longitude) dari titik keluar.

stopEndSeq: Urutan dari titik-titik perhentian, berkaitan dengan arah perjalanan.

tapOutTime: Waktu tap out, termasuk tanggal dan waktu.

payAmount: Jumlah pembayaran yang dilakukan oleh pelanggan, yang bisa jadi beberapa transaksi gratis dan beberapa yang berbayar.

[Tableau](https://public.tableau.com/app/profile/reza.hamzah/viz/CapstoneModul2TJ/Story1)
