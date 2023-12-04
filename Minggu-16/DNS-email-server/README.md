# Cara Kerja dari DNS dan Email Server

    Nama		: Yasir Maarif
    NRP		: 3122600013
    Kelas		: 2 D4 Teknik Informatika
    Mata Kuliah	: Konsep Jaringan
    Dosen Pengampu	: Dr. Ferry Astika Saputra ST, M.Sc

<div align="center">
<img src="./assets/dns.gif">
</div>

##

DNS (Domain Name System) dan Email Server merupakan dua komponen penting dalam infrastruktur internet yang bekerja secara terpisah tetapi saling terkait.

### Cara Kerja DNS (Domain Name System):

1. Permintaan DNS (DNS Request): Ketika pengguna memasukkan nama domain (seperti www.contoh.com) ke dalam peramban web, komputer pengguna akan mengirim permintaan DNS ke server DNS.

2. Server DNS Resolve (Resolusi DNS): Server DNS akan mencari informasi yang sesuai dengan nama domain yang diminta. Jika informasi tersebut ada di dalam cache server DNS, maka informasi tersebut akan dikembalikan ke komputer pengguna. Jika tidak ada dalam cache, server DNS akan menghubungi server lain untuk mencari informasi yang tepat.

3. Pemecahan Nama (Name Resolution): Informasi yang dikembalikan oleh server DNS berisi alamat IP terkait dengan nama domain yang diminta. Ini memungkinkan komputer pengguna untuk mengarahkan permintaan mereka ke alamat IP yang benar.

4. Kesimpulan (Conclusion): Setelah mendapatkan alamat IP dari server DNS, komputer pengguna dapat membuat koneksi langsung ke server yang diinginkan untuk mengakses situs web atau layanan yang dimaksud.

### Cara Kerja Email Server:

1. Pengiriman Email: Ketika seseorang mengirim email, klien email mereka akan mengirimkan email ke server email pengirim.

2. Verifikasi dan Validasi: Server email pengirim akan memeriksa alamat email penerima untuk memastikan validitasnya. Jika valid, email akan dikirim ke server email penerima.

3. Server Penerima: Server email penerima menerima email dan memeriksa alamat tujuan. Jika alamat email valid, email akan disimpan di dalam kotak masuk penerima.

4. Pengambilan Email: Pengguna dapat menggunakan klien email mereka (Outlook, Gmail, dll.) untuk mengambil email dari server email penerima dan membacanya.

5. Respon Email: Saat pengguna menjawab email, klien email mereka akan mengirim balasan ke server email mereka, dan siklus ini berlanjut.

##

Hubungan antara DNS dan Email Server:
DNS memainkan peran penting dalam pengiriman email dengan menyediakan resolusi nama domain ke alamat IP server email penerima. Ketika email dikirim, server email pengirim menggunakan DNS untuk menemukan alamat IP server email penerima yang terkait dengan nama domain tujuan. Proses ini memungkinkan email untuk dikirim ke server email yang tepat dan diarahkan ke kotak masuk yang sesuai. Jadi, DNS adalah komponen penting yang memungkinkan pengiriman email dengan benar dalam infrastruktur internet.
