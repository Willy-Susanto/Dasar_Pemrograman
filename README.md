# 💻 Dasar Pemrograman dengan C

![Language](https://img.shields.io/badge/Language-C-blue.svg)
![Compiler](https://img.shields.io/badge/Compiler-GCC-orange.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)

Repositori ini berisi catatan materi, studi kasus, dan implementasi kode praktikum **Dasar Pemrograman** menggunakan bahasa C. Disusun secara berurutan mulai dari konsep dasar sekuensial hingga manipulasi tipe data terstruktur (*struct*).

---

## 📚 Daftar Modul

| No | Direktori | Materi Pokok | Cakupan Bahasan |
|:---:|:---|:---|:---|
| **01** | `01_Tipe_Data_Penamaan_dan_Sekuens/` | **Tipe Data & Sekuens** | Tipe data primitif, aturan penamaan variabel/konstanta, I/O (`printf`, `scanf`), alur sekuensial |
| **02** | `02_Pemilihan/` | **Percabangan** | Logika kontrol keputusan: `if`, `if-else`, *nested if*, dan `switch-case` |
| **03** | `03_Perulangan/` | **Perulangan (*Looping*)** | Struktur perulangan terhitung dan kondisional: `for`, `while`, `do-while`, serta *nested loop* |
| **04** | `04_Prosedur/` | **Prosedur & Pointer** | Fungsi `void`, parameter formal/aktual, *scope*, konsep pointer, *pass by value* vs *pass by reference* |
| **05** | `05_Fungsi/` | **Fungsi (*Function*)** | Subprogram dengan nilai kembalian (*return value*) dan rekursi dasar |
| **06** | `06_Array/` | **Array 1 Dimensi** | Alokasi memori larik, inisialisasi, traversal, serta operasi manipulasi data |
| **07** | `07_Record/` | **Struktur Data (*Struct*)** | Tipe data bentukan, deklarasi `struct`, `typedef`, dan pengaksesan *member*/*field* |
| **08** | `08_Array_Of_Record/` | **Array of Struct** | Pengelolaan kumpulan entitas terstruktur untuk pemrosesan data tabel/rekaman |

---

## 📂 Struktur Repositori

```text
DasarPemrograman-C/
├── 01_Tipe_Data_Penamaan_dan_Sekuens/
├── 02_Pemilihan/
├── 03_Perulangan/
├── 04_Prosedur/
├── 05_Fungsi/
├── 06_Array/
├── 07_Record/
├── 08_Array_Of_Record/
└── README.md

## 🚀 Cara Jalankan
 
Pastikan sudah ada **GCC** di sistem kamu, lalu:
 
```bash
cd 04_Pemilihan
gcc main.c -o main
./main
```
