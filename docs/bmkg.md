# BMKG Indonesia

Menampilkan data resmi BMKG untuk gempa, prakiraan cuaca tiga hari, dan peringatan dini. Tiga menu memiliki alur yang berbeda.

## Gempa

1. Pilih **Gempa**.
2. Tunggu data gempa terkini atau yang dirasakan.
3. Baca waktu, magnitudo, kedalaman, lokasi, dan keterangan yang tersedia.
4. Periksa waktu pembaruan serta tautan sumber BMKG.

Magnitudo dan intensitas yang dirasakan bukan istilah yang sama. Gunakan penjelasan sumber ketika membutuhkan keputusan berdasarkan data gempa.

## Cuaca: membutuhkan kode ADM4

1. Pilih **Cuaca**.
2. Isi **kode wilayah ADM4**, yaitu kode desa/kelurahan dalam format **XX.XX.XX.XXXX**.
3. Tekan **Lihat prakiraan**.
4. Pastikan nama desa/kelurahan yang muncul benar.
5. Baca prakiraan per waktu untuk tiga hari.

Contoh resmi yang dicantumkan antarmuka: **31.71.03.1001 untuk Kemayoran**. Ini contoh untuk mengenali format, bukan otomatis lokasi tempatmu berada.

Jika belum tahu kode wilayahmu, gunakan **Panduan resmi** yang tersedia pada formulir. Mengetik “Jakarta” atau nama kota saja ke kolom kode tidak mengikuti format yang diminta.

## Peringatan

1. Pilih **Peringatan**.
2. Baca daftar nowcast atau peringatan yang sedang dikembalikan feed.
3. Perhatikan wilayah, waktu, dan keterangan.
4. Buka **Detail BMKG** untuk informasi sumber.

Tidak ada peringatan pada feed saat diperiksa bukan jaminan cuaca akan selalu aman. Data dapat berubah, sehingga waktu pembaruan perlu dibaca.

## Kendala dan hasil

Kode terakhir dapat diingat browser agar pencarian cuaca lebih mudah. Data juga dapat memakai cache untuk mengurangi permintaan.

Jika kode ditolak, periksa pola titik dan jumlah angkanya. Jika nama wilayah hasil salah, ganti dengan kode yang benar. Jika sumber tidak tersedia, coba lagi setelah layanan pulih; tool tidak mengarang prakiraan pengganti.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/bmkg-open-data.js) · [Daftar semua tool](README.md)
