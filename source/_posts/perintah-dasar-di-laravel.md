---
layout: posts
title: perintah-dasar-di-laravel.md
date: 2022-10-07 23:32:00
tags:
---

# Perintah Dasar Di Laravel

Sesi kali ini saya akan membahas mengenai perintah dasar di salah satu framework PHP yaitu laravel, laravel sendiri merupakan sebuah framework yang powerfull dan mudah untuk di gunakan, oleh karena itu tidak jarang para pengguna baik dari kalangan mereka yang baru belajar atau bahkan sekelas perusahaan pun menggunakan framework yang satu ini.

Laravel kini sudah mencapai ke versi 9x yang mana akan ada syntaxsis baru di dalamnya, walau sudah naik versi tetapi perintah dasar untuk menjalankan laravel
ini masihlah sama seperti versi-versi sebelumnya.

Untuk itu mari kita bahas perintah dasar apa saja sih yang ada di dalam laravel ini, sebelum itu pastikan kalian sudah mengintsall laravel ini di komputer kalian masing-masing, jika belum kalian bisa masuk ke laman resmi web laravel.

[!Laravel]('https://laravel.com')

Jika sudah menginstallnya kalian bisa lanjutkan ke step pembahasan selanjutnya.

# Perintah untuk melakukan Migrate
di laravel sudah di sediakan beberapa table default yang tersedia seperti :
    - user
    - migration
    - failed_jobs
    - password_resets
    - personal_access_tokens

lalu fungsi table default di atas pada laravel untuk apa ? mengenai fungsi dari table di atas nanti saya akan menjelaskan di postingan terpisah, jika saya masukkan ke dalam postingan ini maka akan melenceng dari judul.

perintah untuk melakukan migrate `php artisan migrate ` dan tekan enter otomatis laravel akan memigrate table bawaan yang sudah di sebutkan di atas tadi.

sebenarnya bukan hanya perintah migrate default saja di laravel juga banyak sekali perintah dasar dari migrate seperti :
    - migrate:fresh (untuk merefresh table di database dan mengulang migrate tanpa menghapus data di database.)
    - migrate:install (untuk menginstall dan juga melakukan migrate secara bersamaan)
    - migrate:refresh(fungsinya sama seperti di atas yaitu merefresh table di database)
    - migrate:reset(untuk mereset table di database).
    - migrate:rollback(untuk menghapus seluruh table yang ada di database)
    - migrate:status(untuk melihat status dari migrate yang kita lakukan)

Perintah di atas merupakan perintah default yang biasa di lakukan di laravel. selain perintah migrate di laravel ada perintah dasar namanya seed.

# Perintah melakukan seed.

di laravel juga sudah di sediakan perintah seed fungsinya adalah untuk membuat sebuah data dummy atau data palsu yang akan di gunakan sebagai experiment sebelum data aslinya di masukkan.

perintah untuk melakukan seed `php artisan make:seeder UserSeeder` tekan enter dan akan di buatkan sebuah data dengan nama UserSeeder.

untuk contohnya kalian bisa baca di dokumentasi laravel mengenai seeding,

# Apakah ada perintah lain di laravel selain yang di 2 tadi ?

sebenarnya masih banyak perintah di laravel saya ambil contoh satu lagi yaitu perintah untuk membuat sebuah model `php artisan make:model namamodel` dan satu lagi untuk membuat sebuah controller `php artisan make:controller namaController` dan masih banyak lagi perintah dasar yang ada di laravel 9x , jika penasaran kalian bisa langsung ke dokumentasinya dan coba-coba pada app kalian masing-masing.

Sekian pembahasan kali ini kurang lebihnya mohon maaf, assalamu'alaikum wr.wb.


