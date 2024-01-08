<h1>Final Project: Ujian Akhir Semester</h1>

```bash
Kelompok 2      : - Wisnu Ikhwansyah Saputra  (312110305)
                  - Roswanda Nuraini          (312110328)
                  - Galva Al Godzali       (312110301)
                  - Rini Ariza
                  - Muhamad Reza Maulana
Judul Project   : Sistem Lowongan Kerja
Kelas           : TI. 22. A3
Mata Kuliah     : Object Oriented Programming
Dosen Pengampu  : Agung Nugroho,S.Kom.,M.Kom
```
# COMOT (Cowo Motor)

COMOT (Cowo Motor) adalah aplikasi web yang dibangun dengan Django, memungkinkan pengguna untuk menyewa motor.

## Fitur 

- **Otentikasi User:** User dapat membuat akun, masuk, dan mengelola profil mereka.
- **Katalog Motor:** Jelajahi dan cari berbagai macam motor yang tersedia untuk disewa.
- **Sistem Penyewaan:** Pengguna dapat menyewa motor dengan durasi tertentu.
- **Kontak:** User dapat menghubungi kontak yang tersedia jika mengalami kendala.


## Teknologi yang Digunakan

- **Django:** Kerangka web yang digunakan untuk membangun aplikasi.
    - File `settings.py` yang telah disediakan berisi konfigurasi dasar untuk proyek Django.
    - File `__init__.py`  adalah file khusus dalam direktori atau package Python yang menandakan bahwa direktori tersebut adalah sebuah package.
    - File `manage.py` adalah skrip Python yang digunakan untuk menjalankan berbagai tugas administratif dan perintah manajemen dalam proyek Django


- **Database:** ( database yang digunakan SQLite).


## Installation

1. Clone repository:

   ```bash
  
   ```

2. Jalankan development server:

   ```bash
   python manage.py runserver
   ```

5. Akses aplikasi di ` http://127.0.0.1:8000/` di web browser anda.

==================================================================

# OnlineQuiz

## Daftar Isi <br>

