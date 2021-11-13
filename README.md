# latihanvcs
# Cara menggunakan git
#### Pengertian git
##### Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
# cara menambahkan global config
##### pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut

##### - git config --global user.name "username"

##### - git config --global user.email "email"
![gambar](ss/ss1.png)
# jalankan perintah git init. untuk membuat repository local
##### - git init 
![gambar](ss/ss2.png)
# Untuk membuat file dapat menggunakan Text Editor, lalu menyimpan filenya pada repository. disini saya akan membuatkan contoh membuat file README.md dengan perintah berikut
##### - echo#labs1 >> README.md
![gambar](ss/ss3.png)
# Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add. (jika file nya ada banyak)
##### - git add README.md
##### - git add
![gambar](ss/ss4.png)
# Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" dan yang ada didalam kutip "" itu adalah nama komentar setiap kita mencommit project
##### - git commit -m "nama project"
![gambar](ss/ss5.png)
# Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
##### - git remote add origin https://github.com/Adin25/latihanvcs.git
# Untuk mengirim perubah.pngan pada repository local ke server, gunakan perintah git push, perintah ini akan meminta Username dan Password pada akun github mu
##### - gitpush-u origin main
![gambar](ss/ss7.png)
