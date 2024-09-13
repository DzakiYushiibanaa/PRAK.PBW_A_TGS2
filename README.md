# Buku Tamu Online

Proyek ini adalah aplikasi web sederhana yang memungkinkan pengguna untuk mengisi buku tamu secara online. Pengguna dapat memasukkan nama, email, komentar, dan memilih gender. Data yang dimasukkan akan disimpan dalam file teks (`bukutamu.txt`) dan dapat dilihat dalam bentuk tabel di halaman "Lihat Buku Tamu".

## Fitur
- **Form Buku Tamu**: Pengguna dapat mengisi nama, email, komentar, dan memilih gender.
- **Penyimpanan Data**: Data buku tamu disimpan secara aman dalam file teks menggunakan PHP.
- **Cookie**: Nama pengunjung terakhir disimpan di cookie selama 1 hari.
- **Tampilan Daftar Tamu**: Data tamu ditampilkan dalam bentuk tabel yang dapat diakses melalui halaman "Lihat Buku Tamu".
- **Keamanan**: Input data dibersihkan menggunakan metode `htmlspecialchars` untuk mencegah serangan XSS.

