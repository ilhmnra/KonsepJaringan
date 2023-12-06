# ADMIN JARINGAN
**Nama** : Aulia Ilham Nur Alfian </br>
**NRP** : 3122600024 </br>
**Kelas** : 2 D4 IT A </br>
**Mata Kuliah** : Konsep Jaringan </br>
`Semua Tugas dalam repo ini merupakan tugas mata kuliah Konsep Jaringan yang dibimbing oleh Bpk. Dr. Ferry Astika Saputra,ST, M.Sc`
# Daftar Isi
di sini saya menjelaskan tentang beberapa protocol header, Analisis jaringan, dan juga tools/aplikasi yang bisa di pakai untuk uji coba jaringan. Yaitu:
###  [Analisis Telnet, DNS, dan HTTP](#main_analyze)
   - [Analisis Telnet](#telnet_analyze)
   - [Analisis DNS](#dns_analyze)
   - [Analisis HTTP](#http_analyze)


Analisis ini membahas tiga komponen utama dalam jaringan: Telnet, DNS, dan HTTP, serta memberikan pemahaman lebih mendalam tentang masing-masing.

### 1. Analisis Telnet
Telnet adalah protokol yang memungkinkan pengguna untuk mengakses dan mengendalikan perangkat jarak jauh melalui jaringan. Protokol ini sering digunakan untuk mengakses shell atau lingkungan baris perintah pada perangkat seperti server atau router yang dapat diakses melalui koneksi jaringan.

Dalam penggunaannya, Telnet memungkinkan pengguna untuk terhubung ke perangkat jarak jauh dan berinteraksi dengan perangkat tersebut seperti berada di depannya. Ini dilakukan dengan cara mengirimkan perintah dari klien (komputer pengguna) ke server (perangkat jarak jauh) melalui koneksi Telnet. Server kemudian memproses perintah tersebut dan mengirimkan hasilnya kembali ke klien.

Namun, perlu diingat bahwa Telnet tidak aman karena data yang dikirimkan antara klien dan server tidak dienkripsi, sehingga informasi sensitif seperti kata sandi dapat dengan mudah diambil oleh pihak yang tidak berwenang yang memantau lalu lintas jaringan.

### 2. Analisis DNS
DNS adalah sistem yang menghubungkan nama domain yang mudah diingat dengan alamat IP numerik yang diperlukan oleh komputer untuk berkomunikasi di internet. Ketika Anda memasukkan nama domain ke dalam peramban web, DNS bekerja di belakang layar untuk menerjemahkan nama domain tersebut menjadi alamat IP yang dapat dimengerti oleh komputer.

Proses ini terjadi dalam beberapa tahap:
1. **Permintaan Resolusi**: Ketika Anda memasukkan nama domain, perangkat Anda mengirim permintaan ke server DNS lokal atau server DNS yang ditetapkan.
2. **Caching**: Jika alamat IP untuk nama domain tersebut telah disimpan dalam cache, respons cepat dapat diberikan tanpa perlu mencari ulang.
3. **Pengulangan**: Jika alamat IP tidak ada dalam cache, server DNS lokal akan meminta server DNS tingkat atas untuk melakukan pencarian.
4. **Resolusi Hierarkis**: Permintaan diteruskan ke server DNS yang semakin tinggi tingkatannya hingga alamat IP ditemukan.
5. **Respons**: Alamat IP dikirim kembali melalui hierarki DNS ke perangkat Anda.

### 3. Analisis HTTP
HTTP adalah protokol yang digunakan untuk mengirimkan data antara klien (seperti peramban web) dan server di World Wide Web. Protokol ini mengatur cara permintaan dan respon data, terutama digunakan dalam konteks halaman web, tetapi juga diterapkan dalam berbagai aplikasi berbasis web.

Ketika Anda memasukkan URL ke dalam peramban, peramban mengirimkan permintaan HTTP ke server yang dituju. Permintaan ini berisi informasi seperti metode (GET, POST, dll.), Header, dan parameter. Server menerima permintaan tersebut, memprosesnya, dan mengirimkan kembali respon HTTP yang juga berisi header dan data yang diminta (seperti halaman web).

HTTP beroperasi di Layer Aplikasi dalam model OSI, yang mengatur komunikasi antara aplikasi di kedua ujung koneksi jaringan. Model ini mencakup tujuh lapisan yang berkontribusi pada fungsi dan interaksi perangkat keras dan lunak dalam jaringan komputer.

**Penting untuk dicatat** bahwa seiring berkembangnya teknologi, banyak aplikasi web telah beralih ke HTTPS (HTTP Secure), yang menggunakan enkripsi SSL/TLS untuk melindungi keamanan dan privasi data yang dikirimkan antara klien dan server.
