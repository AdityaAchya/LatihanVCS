# LatihanVCS
Repository ini dibuat untuk memenuhi tugas pertemuan 4  - Bahasa Pemrograman

Nama    :   Aditya Achya Ananta Nur

Nim     :   312210714

Kelas   :   TI.22.C.9

## Langkah-Langkah Penggunaan Git![git-scm]


* Download Git terlebih dahulu, dengan link berikut ini : [Click Here](https://git-scm.com/)
![Gambar Git SCM][Uploading git-scm.png…]()
)

* Setelah installasi selesai, buka *software* **GitBash** pada menu di Windows, dan lakukan pengecekan versi, dengan mengetik syntax berikut :
    > git --version


![Git Pict Version Check]![Uploading git-version.PNG…]()


* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan *syntax* berikut :
> git config --global user.name "Masukkan Nama Anda disini"
> git config --global user.email "Masukkan Email Anda disini"

![Picture - Add User]![Uploading git-addname.PNG…]()


Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut :
> git config --global user.name
> git config --global user.email

![Picture - Cek User]![Uploading git-cekname.PNG…]()


* Buat akun di [GitHub](https://github.com) , seperti contoh dibawah ini. Dan lakukan *verifikasi* akun melalui email yang sudah terdaftar. 
![Picture Github SignUp][Uploading github-signup.PNG…]()
G)

* Jika akun GitHub sudah selesai dibuat dan diverifikasi, Proses selanjutnya silahkan buat *Repository* seperti gambar dibawah ini.
**Penjelasan** : 
> * Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository *LatihanVCS*)
> * Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)
> * Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)
> * Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda
> * Add .gitignore : Merupakan  sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.
> * Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat
Kemudian tekan tombol **Create Repository** untuk menyimpan
![Picture Create Github Repository]![Uploading github-create-repo.PNG…]()


* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :
![Picture - Github View 1]!![github-code](https://user-images.githubusercontent.com/123864099/215322876-4a5cc0d1-7da9-4c09-af6d-2fe845a6bfc9.PNG)



* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk *me-remote* repository Github pada GitBash Lokal. Bagaimana caranya?
Langkah pertama kita harus menyalin *link URL* git kita di Github, dengan cara tekan tombol **Code** lalu klik *Copy*.

![Picture - Copy Link Github](pict/github-code.PNG)

* Setelah *Link URL* git kita ter*copy*, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan men*download* Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih ***Git Bash Here***.
![Picture - Git Bash Here](pict/gitbash-here.png)

* *Pop Up* Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan *syntax* berikut :
> git clone [URL]
Pada contohnya, saya akan memasukkan *git clone https://github.com/AdityaAchya/LatihanVCS.git*
![Picture Git Clone](pict/git-clone.PNG)

* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu *LatihanVCS* dengan mengetikkan *syntax* berikut :
> cd LatihanVCS/

![Picture Pilih Direktori](pict/cd-folder.PNG)

* Saat ini kita sudah masuk kedalam folder *LatihanVCS*, Silahkan edit file **README.md** yang ada di File Explorer. Bisa menggunakan Text Editor (*Sublime Text, Notepad, Notepad++, Visual Studio Code*). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : [Click Here](https://guides.github.com/features/mastering-markdown/)
![Picture - README.md Edited](pict/readme-edit.PNG)

Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara **CTRL+S** atau **File -> Save**

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini :
> git add .

![Picture - Git Add](pict/git-add.PNG)

* Setelah selesai melakukan *git add .* langkah berikutnya kita akan melakukan **commit*. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini :
> git commit -m "Update README.md"

![Picture - Git Commit](pict/git-commit.PNG)

* Git *commit* telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, *Git Push* berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut :
> git push

![Picture - Git Push](pict/git-push.PNG)

* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di *commit* dan *push* dari remote. 

![Picture - View 2](pict/git-view2.PNG)


Hal diatas adalah Cara Langkah-Langkah Penggunaan GIT.

Sekian informasi yang dapat saya bagikan kepada kalian.

## TERIMA KASIH
### ADITYA ACHYA ANANTA NUR - 312210714 - TI.22.C. - TEKNIK INFORMATIKA - UNIVERSITAS PELITA BANGSA
