# Pertemuan 04 Seleksi Multi-Kondisi dan Validasi Input

Nama: Elga Greena Rahma Tazkia
NIM: 2225250049
Kelas: 3B

## Tujuan

Membangun program dengan seleksi multi-kondisi menggunakan if-elif-else serta melakukan validasi tipe dan rentang input.

## Cara Menjalankan

Untuk menjalankan latihan:

    python latihan/01_predikat_nilai.py

Untuk menjalankan praktik utama:

    python praktik/validasi_klasifikasi_nilai.py

## Tabel Keputusan

| Kondisi | Hasil |
|---|---|
| Nilai akhir >= 85 | Predikat A |
| Nilai akhir >= 70 dan < 85 | Predikat B |
| Nilai akhir >= 60 dan < 70 | Predikat C |
| Nilai akhir >= 50 dan < 60 | Predikat D |
| Nilai akhir < 50 | Predikat E |
| Kehadiran < 80% | Tidak memenuhi syarat kehadiran |
| Predikat A, B, atau C | Lulus |
| Predikat D atau E | Belum lulus |

## Hasil Pengujian

| No | Nilai Ujian | Nilai Tugas | Kehadiran | Hasil |
|---|---:|---:|---:|---|
| 1 | 90 | 80 | 95 | 86.00, A, Lulus |
| 2 | 75 | 70 | 85 | 73.00, B, Lulus |
| 3 | 60 | 60 | 80 | 60.00, C, Lulus |
| 4 | 55 | 50 | 90 | 53.00, D, Belum lulus |
| 5 | 40 | 30 | 100 | 36.00, E, Belum lulus |
| 6 | 90 | 90 | 75 | Tidak memenuhi syarat kehadiran |
| 7 | 105 | 80 | 90 | Input nilai ujian ditolak |
| 8 | 80 | -5 | 90 | Input nilai tugas ditolak |
| 9 | 80 | 80 | abc | Input ditolak karena bukan angka |

## Refleksi

Pada latihan ini saya belajar bahwa validasi input perlu dilakukan sebelum data digunakan dalam perhitungan. Saya juga memahami bahwa kondisi kehadiran harus diperiksa sebelum menentukan predikat, karena kehadiran di bawah 80% langsung membuat mahasiswa tidak memenuhi syarat.