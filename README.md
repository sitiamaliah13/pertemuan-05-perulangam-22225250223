# Pertemuan 05 Perulangan Python

**Nama:** Siti Amaliah
**NIM:** 2225250223
**Kelas:** 3E

## Tujuan

Mempelajari dan menggunakan perulangan `for` dan `while` dalam Python untuk menyelesaikan masalah iteratif. Selain itu, melakukan pengujian program, tracing perubahan variabel, dan mengunggah hasil pekerjaan ke GitHub.

## Struktur Program

Program pada Pertemuan 05 terdiri dari:

* `01_tabel_perkalian.py` untuk menampilkan tabel perkalian 1 sampai 10.
* `02_jumlah_bilangan.py` untuk menghitung jumlah bilangan 1 sampai n.
* `03_validasi_input.py` untuk melakukan validasi nilai ujian 0 sampai 100.
* `04_hitung_genap.py` untuk menghitung banyak bilangan genap dari 1 sampai n.
* `kuis2_deret_aritmetika.py` untuk menampilkan suku deret aritmetika dan menghitung jumlahnya.

## Cara Menjalankan

Program dapat dijalankan melalui terminal VS Code menggunakan perintah:

```bash
python latihan/01_tabel_perkalian.py
python latihan/02_jumlah_bilangan.py
python latihan/03_validasi_input.py
python latihan/04_hitung_genap.py
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

1. Memasukkan suku pertama `a`.
2. Memasukkan beda `d`.
3. Memasukkan banyak suku `n`.
4. Memvalidasi `n` menggunakan `while` sampai bernilai positif.
5. Mengatur `total = 0`.
6. Menggunakan `for` untuk mengulang sebanyak `n` kali.
7. Menghitung setiap suku dengan `a + i * d`.
8. Menambahkan setiap suku ke dalam `total`.
9. Menampilkan setiap suku dan jumlah akhir deret.

## Hasil Pengujian

| Program          | Test Case         | Hasil    |
| ---------------- | ----------------- | -------- |
| Tabel Perkalian  | n = 4             | Berhasil |
| Tabel Perkalian  | n = -3            | Berhasil |
| Jumlah Bilangan  | n = 1             | Berhasil |
| Jumlah Bilangan  | n = 5             | Berhasil |
| Jumlah Bilangan  | n = 10            | Berhasil |
| Validasi Input   | 120, -5, 75       | Berhasil |
| Hitung Genap     | n = 1, 2, 5, 10   | Berhasil |
| Deret Aritmetika | a=2, d=3, n=5     | Berhasil |
| Deret Aritmetika | a=10, d=-2, n=4   | Berhasil |
| Deret Aritmetika | a=1.5, d=0.5, n=3 | Berhasil |

## Refleksi

Pada latihan ini saya mempelajari bahwa `for` sesuai digunakan ketika jumlah perulangan sudah diketahui, sedangkan `while` digunakan ketika perulangan bergantung pada suatu kondisi. Saya juga belajar bahwa variabel kontrol pada `while` harus diperbarui agar kondisi dapat menjadi `False` dan program tidak mengalami infinite loop.

Selain itu, saya memahami bahwa variabel akumulator seperti `total` harus diinisialisasi sebelum perulangan agar nilainya tidak terus direset pada setiap iterasi.

## Kesimpulan

Pertemuan 05 membantu saya memahami penggunaan `for`, `while`, `if` di dalam perulangan, akumulasi, pencacahan, validasi input, serta pengujian program menggunakan beberapa test case.

**Status:** Seluruh program dan test case telah diuji dan berhasil dijalankan.