
##### instalasi git bash
##### masuk ke github

#### Langkah-langkah
##### 1.*Buat Repositori di GitHub :
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru. ![[buat_repositori.png]]
   
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".![[Pasted image 20240731223815.png]]

##### 2. *Konfigurasi awal di Gitbash *:
   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:
    ~~~
     git config --global user.name "Nama Anda"
     git config --global user.email "email@example.com"
~~~

    *Note:* untuk melihat apakah sudah terhubung konfigurasi git nya silakan ketik 
     git config --list
 *contohnya:*![[konfigurasi_git_lokal.png]]

##### 3.akses folder proyek di git bash
![[akses_folder.png]]

##### 3. *Inisialisasi Git Lokal*:
   -  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
    ~~~
     git init
 ~~~ 
 contohnya:
      ![[git_init.png]]
      
     
##### 4. *Hubungkan ke Repositori GitHub*:
   - Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
     ~~~shell
     git remote add origin https://github.com/username/nama-repository.git
     ~~~
   Ganti username dan nama-repository dengan nama pengguna GitHub Anda dan nama repositori yang Anda buat.kalo dah ada tulisan (master),berarti sudah terhubung ke repositori Githubnya
   *contohnya:*
     ![[hubungkan_repositori.png]]
     
###### 5. *Tambahkan file ke repositori*: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
     cs
     git add .
     
   *contohnya:*![[git_add.jpg]]

##### 8.tambahkan file ke repositori
- perianta ini  akan menambah kan sebuah file di direktori saat inin ke repositori
- tambah kan file yang anda ingin simpan di repositori git dengan menjalan kan perintah 

```git
git add
```

hasil: 
![](git_add.png)
##### 10.hubungkan folder proyek lokal ke github
###### . *Buat Commit:*
   - Jalankan perintah berikut untuk membuat commit dengan pesan yang jelas:
   - Perintah git commit -m *"Pesan commit"* digunakan untuk menyimpan perubahan yang telah dilakukan pada repositori Git dengan menambahkan pesan
     ~~~git
     git commit -m "Pesan commit"
     ~~~
     *contohnya:*
     ![[commit.jpg]]
   Unggah ke GitHub   (git push origin master):
   Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:

###### . *Unggah ke GitHub*:
   - Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:
    ~~~
     git push -u origin master
~~~ 
 *contohnya:*
     ![[git push origin.jpg]]
     maka akan tetampil bgini,berarti anda disuruh untuk login akun github mu yang sudh kamu buat 
     ![[login.jpg]]
   Perintah ini akan mengunggah kode Anda ke repositori GitHub. Setelah ini, setiap kali Anda membuat perubahan pada kode, Anda dapat mengulangi langkah 4, 5,6 dan 7 untuk mengunggah perubahan tersebut ke GitHub.

