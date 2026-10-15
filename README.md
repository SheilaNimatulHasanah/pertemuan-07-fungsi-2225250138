# Pertemuan 07 Fungsi Python

Nama: Sheila Ni'matul Hasanah
NIM: 2225250138
Kelas: 3B

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
python3 praktik/utilitas_matematika.py

## Struktur Fungsi
- `luas_persegi_panjang(p, l)`: Menghitung luas persegi panjang.
- `luas_segitiga(a, t)`: Menghitung luas segitiga.
- `jumlah_n(n)`: Menghitung total deret angka 1 sampai n.
- `faktorial(n)`: Menghitung nilai faktorial secara iteratif.
- `tampilkan_menu()`: Menampilkan antarmuka menu pilihan operasi.

## Hasil Pengujian
- Luas Persegi Panjang (p=8, l=5) -> Expected: 40 | Actual: 40 (Berhasil)
- Luas Segitiga (a=10, t=6) -> Expected: 30.0 | Actual: 30.0 (Berhasil)
- Jumlah 1..n (n=10) -> Expected: 55 | Actual: 55 (Berhasil)
- Faktorial (n=5) -> Expected: 120 | Actual: 120 (Berhasil)

## Refleksi
Pemisahan rumus matematika ke dalam fungsi khusus membuat program utama (`utilitas_matematika.py`) menjadi jauh lebih bersih, terstruktur, mudah diuji secara terpisah, serta terhindar dari pengulangan kode yang tidak perlu.