## Apa itu E-Sekolah?
Dalam dunia pendidikan kehadiran akan situs website akan sangat membantu diantarnya sebagai sarana untuk promosi, penyampaian informasi, instansi akan lebih professional serta masih banyak lagi manfaat yang dapat diperoleh bagi instansi pendidikan ketika menggunakan website. Dalam rangka digitalisasi untuk pendidikan E-Sekolah hadir untuk menjawab permasalahan tersebut. 

## Fitur E-Sekolah?
Berikut beberapa fitur yang ada di dalam E-Sekolah 
- Manajemen Artikel Sekolah
- Manajemen Fasilitas Sekolah
- Manajemen Jurusan Sekolah
- Manajemen Agenda Sekolah
- Manajemen Tentang Sekolah
- Dan masih banyak lagi 
Oleh karena itu website itu sangat cocok digunakan untuk instansi pendidikan mulai dari tingkat SD, SMP, SMA / SMK

## Apakah E-Sekolah open source?
Ya E-Sekolah open source dan kamu juga bisa mengembangkannya kembali, akan tetapi dilarang untuk menghapus atau menghilangkan credit

## Tampilan Halaman Login E-Sekolah
![image](https://user-images.githubusercontent.com/57394564/192224064-f8d23c7d-c433-41a2-ba7e-02b60a03592c.png)

## Tampilan Halaman Manajemen Admin E-Sekolah
![image](https://user-images.githubusercontent.com/57394564/192412620-48cb7583-1f6d-4eec-be06-cc89db8b3490.png)

## Requirements
- Sudah terinstall composer
- Sudah terinstall XAMPP

## Cara Menggunakan E-Sekolah
- Langkah pertama silahkan clone repository ini, kemudian jangan lupa di beri star
- Selanjutnya memasang semua dependensi project menggunakan perintah 
```dark
composer install
```
- Jika Mengalami kegagalan coba untuk melakukan update
```
composer update
```
- Langkah selanjutnya adalah mengenerate file env example menggunakan perintah
```
cp .env.example .env
```
- Kemudian lakukan generate key, menggunakan perintah
```
php artisan key:generate
```
- Kemudian set up database terlebih dahulu di phpmyadmin Anda
- Kemudian edit file hasil generate env file, seperti berikut. Cocokan dengan nama database Anda

- Kemudian lakukan migrate database menggunakan perintah
```
php artisan migrate
```
- Terakhir lakukan seed menggunakan perintah
```
php artisan db:seed
```
