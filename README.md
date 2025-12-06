# Anime-Verse

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Flutter Version](https://img.shields.io/badge/Flutter-3.x-blue.svg)](https://flutter.dev)
[![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com/)

Repositori ini berisi kode sumber untuk aplikasi mobile "Anime-Verse", sebuah proyek yang dikembangkan sebagai bagian dari tugas perkuliahan.


## a. Identitas Mahasiswa

|            Nama Lengkap             |       NIM       |
|:-----------------------------------:|:---------------:|
|      [Rima Maharani Lubis]      | [231401015] |


## b. Deskripsi Proyek

Anime-Verse adalah aplikasi mobile berbasis Android yang dibangun menggunakan Flutter. Aplikasi ini bertujuan untuk menjadi platform bagi para penggemar anime untuk menemukan, melacak, dan mendiskusikan anime favorit mereka. Dengan integrasi Firebase, aplikasi ini menyediakan fitur autentikasi pengguna, penyimpanan data real-time, dan fitur sosial lainnya untuk menciptakan komunitas yang interaktif.

### Fitur Utama
*   Autentikasi Pengguna: Sistem registrasi dan login yang aman menggunakan Firebase Authentication, memungkinkan pengguna memiliki akun pribadi.
*   Eksplorasi Anime: Menampilkan daftar anime populer, yang sedang tayang, dan yang akan datang untuk membantu pengguna menemukan tontonan baru.
*   Pencarian Lanjutan: Fitur pencarian yang memungkinkan pengguna mencari anime berdasarkan judul.
*   Detail Informasi: Halaman detail untuk setiap anime yang menyajikan sinopsis, genre, rating, jumlah episode, dan studio produksi.
*   Favorite: Pengguna dapat menambahkan anime ke daftar "Favorite" pribadi untuk melacak tontonan yang paling disukai.
*   Profil Pengguna: Halaman profil yang menampilkan informasi pengguna dan daftar anime favorit mereka.

### Teknologi yang Digunakan
*   Framework: Flutter
*   Bahasa Pemrograman: Dart
*   Backend & Database: Firebase (Authentication, Cloud Firestore)
*   Manajemen State: setState (Flutter's built-in state management)
*   Routing: go_router
*   API: Jikan API (untuk data anime)


## c. Screenshot Aplikasi

Berikut adalah tampilan dari beberapa halaman utama aplikasi Anime-Verse.

| Sign Up Screen | Sign In Screen | Home Screen |
| :---: | :---: | :---: |
| ![Sign Up Screen](https://github.com/rimamaharanilubis/anime-verse/blob/main/assets/screenshots/singup_screen.jpg?raw=true) | ![Sign In Screen](https://github.com/rimamaharanilubis/anime-verse/blob/main/assets/screenshots/singin_screen.jpg?raw=true) | ![Home Screen](https://github.com/rimamaharanilubis/anime-verse/blob/main/assets/screenshots/home_screen.jpg?raw=true) |
| *Detail Screen* | *Favorite Screen* | *Profile Screen* |
| ![Detail Screen](https://github.com/rimamaharanilubis/anime-verse/blob/main/assets/screenshots/detail_screen.jpg?raw=true) | ![Favorite Screen](https://github.com/rimamaharanilubis/anime-verse/blob/main/assets/screenshots/favorite_screen.jpg?raw=true) | ![Profile Screen](https://github.com/rimamaharanilubis/anime-verse/blob/main/assets/screenshots/profile_screen.jpg?raw=true) |


## d. Link Demo Aplikasi

Anda dapat melihat demo aplikasi melalui link video di bawah ini. Video ini mendemonstrasikan seluruh fungsionalitas utama dari aplikasi Anime-Verse.

**[Link Demo Aplikasi](https://drive.google.com/drive/folders/1nuA1EgSCSIwpoqEegyoalcYVwD5Ak1FE)**


### Cara Menjalankan Proyek

Untuk menjalankan proyek ini di lingkungan pengembangan lokal, ikuti langkah-langkah berikut:

1.  Prasyarat:
    *   Pastikan Anda sudah menginstal [Flutter SDK](https://flutter.dev/docs/get-started/install).
    *   Konfigurasi editor kode Anda (misalnya, VS Code atau Android Studio) dengan plugin Flutter.
    *   Pastikan Anda memiliki emulator Android yang berjalan atau perangkat fisik yang terhubung.

2.  Kloning Repositori:

3.  Setup Firebase:
    *   Proyek ini memerlukan file konfigurasi Firebase. Buat proyek baru di [Firebase Console](https://console.firebase.google.com/).
    *   Tambahkan aplikasi Android dengan nama paket com.example.anime_verse.
    *   Unduh file google-services.json dan letakkan di dalam direktori android/app/.

4.  Instal Dependensi: