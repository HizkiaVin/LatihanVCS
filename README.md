# LatihanVCS
Tutorial cara penggunaan git.
Sebelum menggunakan git, hal yang harus anda lakukan adalah mengunduh file-nya dari situs resmi. Unduh sesuai tipe sistem pada operasi komputer anda. Jika sistem operasi komputer anda 64 bit, pilih Git ynag 64 bit. Untuk mengunduh dari situs resmi, silahkan kunjungi git-scm.com.
Jika sudah selesai terunduh, buka CMD lalu ketik git --version
![Screenshot 2022-10-22 092526](https://user-images.githubusercontent.com/116176746/197316569-6daba721-4468-4bf2-83c0-57c6dee76d3d.png) 

Jika muncul seperti tampilan diatas, git bash berhasil di instal pada komputer anda

Setelah Git berhasil di unduh, selanjutnya adalah membuat repository lokal.

Buka directory aktif, misal: D:\Hizkia\LatihanVCS lalu klik kanan pada directory aktif tersebut lalu pilih Git Bash here
![buat file dan run di git bash](https://user-images.githubusercontent.com/116176746/197316887-9bcdd2e4-3fa8-4ce1-9e87-d56787fa5d1e.png)

Sehingga akan muncul git bash command, lalu buat directory project dengan nama "Latihan1". Untuk membuat directory project bisa dengan memasukan perintah $mkdir Latihan1, maka file pada repository lokal menambah file dengan nama Latihan1 ![mkdir](https://user-images.githubusercontent.com/116176746/197317223-ae5ae8cd-5ca4-4c64-936e-1a1d8d23810c.png)
Untuk change directory, bisa dengan memasukkan perintah $ cd Latihan1 sehingga directory aktif menjadi /d/Hizkia/LatihanVCS/Latihan1 ![cd](https://user-images.githubusercontent.com/116176746/197317330-c6708851-b9f5-457f-8dc8-dc984bbec870.png)

Membuat Repository Lokal

masukkan perintah $ git init untuk membuat repository lokal, repository baru berhasil di inisialisasi, dengan terbentuknya satu
direktori hidden dengan nama .git . Pada direktori tersebut, semua perubahan pada working directory akan disimpan. 
![git initt](https://user-images.githubusercontent.com/116176746/197317631-68bf2fe8-abac-4ee1-9026-1b84508951de.png)

Membuat file baru pada repository 

Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository), kita akan coba buat satu file bernama README.md (text file)
gunakan perintah $ echo "Latihan1" >>README.md
![echo](https://user-images.githubusercontent.com/116176746/197317858-65c8990c-4cc2-45ac-9df6-f6bc30767c1d.png)
![readme md](https://user-images.githubusercontent.com/116176746/197317854-0bf126d5-c44e-4e9d-8a90-954e2861e255.png)

selain menggunakan perintah $ echo "Latihan1" >> README.md kita juga bisa menggunakan perintah $ git add README.md

Untuk menyimpan perubahan ke database kita bisa menggunakan perintah $ git commit -m "isi sesuai yang diinginkan", disini saya mencoba dengan $ git commit -m "Percobaan Pertama" 

![commit](https://user-images.githubusercontent.com/116176746/197318245-69e20398-c7c7-40b4-9e76-f5d895cef7f3.png)
Jika sudah sama seperti gambar di atas, artinya perubahan berhasil disimpan.

