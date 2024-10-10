# Script Execution Tool

Script Execution Tool adalah aplikasi web yang memungkinkan pengguna untuk mengirim permintaan HTTP POST secara berkala dengan payload yang dapat disesuaikan. Aplikasi ini dirancang untuk membantu pengguna dalam pengujian API dengan menyediakan antarmuka yang mudah digunakan.

## Fitur

1. **Input URL**
   - **Deskripsi**: Tempat untuk memasukkan URL tujuan untuk mengirim permintaan POST.
   - **Cara Mengisi**: Masukkan URL lengkap, contohnya: `https://api.example.com/endpoint`.

2. **Payload (Array)**
   - **Deskripsi**: Area ini memungkinkan pengguna untuk menentukan payload yang akan dikirim dalam bentuk array. Anda dapat memasukkan jenis data yang berbeda untuk pengujian, seperti nama pengguna, kata sandi, dan lainnya.
   - **Cara Mengisi**: Masukkan item payload yang diinginkan, pisahkan dengan koma. Contoh: `username, password, gmail, number`.

3. **Interval**
   - **Deskripsi**: Interval waktu antara pengiriman permintaan. Diatur dalam milidetik.
   - **Cara Mengisi**: Masukkan angka yang menunjukkan interval. Contoh: `1000` untuk mengirim setiap detik.

4. **Send Request**
   - **Deskripsi**: Tombol untuk memulai pengiriman permintaan berdasarkan URL dan payload yang telah diatur.
   - **Fungsi**: Setelah tombol ini ditekan, aplikasi akan mengirim permintaan POST secara berkala sesuai dengan interval yang ditentukan.

5. **Stop Request**
   - **Deskripsi**: Setelah permintaan dimulai, tombol ini akan berubah menjadi "Stop Request" yang dapat digunakan untuk menghentikan pengiriman permintaan.
   - **Fungsi**: Menghentikan pengiriman permintaan yang sedang berlangsung.

6. **Clear Logs**
   - **Deskripsi**: Tombol untuk menghapus semua log yang ditampilkan di bagian bawah aplikasi.
   - **Fungsi**: Menghapus semua catatan log yang muncul.

7. **Total Request (Success & Failed)**
   - **Deskripsi**: Menampilkan jumlah total permintaan yang berhasil dan gagal setelah pengiriman.
   - **Fungsi**: Memudahkan pengguna untuk melihat hasil pengujian secara keseluruhan.

## Cara Menggunakan

1. **Isi URL**: Masukkan URL tujuan di textarea URL.
2. **Isi Payload**: Masukkan jenis data yang ingin dikirim, pisahkan dengan koma di textarea Payload.
3. **Isi Interval**: Masukkan angka (dalam milidetik) di textarea Interval.
4. **Kirim Permintaan**: Klik tombol **Send Request** untuk memulai pengiriman permintaan.
5. **Hentikan Permintaan**: Klik tombol **Stop Request** untuk menghentikan pengiriman permintaan.
6. **Bersihkan Logs**: Klik tombol **Clear Logs** untuk menghapus log yang ditampilkan.
7. **Lihat Statistik**: Perhatikan statistik Total Request (Success & Failed) untuk hasil pengujian.

## Teknologi yang Digunakan

- **HTML**
  - <img src="https://cdn.jsdelivr.net/npm/devicons@2.2.0/icons/html5/html5-original.svg" alt="HTML Logo" width="30" height="30"> 
  - Untuk struktur dasar halaman web.

- **CSS**
  - <img src="https://cdn.jsdelivr.net/npm/devicons@2.2.0/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS Logo" width="30" height="30"> 
  - Menggunakan [Tailwind CSS](https://tailwindcss.com/) untuk styling.

- **JavaScript**
  - <img src="https://cdn.jsdelivr.net/npm/devicons@2.2.0/icons/javascript/javascript-original.svg" alt="JavaScript Logo" width="30" height="30"> 
  - Untuk logika interaktif dan pengelolaan data.

- **Font Awesome**
  - <img src="https://cdn.jsdelivr.net/npm/devicons@2.2.0/icons/fontawesome/fontawesome-original.svg" alt="Font Awesome Logo" width="30" height="30"> 
  - Untuk ikon.

## Kontribusi

Kontribusi sangat diterima! Silakan lakukan fork repositori ini dan ajukan pull request dengan perubahan yang ingin Anda buat.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).
