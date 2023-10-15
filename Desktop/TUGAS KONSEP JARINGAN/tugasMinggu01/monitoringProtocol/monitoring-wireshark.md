## Monitoring Protocol HTTP, TELNET, DNS
**Nama** : Aulia Ilham Nur Alfian </br>
**NRP** : 3122600024 </br>
**Kelas** : 2 D4 IT A </br>
**Mata Kuliah** : Konsep Jaringan </br>
<div  align="center">
<img  src="assets/Screenshot 2023-08-29 123453.png">
<p><strong>Gambar:</strong> Wireshark http.cap</p>
</div>

Melakukan pemantauan protokol HTTP, Telnet, dan DNS dengan menggunakan alat Wireshark melibatkan beberapa langkah penting yang meliputi perekaman dan analisis paket data yang mengalir melalui antarmuka jaringan yang Anda gunakan. Wireshark, sebagai alat analisis jaringan yang sangat berguna, memberikan kesempatan untuk secara cermat memeriksa paket data dan menjalankan analisis mendalam terhadap protokol yang terlibat. Berikut adalah panduan langkah demi langkah yang komprehensif dalam melakukan pemantauan protokol HTTP, Telnet, dan DNS menggunakan Wireshark:

**Langkah 1: Unduh dan Instal Wireshark**
Pertama-tama, pastikan perangkat Anda sudah memiliki perangkat lunak Wireshark yang terpasang. Jika belum, Anda dapat mengunduh versi terbaru dari situs resmi Wireshark (https://www.wireshark.org/) dan mengikuti petunjuk instalasinya.

**Langkah 2: Memulai Perekaman**
Setelah Wireshark siap digunakan, tindakan berikutnya adalah memulai proses perekaman paket data:
- Buka aplikasi Wireshark yang telah diinstal.
- Pilih antarmuka jaringan yang ingin Anda amati. Antarmuka ini memberikan tampilan aliran data yang sedang berlangsung. Anda bisa menggunakan contoh file yang disediakan, seperti "http.cap," "telnet.cap," atau "dns.cap."
- Dengan menekan tombol "Open a capture file" atau mengklik ikon serupa berkas, Anda dapat memulai perekaman paket data.

**Langkah 3: Penyaringan Paket Data**
Tahap ini melibatkan penyaringan paket data yang relevan:
- Di bagian atas jendela Wireshark, Anda akan menemukan kotak teks di mana Anda dapat memasukkan kriteria penyaringan paket data.
- Jika Anda ingin fokus pada protokol HTTP, masukkan filter "http" untuk menampilkan hanya paket-paket data terkait HTTP.
- Untuk protokol Telnet, gunakan filter "telnet" untuk menyaring paket-paket yang berkaitan dengan Telnet.
- Bagi protokol DNS, gunakan filter "dns" untuk hanya menampilkan paket-paket terkait DNS.

**Langkah 4: Analisis Rinci Paket**
Setelah perekaman dimulai dan filter telah diaplikasikan, daftar paket data yang melintasi antarmuka jaringan akan ditampilkan:
- Anda dapat mengklik setiap paket data untuk melihat rincian lebih lanjut di bagian bawah jendela.
- Informasi seperti header protokol, muatan data (payload), alamat sumber dan tujuan, serta informasi TCP dapat ditemukan dalam setiap paket data.

**Langkah 5: Analisis Mendalam pada Protokol**
Untuk pemahaman lebih mendalam, fokuskan pada paket-paket data yang terkait dengan protokol tertentu (HTTP, Telnet, DNS):
- Untuk analisis lebih rinci protokol HTTP, klik kanan pada paket data, pilih "Follow," lalu pilih "HTTP Stream." Ini akan membuka tampilan yang menunjukkan interaksi permintaan dan tanggapan antara klien dan server.
- Wireshark membantu Anda mengurai informasi protokol dengan lebih terstruktur.

**Langkah 6: Pemfilteran Lanjutan**
Wireshark memiliki kemampuan penyaringan lanjutan:
- Anda bisa merujuk pada dokumentasi Wireshark atau sumber daya online untuk memahami opsi penyaringan yang lebih kompleks.
