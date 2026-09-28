# Pertemuan 05 Perulangan Python

Nama: Alfitrah Zahra Ameliya
NIM: 2225250181
Kelas: 3B

## Tujuan
Menggunakan for dan while untuk menyelesaikan masalah iteratif.

## Cara Menjalankan
python3 kuis/kuis2_deret_aritmetika.py

## Algoritma Kuis 2
1. Memasukkan nilai suku pertama a, beda d, dan banyak suku n.
2. Memeriksa nilai n menggunakan while. Jika n kurang dari atau sama dengan 0, input n diminta kembali sampai bernilai positif.
3. Menginisialisasi total = 0 sebelum perulangan.
4. Menggunakan for untuk mengulang sebanyak n kali.
5. Menghitung setiap suku dengan a + i * d.
6. Menambahkan setiap suku ke dalam total.
7. Menampilkan setiap suku dan jumlah seluruh suku.

## Hasil Pengujian

| Test Case | Input | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|---|
| 1 | a=2, d=3, n=5 | Suku: 2.00, 5.00, 8.00, 11.00, 14.00; Jumlah=40.00 | Suku: 2.00, 5.00, 8.00, 11.00, 14.00; Jumlah=40.00 | Berhasil |
| 2 | a=10, d=-2, n=4 | Suku: 10.00, 8.00, 6.00, 4.00; Jumlah=28.00 | Suku: 10.00, 8.00, 6.00, 4.00; Jumlah=28.00 | Berhasil |
| 3 | a=1.5, d=0.5, n=3 | Suku: 1.50, 2.00, 2.50; Jumlah=6.00 | Suku: 1.50, 2.00, 2.50; Jumlah=6.00 | Berhasil |
| 4 | a=2, d=3, n=0, kemudian n=5 | n=0 ditolak dan diminta input ulang; setelah n=5, Jumlah=40.00 | n=0 ditolak dan diminta input ulang; setelah n=5, Jumlah=40.00 | Berhasil |

## Refleksi
Kesalahan yang ditemukan adalah nilai n = 0 tidak dapat digunakan sebagai jumlah suku karena jumlah suku harus berupa bilangan bulat positif. Perbaikannya adalah menggunakan while untuk memeriksa nilai n dan meminta input kembali jika n kurang dari atau sama dengan 0. Setelah n bernilai positif, perulangan for dapat dijalankan sesuai jumlah suku yang dimasukkan.