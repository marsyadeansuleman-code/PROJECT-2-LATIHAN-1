# PROJECT-2-LATIHAN-
# LANGKAH 1 
# Membuat Direktori untuk 3 Departemen MARKETING,ENGINEERING,HR
Definisi gambar
https://drive.google.com/file/d/1-GOjiAS4DYMLz0Z_A-0N-SIYlr5REPFi/view?usp=drivesdk
```
mkdir Marketing Enginering HR
```
# MEMBUAT SUBFOLDER DI MASING-MASING DIREKTORI
Definisi gambar
(https://drive.google.com/file/d/12D3Kwj6yivIi9fR0FQ9hxc-0ZTQci57f/view?usp=drivesdk)).
```
Marsyadea@Marsyadea-virtualbox:$ cd Marketing
Marsyadea@Marsyadea-virtualbox:$ mkdir Documents Archives
Marsyadea@Marsyadea-virtualbox:$ cd Documents
Marsyadea@Marsyadea-virtualbox-Documents:$ touch Marketing.docx
Marsyadea@Marsyadea-virtualbox-Documents:$ cd ..
Marsyadea@Marsyadea-virtualbox:$cd Archives
Marsyadea@Marsyadea-virtualbox-Archives:$ touch TargetPasar_file.pdf
Marsyadea@Marsyadea-virtualbox-Archives:$cd ..
```
*`Penjelasan`.
* `mkdir` → membuat folder baru.
* `touch` → membuat file baru.
* `cd` → masuk ke folder.
* `cd ..` → keluar ke folder sebelumnya.
# LANGKAH 2 MEMINDAHKAN FILE YANG SALAH TEMPAT KE FIREKTORI YANG BENAR
Definisi gambar
https://drive.google.com/file/d/1b7uEZZe_NIXLTyM7nIXzGTZlG3CcKxro/view?usp=drivesdk
```
mv images/file11.jpg Marketing/Documents
```
```
mv images/file12.jpg Engineering/Documents
```
```
mv images/file13.jpg HR/Documents
```
# MEMBUAT BACKUP DI FOLDER ARCHIVES
Definisi gambar
[https://drive.google.com/file/d/1EEIXRFoXO_Uduwb6rs9DKZ5j_B_Sen7N/view?usp=drivesdk].
```
cp -r Marketing/Dokuments/Marketing.docx Marketing/Archives
```
```
cp -r Engineering/Documents/Engineering.docx Engineering/Archives
```
```
cp -r HR/Documents/HR.docx HR/Archives
```
# MENAMPILAN ISI FOLDER Marketing,Engineering,HR
Definisi gambar
https://drive.google.com/file/d/1WF2ZdwjRi52lCC2hXCB_6oKpzps8fiD2/view?usp=drivesdk
```
Tree -P "Marketing Engineering HR
```
*`Penjelasan`.
* `mv` → memindahkan file/folder.
* `cp -r` → meng-backup/meng-copy semua folder beserta isinya.
* `Tree -P` → menampilkan struktur folder pohon beserta per misionnya

# LANGKAH 3 SET PERMISION/MEMBATASI HAK AKSES DI SETIAP FOLDER
Definisi Gambar
https://drive.google.com/file/d/1BC9LtfxGCl_V7TYUchoc7J1x_x0TDNvX/view?usp=drivesdk
```
sudo groupadd Marketing
```
```
sudo groupadd Enginering
```
```
sudo groupadd HR 
```
# MENGUBAH KEPEMILIKAN FOLDER DAN SEMUA ISI DI DALAMNYA
Definisi gambar
https://drive.google.com/file/d/1W9PEGwFqHukq0qG3YshYNafKVIrJYlOe/view?usp=drivesdk
```
sudo chgrp -r Marketing Marketing
```
```
sudo chgrp -r Engineering Engineering
```
```
sudo chgrp -r HR HR
```
# MENGATUR IZIN PERMISION FOLDER
Definisi gambar
https://drive.google.com/file/d/1TF075of9P_qNyzetdWYn5CXFvsArx7nz/drivesdk=drivesdk
```
sudo chmod 770 Marketing
```
```
sudo chmod 770 Engineering
```
```
sudo chmod 770 HR
```

*`Penjelasan`.
* `sudo groupadd` → menambahkan grup.
* `sudo chgrp` → mengubah kepemilikan grup.
* `sudo chmod 770` → mengatur izin akses
* `7` → buat owner.
* `7` → buat group.
* `0` → buat outher.

# LATIHAN 4 MENAMPILKAN FILE PDF -7 HATI YANG LALU
definisi gambar
https://drive.google.com/file/d/1nxHlcqRtgMZHNdsiJkPfQDC6eYjan_pB/view?usp=drivesdk
```
find . -type f -iname "*.pdf" -mtime -7
```
*`Penjelasan`.
* `find` → mencari file/folder sesuai nama,tipe,ukuran,dll