| No  | Description             | Link                                                    |
| --- | ----------------------- | ------------------------------------------------------- |
| 1   | Introduction            | [Click Here](#introduction)                             |
| 2   | Fitur-Fitur Website     | [Click Here](#website-ini-memiliki-fitur-fitur-berikut) |
| 3   | Which Is Use            | [Click Here](#which-is-used)                            |
| 4   | How To Run This Project | [Click Here](#how-to-run-this-project)                  |

### Introduction
**Website OnlineQuiz adalah sebuah sistem untuk menguji pengetahuan dan keterampilan murid melalui serangkaian ujian online yang telah diberikan oleh guru dan di kelola oleh admin.** Dengan beragam topik, tingkat kesulitan dan juga berbagai poin disetiap pertanyaan. Website OnlineQuiz dibuat untuk memberikan pengalaman belajar yang menyenangkan dan interaktif, dengan metode online yang pastinya website OnlineQuiz memiliki fitur-fitur yang canggih yang dapat mempermudah dalam pemakaian dan pastinya berisi pertanyaan-pertanyaan berkualitas. 


Website OnlineQuiz yang dibuat dengan **Python**, **Django**, dan **sqlite** memiliki beberapa kelebihan, yaitu :
> Tampilan website yang mudah dipahami

> Fleksibilitas belajar

> Lebih cepat dan efisien

> Interaktif dan menyenangkan


Website ini menggunakan database **db.sqlite3** yaitu sebuah file database yang umumnya digunakan oleh aplikasi berbasis Python yang menggunakan SQLite sebagai sistem manajemen basis data (DBMS). SQLite adalah library C yang memberikan fungsi lengkap sebuah basis data SQL tanpa memerlukan server terpisah dan pengaturan konfigurasi yang kompleks. SQLite adalah DBMS self-contained yang dapat digunakan dengan mudah dan ringan. Dalam konteks Django sebuah framework web Python, **db.sqlite3** biasanya muncul sebagai file database default ketika kita membuat proyek baru. Django menggunakan SQLite sebagai database default karena kemudahan konfigurasi dan kecocokan dengan banyak proyek kecil hingga menengah. 


### Website ini memiliki fitur-fitur berikut:

> **Admin**

- Admin dapat mendaftarkan akun mereka sendiri tanpa persetujuan dari pihak lain. Setelah akun berhasil dibuat, admin dapat melakukan login untuk mengakses sistem.

- Admin dapat mengelola jumlah siswa, jumlah guru, jumlah course dan jumlah pertanyaan.

- Admin dapat memperbarui, melihat, menyetujui, menolak, menghapus dan mengelola gaji guru (menyetujui guru yang bergabung atau melamar pekerjaan pada course mereka).

- Admin dapat melihat dan mengelola nilai/point siswa.

- Admin dapat membuat, melihat, dan menghapus nama course, total pertanyaan dan total nilai.

 - Admin dapat  menambahkan, melihat dan menghapus pertanyaan-pertanyaan pada course yang telah di tambahkan sebelumnya.


> **Teacher**

- Guru harus membuat akun terlebih dahulu sebelum dapat bekerja di course ini. Pendaftaran akun tersebut akan disetujui atau ditolak oleh admin. Setelah disetujui, guru dapat melakukan login untuk mengakses sistem.

- Guru hanya dapat melihat total siswa yang telah di tambahkan dan di kelola oleh admin.

- Guru dapat melihat jumlah siswa, jumlah ujian/course dan jumlah pertanyaan.

- Guru dapat membuat, melihat dan menghapus nama ujian/course, total pertanyaan dan total nilai.

- Guru dapat  menambahkan, melihat dan menghapus pertanyaan-pertanyaan pada course yang telah di tambahkan sebelumnya.


> **Student**

- Siswa harus membuat akun terlebih dahulu sebelum bergabung dan masuk di course ini. Lalu setelah itu siswa dapat login untuk mengakses sistem.

- Siswa dapat melihat total ujian yang tersedia dan total pertanyaan yang telah dibuat dan dikelola oleh guru dan admin.

- Siswa dapat mengikuti/mengerjakan ujian pada course ini sesuai perintah dari guru atau bisa sesuai keinginan siswa ingin mengikuti ujian yang mana.

- Siswa dapat melihat tanda atau point pada ujian yang telah dikerjakan.


### Which Is Used

1. **Django**
   
   Django adalah sebuah framework web berbasis Python yang dirancang untuk mempermudah pengembangan aplikasi web. Django menyediakan sejumlah alat dan fitur bawaan untuk mempercepat pembuatan aplikasi web dengan
   menyederhanakan tugas-tugas umum.

   Dalam sistem OnlineQuiz, Django digunakan untuk membuat struktur aplikasi web, membuat model database dan mempermudah penggunaan aplikasi web.


2. **Python**

    Python adalah bahasa pemrograman tingkat tinggi yang sangat populer, dirancang untuk menyediakan sintaksis yang jelas dan mudah dibaca. Dalam sistem OnlineQuiz, Python digunakan sebagai bahasa pemrograman utama untuk membuat aplikasi web.


3. **SQLite**
   
   
   SQLite adalah sistem manajemen basis data (DBMS) yang bersifat serverless, self-contained, dan bersifat transaksional. Ini berarti SQLite tidak memerlukan server terpisah untuk mengelola basis data, dan seluruh basis
   data disimpan dalam satu file tunggal yang dapat diakses langsung dari program aplikasi.

   Dalam sistem OnlineQuiz, SQLite digunakan sebagai database untuk menyimpan data pengguna, jumlah course/exam, jumlah pertanyaaan, dan data nilai siswa.


4. **VSCode**


   Untuk mengedit code, kami menggunakan Visual Studio Code (VSCode). Visual Studio Code (VSCode) adalah editor kode sumber sumber terbuka dan ringan yang dikembangkan oleh Microsoft. Visual Studio Code sering digunakan oleh para pengembang perangkat lunak untuk proyek-proyek pengembangan perangkat lunak, pemrograman web, dan pengembangan aplikasi lintas platform. Kelebihan dalam ekstensibilitas dan ekosistem ekstensi yang kaya menjadikannya pilihan populer di komunitas pengembangan perangkat lunak.




### How To Run This Project?

1. **Instalasi Python**

- Unduh Python dari situs resminya : https://www.python.org/downloads/

- Saat instalasi, pastikan untuk memberi centang pada kotak "Add Python to PATH". Ini akan memudahkan kita dalam menjalankan Python melalui perintah di terminal.

3. **Mengunduh dan menyiapkan project**
   ```
   https://github.com/syifaaurellia/OnlineQuiz.git
   ```

- Silahkan clone repository di atas atau download ZIP, kemudian extract file ZIP tersebut ke sebuah folder.

4. **Install dependencies**

- Buka terminal atau command prompt anda. (Jangan lupa untuk masuk ke folder yang kita extract sebelumnya)

- Ketik perintah berikut untuk menginstall dependencies :

```
pip install -r requirements.txt
```
   
5. **Jalankan migrasi database**

```
python manage.py migrate
```

6. **Membuat superuser**

```
python manage.py createsuperuser
```

- Pada bagian ini kita akan diarahkan untuk membuat username, mengisi akun email dan membuat password untuk akun kita di web nanti ketika sudah berhasil di run.

7. **Jalankan server**

```
python manage.py runserver
```

8. **Mengakses project di browser**

- Buka browser di pc anda (Chrome, Firefox, Edge dan lain-lain)

- Masukkan alamat berikut pada address bar browser :

  http://127.0.0.1:8000/

- Setelah itu web tampilan project django sudah berjalan dan tampil pada browser anda.


## Semoga Bermanfaat, Terima Kasih 












