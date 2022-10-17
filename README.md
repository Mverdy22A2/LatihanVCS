# tutorial penggunaan git

Git adalah salah satu software penting dalam pengembangan website. Fungsi Git adalah untuk mengatur versi dari source code program Anda dengan memberikan tanda baris dan kode mana yang ditambah atau diganti. Di sini saya akan membahas lengkap soal Git, dari cara install Git, cara login ke Git, hingga cara menggunakan Git.
## Cara Install Git di Windows
Sebelum mempelajari bagaimana cara menggunakan Git, Anda perlu menginstalnya terlebih dahulu di perangkat yang Anda gunakan. Anda bisa memasang Git baik di Windows maupun di Linux. Berikut adalah panduan memasang Git di windows
### Cara install Git di Windows terdiri dari 10 langkah. Berikut adalah penjelasannya:
## 1. Download File Git
Untuk menginstall Git, Anda perlu mengunduh file-nya terlebih dahulu di situs resminya. Download sesuai tipe sistem operasi pada komputer Anda. Apabila tipe sistem operasi komputer Anda 64bit,  pilih Git yang mendukung Windows 64bit. Tujuannya adalah agar tidak terjadi error saat proses instalasi Git.
## 2. Install Git
Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik Next untuk melanjutkan instalasi.
![image](https://user-images.githubusercontent.com/115523263/196168803-8fd28d9b-531b-44aa-a837-a9aa1a06f3f3.png)
## 3. Tentukan Lokasi Instalasi Git
Selanjutnya, pilih lokasi untuk install Git pada komputer Anda. Pada tutorial ini saya menginstall di lokasi C:\Program Files\Git. Setelah menentukan lokasi instalasi Git, klik Next untuk melanjutkan .
![image](https://user-images.githubusercontent.com/115523263/196169114-31d58d0d-13d5-4a59-9789-1a4250ad8cd2.png)
## 4. Pilih Komponen Tambahan
Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik Next untuk melanjutkan instalasi.
![image](https://user-images.githubusercontent.com/115523263/196169241-d4a481c8-87b7-4650-92cf-1cea005f0c40.png)
## 5. Tentukan Nama Aplikasi Git
Sebenarnya Anda bebas mengganti nama aplikasi Git yang akan ditampilkan pada Start Menu. Akan tetapi, demi kemudahan saat mencari aplikasi ini, sebaiknya gunakan nama Git saja. 
![image](https://user-images.githubusercontent.com/115523263/196169434-c73a8e39-cfae-428b-bf24-768c7c1f13d5.png)
## 6. Tentukan File Editor
Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Klik Next apabila Anda sudah menentukan file editor yang akan Anda gunakan.
![image](https://user-images.githubusercontent.com/115523263/196169549-da3a1491-bf86-418e-8a8d-9d4a2bf413a7.png)
## 7. Atur Path Environment
Selanjutnya adalah pengaturan Path Environment. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih Git from the command line and also from 3rd-party software agar saat menjalankan perintah Git dapat dikenali di Command Prompt (CMD) pada Windows.
![image](https://user-images.githubusercontent.com/115523263/196169669-910443e7-35e4-407c-86c0-f0bc7834de66.png)
## 8. Pilih Line Ending
Selanjutnya, Anda perlu memilih pengaturan line ending. Klik Next untuk melanjutkan instalasi.
![image](https://user-images.githubusercontent.com/115523263/196171541-5b7bfaa9-50d9-4b10-8c2a-f16f45f234ae.png)
## 9. Pilih Emulator Terminal
Setelah itu, Anda perlu memilih emulator terminal yang akan digunakan. Anda bisa menggunakan Command Prompt atau MinTTY. Klik Next untuk melanjutkan instalasi.
![image](https://user-images.githubusercontent.com/115523263/196173239-897ea0fd-9c3f-41ff-960a-f95e7269df1b.png)
## 10. Tentukan Opsi ekstra
Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik Next untuk melanjutkan instalasi.
![image](https://user-images.githubusercontent.com/115523263/196173452-e8689d96-0256-486f-8839-fa851749504c.png)
## 11.  Mulai Proses Instalasi
Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik Install untuk melanjutkan proses.
![image](https://user-images.githubusercontent.com/115523263/196173601-e5b0df5d-fdbe-46f4-9aa4-4b938f2fda1e.png)
### Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.
![image](https://user-images.githubusercontent.com/115523263/196173757-e9eaa2a9-935a-48aa-b577-2e02d1c1375b.png)
## 12.  Cek Versi Git
Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui Command Prompt. Klik Win+R lalu ketik CMD untuk membuka Command Prompt seperti di bawah ini.
![image](https://user-images.githubusercontent.com/115523263/196178321-8d3f8f10-574c-4490-a9d2-f9df88d421f6.png)
Selanjutnya masukkan perintah berikut untuk cek versi git 

git --version

setelah git berhasil terinstall,Anda akan melihat tampilan seperti di bawah ini yang menunjukkan versi Git. 
![image](https://user-images.githubusercontent.com/115523263/196201349-843477c4-97ba-43df-b0c0-d3dfbd842ea9.png)

## cara menggunakan git
Setelah berhasil install ke Git, selanjutnya saya akan memberikan 10 langkah menggunakan Git. Berikut ini adalah langkah langkah menggunakan Git.
## 1. Login Git
Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, Anda bisa mendaftarkan diri terlebih dahulu. Selanjutnya Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) Kemudian masukkan perintah-perintah yang akan saya jelaskan di bawah ini.

Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.name "UsernameAnda"

Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.email IsiDenganEmailAnda@gmail.com

Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.

$ git config --list
![image](https://user-images.githubusercontent.com/115523263/196201637-08abd641-c3c7-43ae-97b3-63bfa83caac8.png)

## 2. Login Github
Langkah kedua dalam belajar menggunakan Git adalah Anda harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.
Setelah Anda login, akan muncul tampilan dashboard dari GitHub seperti  gambar di bawah ini.
![image](https://user-images.githubusercontent.com/115523263/196201783-2bd91c53-402d-4bf7-a331-695c009ccbf1.png)

## 3. Buat Repository
Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
![image](https://user-images.githubusercontent.com/115523263/196201997-097e9cf2-21d6-4934-91da-4c457bfe5e6b.png)
Kemudian Anda akan diarahkan pada halaman untuk membuat repository baru seperti gambar di atas

Anda perlu mengisi detail informasi berikut:

Nama Repository : digunakan untuk identitas repository yang dibuat.
Deskripsi Repository : berfungsi untuk deskripsi dari repository yang dibuat.
Jenis Repository   : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.
Setelah mengisi detail informasi di atas, klik Create Repository
## 4. Buat Folder pada Windows
Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
![image](https://user-images.githubusercontent.com/115523263/196202187-ec02d511-39d9-4e5d-b41b-bbc3336730be.png)
## 5. Buka Folder Menggunakan Git Bash
![image](https://user-images.githubusercontent.com/115523263/196202257-6bcbf3ca-e5b0-4ad7-8f27-e6c46e0eb75a.png)
Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 
![image](https://user-images.githubusercontent.com/115523263/196202361-2c980ec6-43c5-4c86-8348-81568cc56d85.png)

## 6. Ubah Folder Menjadi Repository
Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:

$ git init
![image](https://user-images.githubusercontent.com/115523263/196202472-670d8cac-b871-4ab1-99c4-608246af8984.png)

## 7. Tambahkan File ke Repository
Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini:

Buat file di folder yang sudah dibuat (latihan-vcs). Contohnya, di sini saya membuat file index.html
Buka GitBash lalu masukkan perintah berikut:

$ git add index.html

Perintah tersebut tidak akan menghasilkan output apa pun
## 8. Buat Commit 
Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:

$ git commit -m "first commit"

Pada tutorial ini saya membuat first commit sebagai Commit pertama kami. Anda bebas membuat membuat nama Commit apa saja.
![image](https://user-images.githubusercontent.com/115523263/196202657-9443e336-a925-48b7-8305-61ec3afb1551.png)

## 9. Remote Repository Github
Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:

$ git remote add origin git@github.com:UserNameGit/NamaRepository.git

Perintah di atas tidak akan menghasilkan output apa pun.
![image](https://user-images.githubusercontent.com/115523263/196202752-c19d5998-760c-4244-90e7-0505bd03cb19.png)

## 10. Push ke GitHub
Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:

git push -u origin master

Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub. 
## 11. Cek File 
Setelah itu, cek repository yang telah Anda buat. Anda akan mendapati file-file yang telah ditambahkan sebelumnya.
# Kesimpulan
Cara menggunakan Git ini wajib diketahui dan dikuasai oleh semua developer karena akan sangat membantu dalam mengerjakan project pembuatan website.
Demikian penjelasan tentang cara menggunakan Git. Jika masih ada pertanyaan, jangan sungkan untuk meninggalkan di kolom komentar. Jangan lupa juga subscribe untuk mendapatkan informasi terbaru dari kami.
