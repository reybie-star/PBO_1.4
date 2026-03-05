# 🚗 Simulasi Sistem Kendaraan (Python OOP)

Program sederhana berbasis Python untuk mendemonstrasikan konsep dasar **Pemrograman Berorientasi Objek (OOP)** dan **Handling Error** menggunakan *Inheritance* (Pewarisan) serta *Try-Except*.

## 📌 Fitur Utama
* **Inheritance**: Menggunakan class induk `Kendaraan` dan class turunan `Mobil` serta `Truk`.
* **Super() Method**: Memanggil konstruktor dari class induk untuk efisiensi kode.
* **Error Handling**: Validasi input muatan barang menggunakan `try-except` untuk mencegah *crash*.
* **Custom Logic**: Logika pengecekan kapasitas maksimal pada objek Truk.

---

## 🏗️ Struktur Class



1.  **Kendaraan (Parent)**:
    * Atribut: `merek`, `model`.
    * Method: `berkendara()`.
2.  **Mobil (Child)**:
    * Atribut Tambahan: `jumlah_pintu`.
    * Method Tambahan: `klakson()`.
3.  **Truk (Child)**:
    * Atribut Tambahan: `kapasitas_muatan`.
    * Method Tambahan: `muat_barang()` (dengan sistem validasi berat).

---

## 🚀 Cara Menjalankan
1. Pastikan Anda sudah menginstal Python (versi 3.x direkomendasikan).
2. Simpan kode ke dalam file bernama `kendaraan.py`.
3. Jalankan melalui terminal atau command prompt:
   ```bash
   python kendaraan.py
