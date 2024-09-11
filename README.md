Nama	 : Irza Dya Tyasna
Nim	 : 09011282328090
Kelas 	: sk3c

(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/1.png)
Perintah -p digunakan untuk membuat beberapa sub direktori sekaligus karena folder latihan5 belum ada.

(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/2.png)
buat file dataku yang berisi nama, NIM, dan alamat di dalam direktori januari. Gunakan perintah echo untuk memasukkan informasi ke dalam file.Perintah ini akan membuat file dataku dan menuliskan nama, NIM, serta alamat.


(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/3.png)
copy file dataku yang ada di direktori januari ke direktori februari dan maret.

Ubah izin akses file dataku pada direktori januari sehingga group dan others dapat melakukan write:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/4.png)
Perintah ini memberikan izin rwx (read, write, execute) kepada user, rw (read, write) kepada group, dan rw kepada others.

ubah izin akses file dataku pada direktori februari:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/5.png)
memberikan izin rwx kepada user, r-x (read, execute) kepada group, dan r-x kepada others.

ubah izin akses file di direktori maret agar semua dapat melakukan write, read, dan execute:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/6.png)

menghapus direktori maret beserta isinya:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/7.png)

Mengubah kepemilikan sub direktori februari, menggunakan perintah chown:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/8.png)

Coba juga membuat direktori baru bernama haha di dalam februari:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/9.png)

Sekarang, ubah nilai umask untuk file dataku di sub direktori januari menjadi 027:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/10.png)


Terakhir, buat link dari file dataku ke file dataku.ini dan dataku.juga:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/11.png)

Cek berapa banyak link yang ada dengan:
(https://github.com/Dyairza/Irza-Dya-Tyasna_09011282328090_sk3c/blob/main/12.png)

sudah berhasil membuat hard link dari dataku menjadi dataku.ini dan dataku.juga. Output dari perintah ls -l menunjukkan bahwa link count sekarang adalah 3, yang berarti 3 file (2 link dan file asli) menunjuk ke data yang sama.
