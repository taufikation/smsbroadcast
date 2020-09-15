# smsbroadcast
- menggunakan database Mysql
- API yang dipakai hanya method POST yang dimaksudkan untuk mengisi data
  inbox (uuid, no_kirim, teks) 
  uuid untuk key yang terdaftar di server
  no_kirim : nomor tujuan pengiriman
  teks : isi dari sms yang ingin di kirim
- di dalam data inbox nanti dikirimkan sms ke nomor tujuan oleh SMS Gateway C#

## langkah berikutnya
- data yang sudah terkirim dan berhasil dimasukkkan ke outbox
- mengambil perhitungan laporan data  yang terkirim masih belum dikerjakan di tahap ini
