# SCM-Revision-Control-Source-Code-Management-dan-Git

Pembahasan   :

Judul :
SCM, Revision Control/Source Code Management dan Git

Langkah-langkahnya :

Welcome to Git (version 1.6.4-preview20090730)

Run 'git help git' to display the help index.
Run 'git help <command>' to display help for specific commands.

Student@APLIKASI ~/My Documents/lukasvandohop10018

$ mkdir src
=>> Perintah yang berfungsi untuk membuat  sebuah directory baru dengan src.
Student@APLIKASI ~/My Documents/ lukasvandohop10018

$ cd src
=>>Perintah yang berfungsi untuk memakai atau memasuki sebuah directory baru dengan src
Student@APLIKASI ~/My Documents/lukasvandohop10018/src

$ vim student
=>>Perintah untuk menampilkan sebuah tampilan data seperti nama dan alamat email yang telah kita ketikan,Contoh dengan nama “student” dan email “vandohoplukas@yahoo.co.id”
Student@APLIKASI ~/My Documents/lukasvandohop10018/src

$ git config --global user. lukasvandohop "student"
=>>Perintah untuk mengatur  sebuah git  config yang nantinya akan merubah atau mengisikan sebuah nama.
Student@APLIKASI ~/My Documents/lukasvandohop10018/src
$ git config --global user.email vandohoplukas@yahoo.co.id 

=>>Perintah untuk mengatur  sebuah git  config yang nantinya akan merubah atau mengisikan sebuah alamat email.
Student@APLIKASI ~/My Documents/lukasvandohop10018/src
$ git init

=>>Perintah yang berfungsi untuk melakukan penginstalan sebuah folder src di bagian folder lukasvandohop10018  letaknya di My Documents yang telah kita buat tadi.
Initialized empty Git repository in c:/Documents and Settings/Student/My Documen
ts/lukasvandohop10018/src/.git/
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)
$ git add .

=>>Perintah yang berfungsi untuk penambahan sebuah folder src di bagian folder lukasvandohop10018 letaknya di My Documents yang telah kita buat tadi.
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)
$ ls -la .git/
=>>Perintah yang berfungsi untuk mengecek folder yang telah kita buat tadi,contoh pada nama dan alamat email tadi .
total 2
drwxr-xr-x    6 Student  Administ        0 Nov 11 18:56 .
drwxr-xr-x    4 Student  Administ        0 Nov 11 18:45 ..
-rw-r--r--    1 Student  Administ       23 Nov 11 18:56 HEAD
-rw-r--r--    1 Student  Administ      130 Nov 11 18:56 config
-rw-r--r--    1 Student  Administ       73 Nov 11 18:56 description
drwxr-xr-x    2 Student  Administ        0 Nov 11 18:56 hooks
-rw-r--r--    1 Student  Administ      112 Nov 11 18:56 index
drwxr-xr-x    2 Student  Administ        0 Nov 11 18:56 info
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ git commit
=>>Berfungsi untuk menjalankan sebuah perintah yang telah kita ketikan tadi atau kita buat tadi,Contoh pada insert tadi kita ketikan TES TOP SPEED maka akan muncul seperti dibawah ini hasilnya .
[master (root-commit) aeaf55d] TES TOP SPEED
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 student
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ git diff
=>>Perintah yang berfungsi untuk mengecek dalam  folder lukasvandohop10018  letaknya di My Documents yang telah kita buat tadi dengan src.
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ ls –la
=>>Perintah yang berfungsi untuk mengecek folder lukasvandohop10018 dengan src yang telah kita buat tadi.
total 1
drwxr-xr-x    3 Student  Administ        0 Oct 18 08:23 .
drwxr-xr-x    3 Student  Administ        0 Oct 18 08:21 ..
drwxr-xr-x    7 Student  Administ        0 Oct 18 08:33 .git
-rw-r--r--    1 Student  Administ       22 Oct 18 08:27 student
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ vim student
=>>Perintah untuk menampilkan sebuah tampilan data seperti nama dan alamat email yang telah kita ketikan,Contoh dengan nama “student” dan email “vandohoplukas@yahoo.co.id”
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ git status
=>>Perintah yang berfungsi untuk mengecek status dari workcopy apakah sudah ada perubahan atau belum pada folder src yang telah kita buat tadi.
# On branch master
nothing to commit (working directory clean)
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ git diff
=>>Perintah yang berfungsi untuk mengecek dalam  folder lukasvandohop10018  letaknya di My Documents yang telah kita buat tadi dengan src.
Student@APLIKASI ~/My Documents/lukasvandohop10018/src (master)

$ git log=>>Perintah yang berfungsi untuk mengecek atau melihat email dan pesan yang tadi sudah kita ketikan seperti dibawah ini hasilnya.

commit aeaf55d029aeeb75961d9cfb5cbbc6b47b058c60
Author: unknown < vandohoplukas@yahoo.co.id >
Date:   Fri Oct 18 08:36:39 2013 +0700
    TES TOP SPEED
    
Selesai.dan berhasil.
