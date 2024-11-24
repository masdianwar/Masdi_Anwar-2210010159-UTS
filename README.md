# Aplikasi Keuangan Pribadi

## Deskripsi Program
**Aplikasi Keuangan Pribadi** adalah aplikasi berbasis **GUI** yang dirancang untuk membantu pengguna mengelola keuangan mereka. Pengguna dapat menambahkan, mengubah, dan menghapus transaksi, serta melihat informasi keuangan seperti total pemasukan, pengeluaran, dan saldo. Aplikasi ini dibuat dengan menerapkan konsep **Pemrograman Berorientasi Objek (OOP)** dan menggunakan berbagai komponen GUI.

---

## Fitur-Fitur Utama

### 1. Tambah Transaksi
- Pengguna dapat menambahkan transaksi baru dengan memasukkan **kategori**, **jumlah**, dan **deskripsi transaksi**.
- Data transaksi ditampilkan dalam daftar (**JList**) dengan format:  
  `Kategori - Rp<jumlah> (<deskripsi>)`.

### 2. Ubah Transaksi
- Pengguna dapat memilih transaksi dari daftar, mengedit data transaksi (**kategori**, **jumlah**, atau **deskripsi**), dan memperbarui daftar.

### 3. Hapus Transaksi
- Pengguna dapat menghapus transaksi tertentu dari daftar dengan memilih transaksi yang ingin dihapus.

### 4. Ringkasan Keuangan
- Aplikasi secara otomatis menghitung dan menampilkan **ringkasan keuangan**, meliputi:
  - **Total Pemasukan**: Jumlah semua transaksi dengan nilai positif.
  - **Total Pengeluaran**: Jumlah semua transaksi dengan nilai negatif.
  - **Saldo**: Selisih antara pemasukan dan pengeluaran.

### 5. Antarmuka User-Friendly
- Aplikasi dirancang dengan antarmuka yang menarik dan mudah digunakan, menggunakan komponen seperti:
  - **JFrame**, **JPanel**, **JTextArea**, **JList**, **JButton**, dan lainnya.

### 6. Validasi Input
- **Input kategori dan jumlah tidak boleh kosong**.
- **Jumlah transaksi harus berupa angka yang valid**.
- Jika format input salah, aplikasi akan memberikan **pesan kesalahan** secara otomatis.

---

## Cara Kerja Aplikasi

### Alur Penggunaan

#### 1. Menambah Transaksi
1. Masukkan kategori di `txtKategori`.
2. Masukkan jumlah di `txtJumlah` (harus berupa angka).
3. Masukkan deskripsi (opsional) di `txtDeskripsi`.
4. Tekan tombol **"Tambah"**, dan transaksi akan muncul di daftar.

#### 2. Mengubah Transaksi
1. Pilih transaksi dari **JList**.
2. Edit data transaksi di kolom input.
3. Tekan tombol **"Ubah"** untuk memperbarui transaksi.

#### 3. Menghapus Transaksi
1. Pilih transaksi dari **JList**.
2. Tekan tombol **"Hapus"** untuk menghapus transaksi.

#### 4. Melihat Ringkasan Keuangan
- **Total pemasukan**, **pengeluaran**, dan **saldo** diperbarui secara otomatis setiap kali transaksi ditambah, diubah, atau dihapus.

---

## Validasi yang Diterapkan

1. **Jumlah Transaksi**: Hanya menerima input berupa angka (**integer atau desimal**).
2. **Kategori**: Tidak boleh kosong.
3. **Transaksi Harus Dipilih**: Tombol **"Ubah"** dan **"Hapus"** hanya aktif jika ada transaksi yang dipilih dari **JList**.

---

## Teknologi dan Library yang Digunakan

- **Java SE 8+**
- **Swing**: Untuk GUI.
- **NetBeans IDE**: Untuk pengembangan.

---

## Screen Shot
   ![uang](https://github.com/user-attachments/assets/426fa225-284e-4971-a334-4909bbbc5047)
