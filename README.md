# 🛒 Aplikasi Kasir Java

Aplikasi kasir berbasis desktop yang dibangun menggunakan bahasa pemrograman **Java** dan dirancang untuk mempermudah proses transaksi penjualan, manajemen koneksi database, serta pratinjau struk/nota belanja secara efisien.

---

## 🚀 Fitur Utama

*   **Transaksi Penjualan:** Antarmuka intuitif untuk menginput barang, menghitung total belanja, dan mengelola kembalian uang secara otomatis.
*   **Koneksi Database Terintegrasi:** Dilengkapi dengan modul koneksi terpusat untuk menghubungkan aplikasi dengan sistem penyimpanan data.
*   **Pratinjau Transaksi:** Fitur *preview* struk kasir sebelum dicetak untuk memastikan keakuratan data belanja konsumen.

---

## 📂 Struktur Berkas Utama

Berikut adalah komponen kode utama yang menyusun aplikasi ini:

*   **`kasir.java` & `kasir.form`**: Berkas kode utama dan desain antarmuka (*Graphical User Interface*) untuk halaman transaksi kasir.
*   **`Koneksi.java`**: Modul penentu konfigurasi dan penghubung aplikasi ke database.
*   **`previewkasir.java` & `previewkasir.form`**: Berkas kode dan tampilan halaman pratinjau nota transaksi kasir.

---

## 🛠️ Prasyarat Sistem

Sebelum menjalankan proyek ini, pastikan perangkat Anda telah terpasang:
*   **Java Development Kit (JDK)** versi 8 atau yang lebih baru.
*   **IDE/Editor** pendukung seperti Apache NetBeans, Eclipse, atau VS Code (dengan ekstensi Java).
*   **Database Server** (misalnya MySQL/MariaDB) jika ingin mengaktifkan fitur penyimpanan data lewat `Koneksi.java`.

---

## 💻 Cara Menjalankan Aplikasi

1. **Clone Repositori:**
```bash
   git clone [https://github.com/MuhammadAmirN/Kasir_Java.git](https://github.com/MuhammadAmirN/Kasir_Java.git)
