# LatihanVCS
Repository ini dibuat untuk memenuhi tugas pertemuan 4  - Bahasa Pemrograman

Nama    :   Aditya Achya Ananta Nur

Nim     :   312210714

Kelas   :   TI.22.C.9

## Langkah-Langkah Penggunaan Git![git-scm]


* Download Git terlebih dahulu, dengan link berikut ini : [Click Here](https://git-scm.com/)
![Gambar Git SCM]![git-scm](https://user-images.githubusercontent.com/123864099/215322921-21ad3df0-8121-49d7-a60f-7f207d279412.png)

)

* Setelah installasi selesai, buka *software* **GitBash** pada menu di Windows, dan lakukan pengecekan versi, dengan mengetik syntax berikut :
    > git --version


![Git Pict Version Check]![git-version](https://user-images.githubusercontent.com/123864099/215322937-245f57bb-5c6a-454e-b570-2e57a972e3ab.PNG)



* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan *syntax* berikut :
> git config --global user.name "Masukkan Nama Anda disini"
> git config --global user.email "Masukkan Email Anda disini"

![Picture - Add User]![git-addname](https://user-images.githubusercontent.com/123864099/215322978-7f10e2f5-36f8-4ff9-92fa-0d799c324b79.PNG)



Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut :
> git config --global user.name
> git config --global user.email

![Picture - Cek User]!![git-cekname](https://user-images.githubusercontent.com/123864099/215323004-a3402e7b-4c30-41cc-b744-b197e02f080e.PNG)


* Buat akun di [GitHub](https://github.com) , seperti contoh dibawah ini. Dan lakukan *verifikasi* akun melalui email yang sudah terdaftar. 
![Picture Github SignUp]![github-signup](https://user-images.githubusercontent.com/123864099/215323022-423c4b2a-63f3-4e76-b2de-a809f310ca1f.PNG)

* Jika akun GitHub sudah selesai dibuat dan diverifikasi, Proses selanjutnya silahkan buat *Repository* seperti gambar dibawah ini.
**Penjelasan** : 
> * Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository *LatihanVCS*)
> * Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)
> * Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)
> * Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda
> * Add .gitignore : Merupakan  sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.
> * Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat
Kemudian tekan tombol **Create Repository** untuk menyimpan
![github-create-repo](https://user-images.githubusercontent.com/123864099/215323258-d910592c-0e52-4d79-9d60-3fe80a51e537.PNG)





* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :
![github-code](https://user-images.githubusercontent.com/123864099/215322876-4a5cc0d1-7da9-4c09-af6d-2fe845a6bfc9.PNG)



* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk *me-remote* repository Github pada GitBash Lokal. Bagaimana caranya?
Langkah pertama kita harus menyalin *link URL* git kita di Github, dengan cara tekan tombol **Code** lalu klik *Copy*.

![Picture - Copy Link Github]![github-code](https://user-images.githubusercontent.com/123864099/215323275-a72e1ca6-9925-4272-aced-0d616d751e4f.PNG)


* Setelah *Link URL* git kita ter*copy*, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan men*download* Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih ***Git Bash Here***.
![Picture - Git Bash Here]![gitbash-here](https://user-images.githubusercontent.com/123864099/215323285-81b39e70-41f2-4bca-b06f-506e0a9b3b8a.png)

* *Pop Up* Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan *syntax* berikut :
> git clone [URL]
Pada contohnya, saya akan memasukkan *git clone https://github.com/AdityaAchya/LatihanVCS.git*
![git-clone](https://user-images.githubusercontent.com/123864099/215323294-771a15a5-d8bb-4505-b6a5-c1c04f1b06d2.PNG)


* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu *LatihanVCS* dengan mengetikkan *syntax* berikut :
> cd LatihanVCS/

![cd-folder](https://user-images.githubusercontent.com/123864099/215323307-6e510230-44c8-433a-96c1-89b07e23a1ed.PNG)

* Saat ini kita sudah masuk kedalam folder *LatihanVCS*, Silahkan edit file **README.md** yang ada di File Explorer. Bisa menggunakan Text Editor (*Sublime Text, Notepad, Notepad++, Visual Studio Code*). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : [Click Here](https://guides.github.com/features/mastering-markdown/)
![readme-edit](https://user-images.githubusercontent.com/123864099/215323319-a19b0ceb-636f-408a-8764-a5f1010ab93c.PNG)

Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara **CTRL+S** atau **File -> Save**

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini :
> git add .

![pictgit-add](https://user-images.githubusercontent.com/123864099/215323345-fb831def-fbca-489d-8921-d73843fd5d29.PNG)


* Setelah selesai melakukan *git add .* langkah berikutnya kita akan melakukan **commit*. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini :
> git commit -m "Update README.md"

![git-commit](https://user-images.githubusercontent.com/123864099/215323368-30ce51f8-142e-41b5-8b2b-980799661d03.PNG)

* Git *commit* telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, *Git Push* berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut :
> git push

![git-push](https://user-images.githubusercontent.com/123864099/215323397-5d1aa7d3-c03b-4bef-af64-bcde84714532.PNG)


* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di *commit* dan *push* dari remote. 

![git-view2](https://user-images.githubusercontent.com/123864099/215323411-4148af81-64b6-4014-99ae-dbf564f7f493.PNG)


Hal diatas adalah Cara Langkah-Langkah Penggunaan GIT.

Sekian informasi yang dapat saya bagikan kepada kalian.

## TERIMA KASIH
### ADITYA ACHYA ANANTA NUR - 312210714 - TI.22.C. - TEKNIK INFORMATIKA - UNIVERSITAS PELITA BANGSA
