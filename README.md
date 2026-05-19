# Implementasi UI Katalog Produk dengan Flutter

## Deskripsi Project
Project ini merupakan implementasi User Interface (UI) katalog produk menggunakan framework Flutter.  
Tampilan dibuat berdasarkan referensi desain yang diberikan pada tugas dengan menerapkan widget fundamental Flutter seperti:

- Column
- Row
- ListView
- Image

Project ini menampilkan:
- Search bar
- Daftar kategori produk horizontal
- Grid katalog produk
- Informasi harga dan diskon produk

---

# Screenshot Aplikasi

Tambahkan screenshot aplikasi kalian di sini.

Contoh:

![Screenshot App](assets/screenshot.png)

---

# Widget yang Digunakan

## 1. Column
Digunakan untuk menyusun widget secara vertikal.

Contoh:
```dart
Column(
  children: [
    searchBar(),
    categoryList(),
    productGrid(),
  ],
)
