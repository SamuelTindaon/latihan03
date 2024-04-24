# TugasPraktikum1
# Tugas Praktikum { Pertemuan ke 6 } <img src=https://qph.fs.quoracdn.net/main-qimg-648763cc041459725b62108f4fdf5b91 width="110px" >
|*Nama|NIM|Kelas|Matkul*|
|----|---|-----|------|
|Samuel Damatta Tindaon|312310462|TI.23.A5|Basis Data|

# Soal Latihan Praktikum
## 1. Tulis semua perintah-perintah SQL percobaan di atas beserta outputnya!

*1. Buat sebuah database dengan nama latihan03*

Untuk membuat database gunakan perintah sebagai berikut :

CREATE DATABASE [nama_database]

CREATE DATABASE latihan03;

lalu, setelah kita membuat database. kita masuk kedalam database tersebut dengan perintah sebagai berikut :

USE latihan03;

![Screenshot 2024-04-24 133838](https://github.com/SamuelTindaon/latihan03/assets/147571483/544e591d-e47f-4e35-b265-5dea81c33e4c)


*2. Buat sebuah tabel dengan nama biodata (nama, alamat) didalam database latihan03!*

Untuk membuat Tabel gunakan perintah sebagai berikut :

`CREATE TABLE nama_tabel (
    nama_field1 tipe _data(ukuran), nama_field2 tipe_data(ukuran), ..., nama_fieldn tipe_data(ukuran)
    );`

`CREATE TABLE biodata (
    nama varchar (100),
    alamat text
    );`

![SS 2](https://github.com/SamuelTindaon/latihan03/assets/147571483/76b091a7-9674-44a3-bb62-d5a3e5563592)


*3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom terakhir!*

Contoh :

ALTER TABLE biodata ADD COLUMN keterangan VARCHAR (15);

![Screenshot 2024-04-24 132709](https://github.com/SamuelTindaon/latihan03/assets/147571483/c3f67dfe-db05-42f9-b263-ecccd93fdb58)


*4.Tambahkan kolom id(int 11) di awal (sebagai kolom pertama)!*

Untuk menambahkan kolom pertama yaitu dengan perintah sebagai berikut :

`ALTER TABLE biodata ADD COLUMN id int FIRST; `

![Screenshot 2024-04-24 132810](https://github.com/SamuelTindaon/latihan03/assets/147571483/eb7eb8d9-c28f-4611-8250-1c5407de4efb)


*5. Sisipkan sebuah kolom dengan nama phone (varchar 15) setelah kolom alamat!*

Untuk menambahkan kolom setelah kolom lain yaitu dengan perintah AFTER

![SS 5](https://github.com/SamuelTindaon/latihan03/assets/147571483/d6773086-9d02-4055-946d-28f3f91b9644)


*6. Ubah tipe data kolom id menjadi char(11)!*

Untuk mengubah type data yaitu dengan perintah sebagai berikut :

ALTER TABLE [nama_tabel] MODIFY nama_field tipe_data_baru(ukuran);

![Screenshot 2024-04-24 132943](https://github.com/SamuelTindaon/latihan03/assets/147571483/bb943be0-a420-48de-9458-bd2535241e5c)


*7. Ubah nama kolom phone menjadi hp (char 20)!*

Untuk mengubah kolom yaitu dengan perintah sebgai berikut :

ALTER TABLE [nama_tabel] CHANGE nama_field_lama nama_field_baru tipe_data(ukuran);

![SS 7](https://github.com/SamuelTindaon/latihan03/assets/147571483/2329a258-aebb-495a-b73e-6da33485fb98)


*8. Tambahkan kolom email setelah kolom hp*

![SS 8](https://github.com/SamuelTindaon/latihan03/assets/147571483/20bb8c84-c68a-4208-b0e4-dbd3048c2487)


*9. Hapus kolom keterangan dari tabel!*

Untuk menghapus kolom dari tabel yaitu dengan perintah sebagai berikut :

ALTER TABLE [nama_tabel] DROP nama_field;

![Screenshot 2024-04-24 134511](https://github.com/SamuelTindaon/latihan03/assets/147571483/097ac95f-3e00-416d-ab1b-dc65a9d94a77)


*10. Ganti nama tabel menjadi data_mahasiswa!*

Untuk mengganti nama tabel yaitu dengan perintah sebagai berikut :

ALTER TABLE [nama_tabel] RENAME [nama_tabel_baru];

![Screenshot 2024-04-24 134844](https://github.com/SamuelTindaon/latihan03/assets/147571483/63179c80-a1d3-4814-8600-009777d4b77a)


*11. Ganti nama field id menjadi nim!*

![Screenshot 2024-04-24 134610](https://github.com/SamuelTindaon/latihan03/assets/147571483/55d73410-8eb4-494a-af9a-0e2864a56538)


*12. Jadikan nim sebagai PRIMARY KEY!*

Untuk menambahkan index atau key, gunakan perintah sebagai berikut :

tipe index :

- PRIMARY KEY
- UNIQUE KEY
- FULLTEXT

ALTER TABLE [nama_tabel] ADD [INDEX|PRIMARY KEY] (nama_field);

![Screenshot 2024-04-24 134705](https://github.com/SamuelTindaon/latihan03/assets/147571483/1b68f89d-a7f8-44ea-891a-e5ff5ba91366)


*13. Jadikan kolom email sebagai UNIQUE KEY!*

Perintah nya sama seperti diatas, hanya saja diganti menjadi UNIQUE KEY

![Screenshot 2024-04-24 134844](https://github.com/SamuelTindaon/latihan03/assets/147571483/8147f3a1-5f20-448f-99de-1dcf49223586)



## 2. Apa Maksud Dari INT(11) ?

- INT(11) Adalah Nama Tipe Datanya Yaitu Integer dan Memiliki Panjang 11 Karakter.

## 3. Ketika Kita Melihat Struktur Tabel Dengan Perintah DESC , Ada Kolom Null yang Berisi Yes dan No. Apa Maksudnya ?

- Yaitu Untuk Menjelaskan Bahwa Pada Record yg NO Harus diisi , Sedangkan YES Boleh Tidak diisi.


### Sekian Tugas Praktikum Saya di Pertemuan kali ini, Jika Masih Ada Yang Salah Saya Mohon Maaf.
### TERIMA KASIH :)
