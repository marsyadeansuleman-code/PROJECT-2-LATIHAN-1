# PROJECT-2-LATIHAN-
# LANGKAH 1 Membuat direktori untuk 3 departemen(Marketing Engineering HR)
Definisi gambar
https://drive.google.com/file/d/1-GOjiAS4DYMLz0Z_A-0N-SIYlr5REPFi/view?usp=drivesdk
```
mkdir Marketing Enginering HR
```
# LANGKAH 2 Membuat subforder pada direktori dan archiven di masing-masing
Definisi gambar
https://drive.google.com/file/d/1l9KBruILwD0dX2oPpzSulVFSHyI9n_1g/view?usp=drivesdk
```
virtualbox:-/project_1$ cd Marketing
virtualbox:~/project_1/Marketing$ mkdir Documents Archives
virtualbox:~/project_1/Marketing$ ls
Archives Documents
virtualbox:~/project_1/Marketing$ cd Documents
virtualbox:~/project_1/Marketing/Documents$ mkdir engineering_report.txt
virtualbox:~/project_1/Marketing/Documents$ ls
engineering_report.txt
virtualbox:~/project_1/Marketing/Documents$ cd ..
virtualbox:~/project_1/Marketing$ cd Archives
virtualbox:~/project_1/Marketing/Archives$ mkdir Laporan_Marketing.pdf
virtualbox:~/project_1/Marketing/Archives$ ls
Laporan_Marketing.pdf
virtualbox:~/project_1/Marketing/Archives$ cd ..
virtualbox:~/project_1/Marketing$ cd ..
virtualbox:~/project_1$ cd Engineering
virtualbox:~/project_1/Engineering$ cd Documents
virtualbox:~/project_1/Engineering$ mkdir Documents
virtualbox:~/project_1/Engineering$ cd Documents
virtualbox:~/project_1/Engineering/Documents$ mkdir Doc_engineering.pdf
virtualbox:~/project_1/Engineering/Documents$ cd ..
virtualbox:~/project_1/Engineering$ mkdir Archives
virtualbox:~/project_1/Engineering$ cd Archives
virtualbox:~/project_1/Engineering/Archives$ mkdir Doc_Marketing.txt
virtualbox:~/project_1/Engineering/Archives$ cd ..
virtualbox:~/project_1/Engineering$ cd ..
virtualbox:~/project_1$ cd HR
virtualbox:~/project_1/HR$ mkdir Documents
virtualbox:~/project_1/HR$ cd Documents
virtualbox:~/project_1/HR/Documents$ mkdir HR_pict.jpg
virtualbox:~/project_1/HR/Documents$ cd ..
virtualbox:~/project_1/HR$ mkdir Archives
virtualbox:~/project_1/HR$ cd Archives
virtualbox:~/project_1/HR/Archives$ mkdir file_HR.pdf
virtualbox:~/project_1/HR/Archives$ cd ..
virtualbox:~/project_1/HR$ cd ..
```
# MENAMPILAN ISI folder Marketing Enginering HR
Definisi gambar
https://drive.google.com/file/d/1WF2ZdwjRi52lCC2hXCB_6oKpzps8fiD2/view?usp=drivesdk
```
Tree -P "Marketing Engineering HR
```
# LANGKAH 3 MEMINDAHKAN FILE YANG SALAH TEMPAT KE FIREKTORI YANG BENAR
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
#LANGKAH 4 MENAMPILKAN FILE PDF -7 HARI YANG LALU
Definisi gambar























































