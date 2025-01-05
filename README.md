# The Onion Router (ToR) Tunnel

> **Peringatan:** :red_circle: Alat ini dibuat khusus untuk keperluan pendidikan dan penelitian. Penulis tidak bertanggung jawab atas segala bentuk penyalahgunaan atau kerusakan yang mungkin timbul dari penggunaan program ini. Harap gunakan dengan bijak dan hanya di lingkungan di mana Anda memiliki izin eksplisit.

The Onion Router (TOR) Tunnel adalah sebuah jaringan anonim yang memungkinkan penggunanya untuk menjelajah internet secara anonim dengan menyembunyikan alamat IP mereka dan mengenkripsi lalu lintas internet yang mereka kirimkan. TOR bekerja dengan cara mengalihkan data melalui beberapa lapisan enkripsi (seperti kulit bawang, hence "onion") yang melewati berbagai node (komputer yang terhubung ke jaringan TOR) sebelum mencapai tujuan akhir.

Berikut adalah penjelasan lebih rinci mengenai cara kerja TOR:

1. Lapisan Enkripsi ("Onion"): Setiap kali Anda mengirim data melalui TOR, data tersebut dibungkus dalam beberapa lapisan enkripsi, seperti lapisan-lapisan pada bawang. Setiap lapisan ini hanya dapat dibuka oleh node yang relevan dalam rute TOR. Lapisan enkripsi pertama dibuka oleh node pertama, lapisan kedua oleh node kedua, dan seterusnya. Proses ini membuat pengamat di luar jaringan TOR kesulitan untuk melacak asal atau tujuan data.

2. Jalur Tiga Node: Data yang dikirim melalui TOR biasanya melewati tiga node (komputer dalam jaringan TOR). Proses ini adalah:

- Node pertama (Guard node): Menerima data dan membuka lapisan pertama enkripsi, mengetahui asal data tetapi tidak tahu tujuannya.
- Node kedua (Relay node): Menerima data yang sudah didekripsi sebagian dan meneruskannya ke node berikutnya. Node ini hanya mengetahui asal dan tujuan dari node pertama dan node ketiga.
- Node ketiga (Exit node): Membuka lapisan terakhir dari enkripsi dan mengirim data ke tujuannya, seperti situs web atau server. Exit node ini dapat melihat data yang dikirim ke tujuan, tetapi tidak tahu siapa yang mengirimnya.

3. Anonimitas dan Privasi: Karena data melintasi beberapa node dan dilindungi oleh enkripsi, maka identitas pengirimnya (misalnya, alamat IP asli) dan data yang dikirim akan terlindungi. Hal ini membuat TOR sangat berguna bagi mereka yang ingin menjaga privasi saat menjelajah web atau mengakses informasi sensitif.

4. Penggunaan: TOR sering digunakan oleh individu yang ingin menjaga privasi mereka saat online, aktivis, jurnalis, dan juga orang-orang di negara-negara dengan sensor internet yang ketat. Namun, TOR juga terkadang digunakan untuk aktivitas ilegal, karena kemampuannya menyembunyikan identitas penggunanya.

#
~ (v1.0.0.1) Minggu 5 Januari 2025 - First Release The Onion Router (ToR) Tunnel v1.0.0.1 by Geoclans

Note: Aplikasi sudah di Test di Windows 10 dan Windows 11 (x32/x64)

#
<b>[ Tutorial Singkat Penggunaan Aplikasi The Onion Router (ToR) Tunnel ]</b>

1. Download ToR Tunnel via https://codeload.github.com/MichaelJorky/The-Onion-Router-TOR-Tunnel/zip/refs/heads/main
2. Lalu jalankan ToR Tunnel.exe di aplikasi ada ip proxy yang sudah include 161.123.152.115:6360 itu hanya berfungsi jika "Use Proxy" di ceklist dan itu hanya proxy demo saja, proxy tersebut saya dapatkan secara gratis di https://www.webshare.io/features/free-proxy silahkan daftar terlebih dahulu dan tidak perlu saya jelaskan cara daftarnya tetapi pastikan type proxy yang teman-teman gunakan adalah type authorization ip atau istilahnya proxy direct yang dikunci hanya untuk 1 ip address yang terdaftar saja, tetapi jika teman teman tidak menceklis "Use Proxy" abaikan saja. untuk "Use proxy" tersebut tidak harus selalu menggunakan type server proxy karena itu bisa kita atur menggunakan secara lokal, misalkan output dari aplikasi Psiphon dll.
3. Listen Port: 127.0.0.1:9050 itu adalah output koneksi dari Tor Tunnel yang secara default sudah diatur dan diarahkan ke aplikasi Proxifer, hanya saja jika teman-teman ingin mengatur outputnya secara manual tinggal atur saja listen portnya lalu arahkan misalkan ke aplikasi Psiphon dll, dan pastikan tidak menggunakan port sama aktif secara bersamaan pada systemnya agar tidak terjadi konflik port.
4. Remote Port: digunakan untuk menggunakan port berapa untuk terhubung ke server jaringan ToR, Secara default remote port terbaik di indonesia dan bisa digunakan di semua provider adalah port 80 dan 443
5. Status: untuk menampilkan status apakah aplikasi berhasil terhubung ke jaringan Tor atau tidak.
