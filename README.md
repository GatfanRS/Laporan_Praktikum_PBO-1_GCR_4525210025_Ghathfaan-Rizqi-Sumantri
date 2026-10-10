Sesi 1: Objek Pertama Anda (Java & PHP)

Repositori ini berisi latihan dasar pemrograman berorientasi objek (OOP) dalam dua bahasa pemrograman: Java dan PHP. Latihan ini dirancang untuk memperkenalkan konsep fundamental seperti kelas (class), objek (object), atribut/properti, constructor, enkapsulasi (private), dan penggunaan referensi objek (this / $this).

Disusun oleh: Ghathfaan Rizqi Sumantri (NPM: 4525210025)

Struktur Berkas

HaloObjek.java — Kode sumber latihan berbasis Java.

halo_objek.php — Padanan kode sumber latihan berbasis PHP.

Konsep Utama yang Dipelajari

Deklarasi Kelas dan Pembuatan Objek: Membedakan antara cetak biru (blueprint / class) dengan instansiasi objek nyata menggunakan kata kunci new.

Atribut / Properti Privat: Menerapkan enkapsulasi dengan menyembunyikan data internal agar tidak dapat diakses secara sembarangan dari luar kelas.

Konstruktor dan Kata Kunci this: Cara menginisialisasi nilai awal saat objek dibuat serta membedakan antara parameter fungsi dan atribut/properti milik objek.

Cakupan Method: Bagaimana sebuah method yang ditulis satu kali dapat menghasilkan keluaran dinamis berdasarkan data unik milik masing-masing objek.

Cara Kompilasi dan Menjalankan Program

1. Java (HaloObjek.java)

Pastikan komputer Anda sudah terpasang Java Development Kit (JDK).

# Kompilasi kode ke dalam direktori out
javac -d out HaloObjek.java

# Jalankan program
java -cp out HaloObjek


2. PHP (halo_objek.php)

Pastikan komputer Anda sudah terpasang PHP versi 8.0 atau yang lebih baru (mendukung declare(strict_types=1)).

# Jalankan program secara langsung via CLI
php halo_objek.php


Pertanyaan Refleksi

Baris mana yang membuat objek dan mana yang mendeklarasikan kelas?

Apa perbedaan penggunaan operator akses (titik . pada Java vs panah -> pada PHP)?

Mengapa method sapa() menghasilkan teks yang berbeda untuk setiap objek?