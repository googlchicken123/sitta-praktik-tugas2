# SITTA – Tugas Praktik 2 
Disusun oleh: Reza Rinaldi
NIM: 050601026
UPJJ: Surabaya
Program Studi: Sistem Informasi

**Pemrograman Berbasis Web – STSI4209**  
Universitas Terbuka  

Tugas Praktik 2 ini merupakan pengembangan lanjutan dari Tugas Praktik 1 dengan fokus utama pada penerapan **Vue.js** sebagai framework front-end untuk menghasilkan tampilan interaktif, dinamis, dan terstruktur pada aplikasi pemesanan bahan ajar SITTA UT.

---

## Tujuan Pembelajaran

Pada tugas ini mahasiswa diharapkan mampu:

- Menerapkan **struktur project** menggunakan Vue.js.
- Menggunakan **data binding** (`{{ }}`, `v-text`, `v-model`, `v-bind`).
- Mengimplementasikan **conditional rendering** (`v-if`, `v-else`, `v-show`).
- Menggunakan **list rendering** (`v-for`) untuk menampilkan data.
- Menerapkan **computed properties** dan **methods**.
- Menggunakan **watchers** untuk memantau perubahan data.
- Membuat **form input**, validasi, dan event handling.
- Mendesain UI/UX aplikasi agar informatif serta mudah digunakan.

---

## 1. Halaman Stok Bahan Ajar (stok.html)

Halaman ini menampilkan daftar lengkap bahan ajar menggunakan Vue.js dengan data dummy.
- Menampilkan tabel stok (kode, judul, kategori, lokasi, qty, safety, status, catatan).
- Filter:
  - Filter UT-Daerah.
  - Filter kategori mata kuliah.
  - Filter stok menipis/kosong.
- Sorting:
  - Berdasarkan judul, stok, harga.
- Form tambah & edit stok menggunakan **SweetAlert2**.
- Validasi input form.
- Status stok otomatis:
  - **Aman** → hijau.
  - **Menipis** → orange (warning).
  - **Kosong** → merah.
- Watcher untuk perubahan filter dan perhitungan dinamis.

---

## 2. Halaman Tracking Delivery Order (tracking.html)

Digunakan untuk mencatat pengiriman DO berdasarkan input pengguna.
- Nomor DO otomatis dengan format:  
  **DOYYYY-XXX**
- Form input lengkap:
  - NIM  
  - Nama  
  - Ekspedisi  
  - Paket Bahan Ajar  
  - Tanggal Kirim  
- Total harga otomatis.
- List DO menggunakan Vue list rendering.

---

## Fitur yang Digunakan

- **Vue.js CDN**
- HTML5 + CSS3
- JavaScript murni
- SweetAlert2 (modals)
- Dummy data dari dosen sebagai dasar Vue rendering

---

## Status Pengembangan

- Stok bahan ajar: **Selesai**
- Tracking DO: **Selesai**
- Histori transaksi: **Placeholder (maintenance mode)**
- Vue.js sudah diterapkan pada seluruh alur inti.

---

## Penutup
Sekian penjelasan yang dapat saya sampaikan.  
Mohon maaf apabila terdapat kesalahan dalam penulisan maupun penjelasan.  
Terima kasih.

---
