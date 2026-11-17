# Nexora Web Intelligence

Memeriksa website dari sisi SEO, keamanan, performa, aksesibilitas, dan teknologi yang dapat dikenali. Gunakan untuk mengetahui bagian yang perlu ditinjau, bukan sebagai sertifikat bahwa situs sepenuhnya aman.

## Cara pakai

1. Isi alamat website pada kolom **SCAN WEBSITE**.
2. Pilih **Standard Scan** untuk percobaan pertama.
3. Tekan **SCAN WEBSITE**.
4. Tunggu laporan atau pesan kegagalan.
5. Buka tab Overview, Findings, SEO, Security, Speed, dan Stack.
6. Mulai dari temuan prioritas, lalu periksa detailnya.

Contoh: gunakan halaman website milikmu untuk melihat judul halaman, header keamanan, dan informasi teknologi yang terdeteksi.

## Standard Scan dan Deep Intelligence

**Standard Scan** memeriksa informasi server/halaman yang dapat diambil dengan alur lebih cepat.

**Deep Intelligence** menambahkan pemeriksaan seperti Lighthouse dan reputasi sesuai ketersediaan layanan pendukung. Pilihan ini dapat memerlukan waktu lebih lama atau tidak menghasilkan semua bagian ketika layanan belum tersedia.

Jangan menyamakan bagian yang belum diuji dengan nilai sempurna. Baca keterangan data yang tersedia, terbatas, atau gagal.

## Membaca tab hasil

| Tab | Fokus |
| --- | --- |
| **Overview** | Ringkasan keadaan situs. |
| **Findings** | Temuan dan prioritas pemeriksaan. |
| **SEO** | Unsur halaman yang berkaitan dengan keterbacaan mesin pencari. |
| **Security** | Header dan sinyal keamanan yang dapat diperiksa. |
| **Speed** | Informasi performa yang berhasil diperoleh. |
| **Stack** | Teknologi yang terdeteksi dari sinyal publik. |

Jika suatu teknologi tidak terdeteksi, belum tentu tidak dipakai. Jika suatu header tidak ada, baca dampak temuan tersebut sebelum mengubah konfigurasi.

## Kendala umum

**Batalkan** menghentikan penantian halaman. **New Scan** atau Kembali ke scanner memulai masukan baru.

Website yang memblokir pemeriksaan, membutuhkan login, atau sedang tidak tersedia dapat memberi hasil terbatas. Jika Deep gagal, Standard adalah pemeriksaan dengan cakupan berbeda, bukan pengganti bukti bahwa semua pemeriksaan Deep sudah lulus.

Untuk mengambil kode HTML atau paket halaman, gunakan [Get Code HTML](getcode.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/web-intelligence.js) · [Daftar semua tool](README.md)
