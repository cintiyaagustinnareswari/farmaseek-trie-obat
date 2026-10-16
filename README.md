# FarmaSeek — Aplikasi Pencarian Obat Berbasis Trie

## Deskripsi Proyek

FarmaSeek adalah aplikasi desktop berbasis Python yang digunakan untuk mencari informasi obat berdasarkan awalan nama obat atau gejala penyakit. Aplikasi ini menerapkan struktur data Trie (*Prefix Tree*) untuk membantu proses pencarian string secara efisien.

Aplikasi dilengkapi dengan antarmuka grafis menggunakan Tkinter. Pengguna dapat mencari obat, melihat informasi detail obat, dan melihat visualisasi struktur Trie berdasarkan awalan yang dimasukkan.

Proyek ini dikembangkan sebagai implementasi materi Struktur Data dan Algoritma.

## Fitur Utama

1. **Pencarian berdasarkan nama obat**  
   Menampilkan daftar obat yang sesuai dengan awalan nama yang dimasukkan.

2. **Pencarian berdasarkan gejala atau penyakit**  
   Menampilkan nama obat berdasarkan awalan gejala yang tersedia dalam dataset.

3. **Informasi detail obat**  
   Menampilkan informasi seperti golongan, kategori, manfaat, pengguna, bentuk obat, dan gangguan yang berkaitan.

4. **Visualisasi struktur Trie**  
   Menampilkan representasi grafis struktur Trie menggunakan NetworkX dan Matplotlib.

5. **Antarmuka grafis**  
   Menyediakan halaman utama dan halaman pencarian agar aplikasi lebih mudah digunakan.

## Struktur Data dan Teknologi

| Komponen | Kegunaan |
|---|---|
| Python | Bahasa pemrograman |
| Trie (Prefix Tree) | Menyimpan dan mencari data berdasarkan awalan |
| Tkinter | Membuat antarmuka grafis |
| CSV | Menyimpan data obat |
| NetworkX | Membentuk graf untuk visualisasi Trie |
| Matplotlib | Menampilkan visualisasi struktur Trie |

## Dataset

Data obat disimpan dalam file CSV bernama `data obat baru fix.csv`.

Kolom informasi yang digunakan meliputi:

- Nama Obat
- Golongan
- Kategori
- Manfaat
- Pengguna
- Bentuk obat
- Gangguan

Data tersebut dimuat ke dalam dua struktur Trie, yaitu Trie untuk pencarian nama obat dan Trie untuk pencarian gejala atau gangguan.

**Catatan:** Data obat dalam proyek ini digunakan untuk demonstrasi pemrograman. Informasinya perlu diverifikasi melalui sumber medis resmi sebelum digunakan sebagai dasar keputusan pengobatan.

## Cara Kerja Aplikasi

1. Program membaca dataset obat dari file CSV.
2. Program membangun Trie berdasarkan nama obat dan gejala.
3. Pengguna memilih jenis pencarian pada halaman utama.
4. Pengguna memasukkan awalan kata kunci.
5. Sistem menelusuri Trie untuk menemukan data yang sesuai.
6. Hasil pencarian ditampilkan pada daftar.
7. Pengguna dapat memilih obat untuk melihat detail informasinya.
8. Pengguna dapat menampilkan visualisasi struktur Trie.

## Instalasi dan Menjalankan Program

### 1. Clone Repository

```bash
git clone https://github.com/USERNAME/farmaseek-trie-obat.git
cd farmaseek-trie-obat
```

Ganti `USERNAME` dengan nama akun GitHub pemilik repository.

### 2. Instal Dependensi

Pastikan Python sudah terpasang. Kemudian jalankan:

```bash
pip install networkx matplotlib
```

Tkinter umumnya sudah tersedia pada instalasi Python untuk Windows. Pada sistem operasi lain, instalasinya mungkin perlu dilakukan secara terpisah.

### 3. Siapkan File

Pastikan file berikut berada dalam folder yang sama:

```text
farmaseek-trie-obat/
├── README.md
├── FARMASEEK SHOW.py
└── data obat baru fix.csv
```

### 4. Jalankan Aplikasi

```bash
python "FARMASEEK SHOW.py"
```

Pastikan nama file CSV pada kode sesuai dengan nama file dataset yang digunakan.

## Kontributor

Proyek ini dikerjakan oleh Kelompok 7:

1. Putri Sofiyatus Salwa
2. Meida Rifa Alfiani
3. Cintiya Agustin Nareswari

## Informasi Akademik

- **Mata kuliah:** Struktur Data dan Algoritma
- **Program studi:** Sains Data
- **Universitas:** Universitas Negeri Surabaya
- **Kelas:** 2024 D

## Tujuan Pengembangan

Proyek ini bertujuan menerapkan struktur data Trie dalam aplikasi pencarian berbasis string serta menunjukkan penerapan konsep Struktur Data dan Algoritma melalui aplikasi desktop sederhana.
