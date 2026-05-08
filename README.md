# UTS Mobile Programming - Aplikasi Workshop Kampus

Dokumentasi ini dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah **Mobile Programming** yang diampu oleh **Ade Putra Prima Suhendri, S.Kom, M.Kom.**

## Deskripsi Proyek
Aplikasi ini merupakan prototipe halaman utama untuk sistem pendaftaran Workshop Kampus. Fokus utama dari proyek ini adalah implementasi *Layouting* Flutter yang rapi, informatif, dan memiliki pengalaman pengguna (UX) yang baik.

### Fitur Utama:
* **Daftar Workshop Dinamis:** Menggunakan `ListView` untuk menampilkan daftar kartu workshop.
* **Informasi Terstruktur:** Setiap kartu menampilkan Judul, Tanggal, Lokasi, dan Sisa Kuota.
* **Responsif:** Tata letak disesuaikan agar nyaman dibaca di berbagai ukuran layar smartphone.

## Teknologi yang Digunakan
* **Framework:** Flutter
* **Bahasa Pemrograman:** Dart
* **IDE:** Visual Studio Code

## Struktur Folder (Bagian Penting)
Karena repositori ini hanya menyertakan folder `lib`, berikut adalah rincian isinya:
* `lib/main.dart`: Berisi logika utama aplikasi, definisi tema, serta implementasi `WorkshopScreen`.

## Cara Menjalankan Proyek
Jika Anda ingin mencoba menjalankan kode ini namun hanya memiliki folder `lib`, ikuti langkah-langkah berikut:

1.  Buat proyek Flutter baru di VS Code:
    `Ctrl + Shift + P` -> `Flutter: New Project` -> `Application`.
2.  Beri nama proyek tersebut (contoh: `uts_workshop_app`).
3.  Buka folder proyek baru tersebut, lalu cari folder bernama `lib`.
4.  Ganti isi file `main.dart` bawaan dengan isi file `main.dart` yang ada di repositori ini.
5.  Jalankan aplikasi dengan menekan **F5** (pastikan emulator atau device sudah terhubung).

## Konsep UI/UX
Dalam mengerjakan Soal 1 dan 2 pada UTS, saya menerapkan beberapa prinsip berikut:
* **Chunking:** Membagi informasi ke dalam `Card` agar data tidak terlihat menumpuk.
* **Visual Hierarchy:** Menggunakan teks tebal (Bold) pada judul workshop untuk menarik perhatian utama pengguna.
* **Whitespace:** Memberikan padding yang cukup di setiap sisi agar konten "bernafas" dan mudah dibaca.

---
**Disusun oleh:**
[Rafi Musyaffa Ahmad]
*Mahasiswa Teknik Informatika - Universitas Pamulang*
