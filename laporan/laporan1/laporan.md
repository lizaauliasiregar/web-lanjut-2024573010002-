# Laporan Modul 1: Perkenalan Laravel
**Mata Kuliah:** Workshop Web Lanjut   
**Nama:** [Liza Aulia Siregar]
**NIM:** [2024573010002]  
**Kelas:** [TI.2C]  

---

## Abstrak 
Praktikum ini membahas implementasi framework Laravel untuk membangun aplikasi web modern yang aman. Pada praktikum ini kita diharuskan untuk instalasi, konfigurasi, dan penerapan dari fitur-fitur umum seperti Routing, manajemen basis data, dan autentikasi (authentication). Tujuan utama dari praktikum ini yaitu untuk lebih memahami penggunaan Laravel dalam membangun web yang efesien dan terstruktur.

---

## 1. Pendahuluan
Laravel adalah framework web PHP yang populer, bersifat open-source, dan dirancang untuk membangun aplikasi web modern yang skalabel dan aman.

Laravel merupakan framework high-level yang bersifat opinionated (punya aturan dan konvensi tertentu). Framework ini pertama kali diperkenalkan oleh Taylor Otwell pada tahun 2011

Karakteristik utama Laravel:
- Model-View-Controller (MVC) merupakan pola desain perangkat lunak yang umum digunakan untuk mengimplementasikan antarmuka pengguna, data, dan logika kontrol. tujuannya unuk mempermudah dan membbuat proses pengembangan menjadi lebih aman dan efesien
- Eloquent ORM adalah fitur dari Laravel yang memungkinkan developer untuk dapat menggunakan dan memanipulasi data yang ada di dalam database dengan PHP objects dan model terkait. 



## 2. Komponen Utama Laravel (ringkas)
- Blade (templating), adalah emplate engine bawaan Laravel yang memungkinkan pembuatan tampilan dinamis dengan sintaks sederhana dan mendukung pewarisan layout.
- Eloquent (ORM), adalah Object Relational Mapping Laravel yang mempermudah interaksi dengan database menggunakan model berbasis objek, tanpa perlu query SQL manual.
- Routing mengatur alur dan URL aplikasi, menentukan halaman atau aksi mana yang akan dijalankan berdasarkan permintaan pengguna.
- Controllers, berfungsi sebagai penghubung antara model dan view, menampung logika aplikasi serta mengatur data yang ditampilkan ke pengguna.
- Migrations & Seeders, digunakan untuk mengatur struktur database secara version control, sedangkan Seeder untuk mengisi database dengan data awal atau dummy
- Artisan CLI, adalah command line tool Laravel yang menyediakan berbagai perintah untuk mempercepat pembuatan file, menjalankan migration, atau menjalankan server.
- Testing (PHPUnit), Laravel mendukung pengujian otomatis menggunakan PHPUnit untuk memastikan fungsi aplikasi berjalan sesuai harapan dan bebas dari error.



## 3. Berikan penjelasan untuk setiap folder dan files yang ada didalam struktur sebuah project laravel.

- Folder web-lanjut merupakan folder utama untuk membuat proyek.
- File .gitignore untuk menentukan berkas dan direktori agar tidak bisa dilacak oleh system control, seperti versu git, file log, atau berkas konfigurasi local, sehingga repositori tetap bersih dan focus pada inti proyek
- File README.md adalah berkas dokumentasi proyek yang ditulis dalam format Markdown
- Folder laporan untuk isi laporan praktikum project laravel 
- Folder laporan1 untuk memasukkan laporan praktikum berbentuk pdf.
- file laporan.md dan folder gambar untuk menampung gambar yang dipakai didalam laporan.
- Folder projects untuk menyimpan proyek yang berhubungan dengan laporan laravel ini.


## 4. Diagram MVC dan Cara kerjanya

Alur Kerja MVC dalam sebuah aplikasi 
1. Pengguna berinteraksi dengan aplikasi melalui View. Contohnya pengguna dapat melakukan Login atau memasukkan data kedalam formulir.
2. Controller menerima input dari pengguna dan memprosesnya. Controller ini bertugas menentukan apakah input tersebut perlu dikirim ke Model untuk pengolahan selanjutnya atau langsung diteruskan ke View.
3. mengelola data dan mengembalikan hasil ke Controller. Jika input pengguna membutuhkan data dari database (misalnya login), Model akan mengambil atau menyimpan informasi tersebut.
4. Controller mengirimkan data dari Model ke View. Setelah mendapatkan data dari Model, Controller mengatur bagaimana data ini ditampilkan di layar pengguna.
5. View memperbarui tampilan sesuai data yang diberikan oleh Controller. Misal, setelah Login berhasil, pengguna akan diarahkan ke halaman dasbord mereka. 

<img src=".../laporan1/gambar/AlurMVC.jpg" alt="Gambar Cara Kerja MVC>



---

## 5. Kelebihan & Kekurangan (refleksi singkat)
Kelebihan Laravel menurut saya mudah untuk dipelajari bagi pemula.
Menurut saya Laravel memiliki banyak konsep seperti MVC, ORM, atau Composer. Karena bagi saya yang masih pemula yang baru mengenal php terasa membingungkan diawal. Hal itu juga menjadi tantangan bagi saya. 


---

## 7. Referensi

1. Modul Pengenakan Laravel-https://hackmd.io/@mohdrzu/By0Wc1Dule
Gunakan format sederhana (judul — URL).
2. Markdown Memasukkan Gambar-https://www.ulas.in/komputer/markdown-memasukkan-gambar/
3. Cara kerja MVC-https://ids.ac.id/mvc-model-view-controller/
4. Belajar artisan CLI-https://buildwithangga.com/tips/belajar-laravel-11-artisan-cli-definisi-contoh-kodingan-cara-penggunaan-tepat#:~:text=Artisan%20adalah%20CLI%20khusus%20yang,developer%20dalam%20berbagai%20tugas%20pengembangan
5. Fungsi ORM-https://www.sekawanmedia.co.id/blog/eloquent-orm/

---
