## Port FTP
**Nama** : Aulia Ilham Nur Alfian </br>
**NRP** : 3122600024 </br>
**Kelas** : 2 D4 IT A </br>
**Mata Kuliah** : Konsep Jaringan </br>
<div align="center">
<img src="assets/Port Networking.PNG">
<p><strong>Gambar:</strong> Port Networking</p>
</div>

Port dalam konteks komputer dan jaringan merupakan mekanisme yang berfungsi untuk mengarahkan lalu lintas data ke aplikasi atau layanan tertentu di dalam suatu perangkat. Pada umumnya, protokol FTP (File Transfer Protocol) menggunakan TCP (Transmission Control Protocol) sebagai protokol transportasinya. Namun, ada beberapa situasi di mana dinyatakan bahwa 1 port FTP dapat menggunakan baik UDP (User Datagram Protocol) maupun TCP.

**1. Penggunaan UDP dalam 1 Port FTP:**
Jarang sekali protokol FTP menggunakan eksklusif UDP pada satu port tertentu. UDP biasanya digunakan pada aplikasi yang mengutamakan latensi rendah, seperti permainan online atau streaming media, di mana kecepatan lebih diutamakan daripada keandalan. Penggunaan UDP dalam protokol FTP mungkin hanya terjadi pada kasus-kasus sangat spesifik dan tidak konvensional. Namun, pendekatan ini membawa risiko terkait integritas data dan potensi hilangnya paket data.

**2. Penggunaan TCP dalam 1 Port FTP:**
Penggunaan TCP dalam protokol FTP jauh lebih umum dan dianggap sebagai pendekatan standar. TCP menyediakan komunikasi yang handal, mencakup deteksi kesalahan, retransmisi paket, serta penjaminan urutan yang benar. Dalam protokol FTP, port kontrol (umumnya port 21) digunakan untuk memulai dan mengelola sesi, sedangkan port data (misalnya, port 20) digunakan untuk mengirimkan file aktual. Keandalan yang diberikan oleh TCP memastikan bahwa file dapat ditransfer dan diterima tanpa kehilangan data dan dalam urutan yang tepat.

**Kesimpulan:**
Walaupun ada kemungkinan bahwa 1 port FTP dapat menggunakan baik UDP maupun TCP, penggunaan UDP dalam konteks protokol FTP sangatlah langka dan biasanya terkait dengan implementasi khusus atau situasi yang tidak umum. Dalam kebanyakan kasus, protokol FTP lebih umum menggunakan TCP sebagai protokol transportasi untuk menjamin keandalan dan integritas transfer file antara klien dan server.