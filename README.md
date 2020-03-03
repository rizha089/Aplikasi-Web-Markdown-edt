# Aplikasi-Web-Markdown-edt
<h1 align="center"><img src="https://raw.github.com/georgeOsdDev/markdown-edit/master/images/ScreenShot.png"></h1>


[Penjelasan](#Penjelasan) | [Instalasi](#Instalasi) | [Fitur](#Fitur)
:---:|:---:|

## Penjelasan
[`^ kembali ke atas ^`](#)

Ini adalah online markdown editor yang dapat mempermudah anda dalam men-sunting dokumen dengan teknologi web, aplikasi web markdown editor memiliki tools untuk melakukan konversi text-to-HTML yang bisa digunakan untuk membuat konten web. Dengan menggunakan Mawrkdown kita dapat menulis konten HTML dengan format yang mudah dibaca dan mudah pula untuk ditulis(easy-to-read dan east-to-write).
## Instalasi
[`^ kembali ke atas ^`](#)

### Kebutuhan sistem :
- Unix, Linux atau Windows.
- Apache Web server 1.3+.

### Proses Instalasi :
1. Login kedalam server menggunakan SSH.
    ```
    $ ssh student@localhost -p 2200
    ```
2. Lakukan kloning pada github yang menjadi refrensi.
    ```
    $ git clone http://github.com/georegeosddev/markdown-edit.git
    ```
3. Kemudian install bower agar tampilannya lebih bagus.
    ```
    $ bower install
    ```
4. Meluncurkannya ke web server.
    ```
    $ ln -s /home/student/markdown-edit /var/www/html/markdown-edit
    $ ls -la
    ```
5. Setelah proses instalasi selesai hapus direktori install untuk alasan keamanan.    
    ``` 
    $ sudo rm -rf /var/www/html/markdown-edit
    ```
6. Setelah semuanya dilakukan, akses http://localhost:8000 untuk melihat hasilnya.

## Fitur
[`^ kembali ke atas ^`](#)
### Editor
* Menampilkan nomor baris
* Mencocokan tanda dalam dokumen
* Drag dan Drop file
* Mengganti tema
* Menandakan syntaks markdown
### Convertor
Untuk mencovert markdown menjadi html, Markdown-Edit menggunakan Github's API sebagai standar
### Viewer
Untuk menampilkan hasil konversi HTML seperti Github, Markdown-Edit dapat menggunakan github.css dari highlight.js dan github-style
    
