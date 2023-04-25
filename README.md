# LP7DPBO2023

> Saya Achmad Fauzam NIM 2108061 mengerjakan soal Latihan Praktikum 7
dalam mata kuliah Desain dan Pemrograman Berorientasi Objek
untuk keberkahanNya maka saya tidak melakukan kecurangan
seperti yang telah dispesifikasikan. Aamiin.

## Alur Program
- Player dapat menggerakan sebuah bola dengan menekan tombol `W` `A` `S` `D` atau `⬆` `⬅` `⬇` `➡`
- Setiap kali player berganti arah, maka score akan bertambah 1
- Terdapat sebuah objek Kotak di dalam game. Jika player menyentuh kotak tersebut, maka score akan bertambah 10

## Perbedaan dari template project Synchronization
- Menambahkan sebuah class baru yaitu Target sebagai representasi model dari objek kotak, class Target merupakan anak dari class GameObject
- Mengganti pemanggilan method setScore pada class Controller, method hanya akan dipanggil apabila key yang ditekan berbeda dari key sebelumnya
- Menambahkan method static "isOverlapping()" pada class Handler untuk menentukan apakah dua GameObject saling bersentuhan atau tidak
- Menambahkan kondisi pada method "loop()" dari class Game, dimana jika Player dan Target saling bersentuhan maka method "moveRandom()" milik Target akan dipanggil

## Demo Program
https://user-images.githubusercontent.com/91662639/234273954-143ab28b-0ab7-4b7f-bca0-c5e6366c2a9d.mp4
