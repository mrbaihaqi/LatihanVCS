<h2>Git</h2>
Git adalah perangkat lunak pengendali versi atau proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds, yang pada awalnya ditujukan untuk pengembangan kernel Linux. Desain Git terinspirasi oleh BitKeeper dan Monotone. Git pada awalnya hanya dirancang sebagai mesin tingkat rendah yang dapat digunakan oleh tampilan muka (front end) lain seperti Cogito atau StGIT. Namun selanjutnya proyek inti Git telah berkembang menjadi pengendali revisi lengkap yang dapat digunakan langsung. Saat ini, beberapa perangkat lunak terkenal menggunakan Git sebagai pengendali revisinya, antara lain kernel Linux, Server X.org, pengembangan inti OLPC (One Laptop per Child), serta kerangka kerja web Ruby on Rails. Pemeliharaan perangkat lunak Git saat ini diawasi oleh Junio Hamano. Dirilis di bawah Lisensi Publik Umum GNU versi 2, Git adalah suatu perangkat lunak bebas. 

# Cara Menggunakan Git dan Github:

1.Install git terlebih dahulu(www.git-scm.com)

2.Setelah menginstall Git, Silahkan cek untuk melihat versi Git yang anda install dengan mengetik

![image](https://user-images.githubusercontent.com/108067634/215322900-f41617a6-304a-4864-b322-c64bf6645717.png)

    git version
  
3.Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows)

4.Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.

![image](https://user-images.githubusercontent.com/108067634/215322932-346f8915-f3fb-4d14-b6aa-8167707f3a79.png)

    $ git config --global user.name "UsernameAnda"
  
5.Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.

![image](https://user-images.githubusercontent.com/108067634/215322940-5fe315ac-5fd2-4684-b710-fa1a768eaffb.png)
      
    $ git config --global user.email emailanda
  
6.Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.

![image](https://user-images.githubusercontent.com/108067634/215322953-411de525-d8e5-4c25-a282-7abb55289702.png)
       
    $ git config --list
  
7.Login ke Github

![image](https://user-images.githubusercontent.com/108067634/215322969-af369109-ccf4-43f2-86ed-ee1c17ad71b8.png)
  
8.Buat akun terlebih dahulu jika anda baru pertama kali menggunakan Github

![image](https://user-images.githubusercontent.com/108067634/215322982-73005c76-94b8-453b-bc8f-786fef9be4bb.png)
  
9.Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![image](https://user-images.githubusercontent.com/108067634/215322996-aac22d1d-f83d-4116-a3e1-a9ac7eb0bdba.png)

10.Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.

![image](https://user-images.githubusercontent.com/108067634/215323002-a703aa89-15d2-4909-b10b-44cd7bb888fa.png)
  
11.Setelah berhasil membuat folder pada local disk komputer Anda, buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 

![image](https://user-images.githubusercontent.com/108067634/215323014-e3aaa0f6-a8c5-492f-915c-dda31fbfe35e.png)
  
12.Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut

![image](https://user-images.githubusercontent.com/108067634/215323020-7d2e7eda-0ce2-47aa-b1d7-4b04b3fb3b3a.png)
       
    $ git init

13.Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini

![image](https://user-images.githubusercontent.com/108067634/215323029-0ba99aff-6078-4131-9512-086119cdca68.png)
   
->Buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini kami membuat file README.md

14.Buka GitBash lalu masukkan perintah berikut

![image](https://user-images.githubusercontent.com/108067634/215323039-3db29e25-b9e3-4c23-8969-0fdc38f26d81.png)
      
    $ git add README.md
   
15.Lalu setelah itu ketik perintah berikut

![image](https://user-images.githubusercontent.com/108067634/215323047-ca0b8dd4-a210-4ee0-b60d-a185e3ec01b1.png)

    $ git add .
    
16.Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit

![image](https://user-images.githubusercontent.com/108067634/215323066-9aeaf6e5-efa6-4fa8-9085-51d914c57df5.png)
    
    $ git commit -m "first commit"
   
17.Setelah git commit, lalu anda masukan perintah git log

![image](https://user-images.githubusercontent.com/108067634/215323073-898ff74e-19db-41d3-bb93-8cbef6c88874.png)

        
    $ git log
     
18.Lakukan Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository

![image](https://user-images.githubusercontent.com/108067634/215323088-efd8e551-6cd1-42e1-9156-84310121b77b.png)
        
    $ git remote add origin https://github.com/AkbarXelion/LatihanVCS.git
   
19.Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub

![image](https://user-images.githubusercontent.com/108067634/215323094-9df2b651-9b14-4f94-94f1-4bffa88e88a4.png)
        
    $ git push -u origin main

->Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.
      
20.Selesai anda sudah berhasil menginstall git juga menggunakan git dan github

![image](https://user-images.githubusercontent.com/108067634/215323107-7e142916-92af-4709-8805-cda0bc85d7eb.png)
