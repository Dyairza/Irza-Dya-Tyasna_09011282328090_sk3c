![Nama: Irza Dya Tyasna](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/1.png)

Perintah `-p` digunakan untuk membuat beberapa sub direktori sekaligus karena folder latihan5 belum ada.

![Perintah -p](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/2.png)
Buat file `dataku` yang berisi nama, NIM, dan alamat di dalam direktori januari. Gunakan perintah `echo` untuk memasukkan informasi ke dalam file. Perintah ini akan membuat file `dataku` dan menuliskan nama, NIM, serta alamat.

![Buat file dataku](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/3.png)
Copy file `dataku` yang ada di direktori januari ke direktori februari dan maret.

![Copy file dataku](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/4.png)
Ubah izin akses file `dataku` pada direktori januari sehingga group dan others dapat melakukan write: Perintah ini memberikan izin `rwx` (read, write, execute) kepada user, `rw` (read, write) kepada group, dan `rw` kepada others.

![Ubah izin akses](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/5.png)
Ubah izin akses file `dataku` pada direktori februari: memberikan izin `rwx` kepada user, `r-x` (read, execute) kepada group, dan `r-x` kepada others.

![Ubah izin akses Februari](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/6.png)
Ubah izin akses file di direktori maret agar semua dapat melakukan write, read, dan execute.

![Ubah izin akses Maret](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/7.png)
Menghapus direktori maret beserta isinya.

![Hapus Direktori Maret](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/8.png)
Mengubah kepemilikan sub direktori februari, menggunakan perintah `chown`.

![Ubah Kepemilikan Direktori Februari](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/9.png)
Coba juga membuat direktori baru bernama `haha` di dalam februari.

![Buat Direktori Haha](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/10.png)
Sekarang, ubah nilai `umask` untuk file `dataku` di sub direktori januari menjadi `027`.

![Ubah Nilai Umask](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/11.png)
Terakhir, buat link dari file `dataku` ke file `dataku.ini` dan `dataku.juga`.

![Buat Link](https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/12.png)
Cek berapa banyak link yang ada dengan: Sudah berhasil membuat hard link dari `dataku` menjadi `dataku.ini` dan `dataku.juga`. Output dari perintah `ls -l` menunjukkan bahwa link count sekarang adalah 3, yang berarti 3 file (2 link dan file asli) menunjuk ke data yang sama.
