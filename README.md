# Laporan Praktikum - Pemrograman Web

*Nama Repository:* Lab2Web  
*Mata Kuliah:* Pemrograman Web  
*Kampus:* Universitas Pelita Bangsa  

---

## 1. Langkah-langkah Praktikum

### A. Membuat File HTML dan CSS Dasar (lab2_css_dasar.html)
- Membuat file lab2_css_dasar.html yang berisi struktur dasar HTML, elemen navigasi, header, dan div intro.
- Menambahkan *Inline CSS* pada elemen header (<h1 style="color: blue;">).
- Menambahkan *Internal CSS* di dalam tag <style> pada bagian <head> untuk mengatur ID Selector (#merah, #serif, #rata-tengah, #intro) dan Class Selector (.button).

### B. Membuat File CSS Eksternal (style.css)
- Membuat file terpisah bernama style.css untuk menyimpan seluruh aturan styling agar kode lebih rapi dan modular.
- Mengatur tampilan font, margin, warna latar belakang, styling tombol, dan efek hover.

### C. Menghubungkan CSS Eksternal (lab2_css_eksternal.html)
- Membuat file lab2_css_eksternal.html dan menghubungkannya ke style.css menggunakan tag <link rel="stylesheet" href="style.css">.

---

## 2. Screenshot Perubahan dan Hasil

(Silakan unggah/tempel gambar screenshot hasil tampilan halaman web Anda di bawah ini)

![Screenshot Tampilan CSS Dasar](masukkan_link<img width="960" height="600" alt="Screenshot 2026-10-11 010043" src="https://github.com/user-attachments/assets/a5341c7d-a8b7-45d7-8a28-d66d2fff92c1" />
_gambar_di_sini)

---

## 3. Jawaban Pertanyaan dan Tugas

1. *Eksperimen CSS:*  
   Properti dan nilai CSS telah ditambahkan dan disesuaikan menggunakan acuan CSS Cheat Sheet.

2. *Perbedaan h1 {...} dan #intro h1 {...}:*  
   - h1 {...} bersifat *global*, yaitu menerapkan style ke seluruh elemen <h1> yang ada pada halaman.
   - #intro h1 {...} bersifat *spesifik (turunan)*, yaitu hanya menerapkan style pada elemen <h1> yang berada di dalam elemen bersangkutan yang memiliki id="intro".

3. *Prioritas Deklarasi CSS (Internal vs Eksternal vs Inline):*  
   - *Inline CSS* yang akan ditampilkan oleh browser karena memiliki tingkat prioritas (cascade priority) paling tinggi dibanding Internal maupun Eksternal CSS.

4. *Prioritas Antara ID Selector dan Class Selector:*  
   - Deklarasi dari *ID Selector* yang akan ditampilkan oleh browser karena nilai spesifisitas (specificity score) ID Selector lebih tinggi daripada Class Selector.
