Latihan 1 #latihan1 cara penggunan git 
•	Download Git, buka website resminya Git (git-scm.com). 

![image](https://user-images.githubusercontent.com/56190893/66699015-551f8e80-ed0d-11e9-89e9-a3dc20f4552c.png)
 

1.	install git terlebih dahulu
2.	buka aplikasi git dan jalankan perintah "git config --global user.nama "nama anda" lalu enter dan tulis "git config --global user.email "email anda"

![image](https://user-images.githubusercontent.com/56190893/66699033-813b0f80-ed0d-11e9-9af7-f9bb17606d55.png)


3.	Membuat Reposiory Local
klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad Buat direktory project praktikum pertama dengan nama latihan1
Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori         tersebut dengan perintah cd (change directory)
Jalankan perintah git init, untuk membuat repository local.Repository baru berhasil diinisialisasi, dengan terbentuknya satu direktori hidden dengan nama .gitPada direktori tersebut, semua perubahan pada working directory akan disimpan.

![image](https://user-images.githubusercontent.com/56190893/66699077-cb23f580-ed0d-11e9-826d-b999917344f3.png)


4.	Menambahkan File baru pada reposiUntuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)disini kita akan coba buat satu file bernama README.md (te126b6557a.png)
ext file)File README.md berhasil dibuat.
!
![image](https://user-images.githubusercontent.com/56190893/66699097-fb6b9400-ed0d-11e9-9dda-d9e126b6557a.png)

5.	Menambahkan File baru pada repository Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
File README.md berhasil ditambahkan 

![image](https://user-images.githubusercontent.com/56190893/66699113-248c2480-ed0e-11e9-86e1-0db2548a374d.png


6.	Lalu gunakan Git commit untuk menyimpan perubahan Kedalam database git				 gunakan perintah git commit -m “file pertama saya”

![image](https://user-images.githubusercontent.com/56190893/66699130-38d02180-ed0e-11e9-8284-effca82bfe64.png)
)


7.	Membuat repository server
Server reopsitory yang akan kita gunakan adalah http://github.com
Dari menu (icon +) klik New Repository

![image](https://user-images.githubusercontent.com/56190893/66699137-4be2f180-ed0e-11e9-9d4d-3de43026ccaa.png)
 
8.	Isi nama repositorynya, misal: latihan1
lalu klik tombol Create repository

![image](https://user-images.githubusercontent.com/56190893/66699143-5d2bfe00-ed0e-11e9-83d7-ea505bb1a0f2.png)

 

9.	Menambahkan Remote Repository
Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

![image](https://user-images.githubusercontent.com/56190893/66699153-716ffb00-ed0e-11e9-91e2-43fe10e07855.png)



10.	Lalu setelah itu kita menggunakan $ git push-u origin master untuk mengirim perubahan dari
local repository ke server dan pada perintah ini akan anda akan di minta memasukan username 
dan password anda pada akun github.com 
11.	Jika sudah lalu anda tinggal melihat hasil pada server repository , caranya anda membuka github.com 
Lalu klik repository , jselesai
 
 ![image](https://user-images.githubusercontent.com/56190893/66699175-8fd5f680-ed0e-11e9-862a-71fe40684206.png)

