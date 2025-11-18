# PROJECT-2-LATIHAN-
# LANGKAH 1 MEMBUAT DIREKTORI UNTUK 3 DEPARTEMEN MARKETING,ENGINEERING,HR
Definisi gambar
https://drive.google.com/file/d/1-GOjiAS4DYMLz0Z_A-0N-SIYlr5REPFi/view?usp=drivesdk
```
mkdir Marketing Enginering HR
```
# MEMBUAT SUBFOLDER DI MASING-MASING DIREKTORI
Definisi gambar
https://drive.google.com/file/d/1l9KBruILwD0dX2oPpzSulVFSHyI9n_1g/view?usp=drivesdk.
# ISI LANGKAH-LANGKAH DAN PERINTAH
```
‎virtualbos:-/project_1$ cd Marketing
‎virtualbox:~/project_1/Marketing$ mkdir Documents Archives
‎virtualbox:~/project_1/Marketing$ ls
‎Archives Documents
‎virtualbox:~/project_1/Marketing$ cd Documents
‎virtualbox:~/project_1/Marketing/Documents$ mkdir engineering_report.txt
‎virtualbox:~/project_1/Marketing/Documents$ ls
‎engineering_report.txt
‎virtualbox:~/project_1/Marketing/Documents$ cd ..
‎virtualbox:~/project_1/Marketing$ cd Archives
‎virtualbox:~/project_1/Marketing/Archives$ mkdir Laporan_Marketing.pdf
‎virtualbox:~/project_1/Marketing/Archives$ ls
‎Laporan_Marketing.pdf
‎virtualbox:~/project_1/Marketing/Archives$ cd ..
‎virtualbox:~/project_1/Marketing$ cd ..
‎virtualbox:~/project_1$ cd Engineering
‎virtualbox:~/project_1/Engineering$ cd Documents
‎virtualbox:~/project_1/Engineering$ mkdir Documents
‎virtualbox:~/project_1/Engineering$ cd Documents
‎virtualbox:~/project_1/Engineering/Documents$ mkdir Doc_engineering.pdf
‎virtualbox:~/project_1/Engineering/Documents$ cd ..
‎virtualbox:~/project_1/Engineering$ mkdir Archives
‎virtualbox:~/project_1/Engineering$ cd Archives
‎virtualbox:~/project_1/Engineering/Archives$ mkdir Doc_Marketing.txt
‎virtualbox:~/project_1/Engineering/Archives$ cd ..
‎virtualbox:~/project_1/Engineering$ cd ..
‎virtualbox:~/project_1$ cd HR
‎virtualbox:~/project_1/HR$ mkdir Documents
‎virtualbox:~/project_1/HR$ cd Documents
‎virtualbox:~/project_1/HR/Documents$ mkdir HR_pict.jpg
‎virtualbox:~/project_1/HR/Documents$ cd ..
‎virtualbox:~/project_1/HR$ mkdir Archives
‎virtualbox:~/project_1/HR$ cd Archives
‎virtualbox:~/project_1/HR/Archives$ mkdir file_HR.pdf
‎virtualbox:~/project_1/HR/Archives$ cd ..
‎virtualbox:~/project_1/HR$ cd ..
```
*`Penjelasan`.
* `mkdir` → membuat folder baru.
* `cd` → masuk ke folder.
* `cd ..` → keluar ke folder sebelumnga.
# LANGKAH 2 MEMINDAHKAN FILE YANG SALAH TEMPAT KE FIREKTORI YANG BENAR
Definisi gambar
https://drive.google.com/file/d/1jruhOvXfXie--b6SyKoJJKptwZPwjJ24/view?usp=drivesdk
```
mv Marketing/Documents/engineering_report.txt Engeneering/Archives
```
```
mv Engineering/Archives/Doc_Marketinf.txt Marketing/Documents
```
# MEMBUAT BACKUP DI FOLDER ARCHIVES
Definisi gambar
https://drive.google.com/file/d/1EEIXRFoXO_Uduwb6rs9DKZ5j_B_Sen7N/view?usp=drivesdk
```
cp -r Marketing/Dokuments/Doc_Marketing.txt Marketing/Archives
```
```
cp -r Engineering/Documents/Doc_engineering.pdf Engineerinf/Archives
```
```
cp -r HR/Documents/HR_pict.jpg HR/Archives
```
# MENAMPILAN ISI FOLDER
# Marketing,Engineering,HR
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
sudo groupadd HR HR
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










