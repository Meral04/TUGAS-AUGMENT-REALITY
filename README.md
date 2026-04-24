# TUGAS-AUGMENT-REALITY
Moh. Rifki Almahdi (232410102023)


LINK YT : https://youtu.be/_5thN6-2UaA

Aplikasi ini merupakan implementasi Augmented Reality (AR) berbasis marker menggunakan Unity dan Vuforia.
Ketika kamera diarahkan ke marker (poster yang telah dibuat), maka akan muncul objek bola sepak 3D secara realtime di atas marker.

Marker yang Digunakan
Marker berupa desain poster bertema sepak bola.
Fitur marker:
1. Memiliki banyak detail visual
2. Kontras tinggi
3. Mudah dikenali oleh Vuforia

Tools & Teknologi
1. Unity 2022.3 LTS
2. Vuforia Engine
3. Visual Studio
4. Asset 3D (bola sepak)

Cara Menjalankan Project
1. Ambil dari folder drive saya : https://drive.google.com/drive/folders/1np6SJk2dVb_zHScTU1T9WVIpjzFJTiLk?usp=sharing
2. Buka Project di Unity
Buka Unity Hub
Klik Open Project
Pilih folder project
3. Setup Vuforia
Masuk ke Vuforia Developer
Buat License Key
Masukkan License Key ke:
AR Camera → Vuforia Configuration
4. Import Database Marker
Download database marker dari Vuforia
Import ke Unity:
Assets → Import Package → Custom Package
5. Setup Scene AR
Hapus Main Camera
Tambahkan:
AR Camera
Image Target
Pilih:
Database → marker yang dibuat
Image Target → gambar marker
6. Menambahkan Objek 3D (Bola)
Import model bola 3D ke Unity
Drag objek bola ke dalam Image Target
Atur:
Position
Scale
Rotation

Hasil:
Objek bola akan muncul di atas marker saat terdeteksi kamera.

7. Jalankan Aplikasi

Klik tombol Play di Unity.

Arahkan kamera ke marker → bola 3D akan muncul.
