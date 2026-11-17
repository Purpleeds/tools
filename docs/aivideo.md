# Nexora AI Video Generator

Membuat video dari tulisan atau dari satu gambar awal melalui akun Puter. Jika baru mencoba, mulai dari adegan sederhana, durasi pendek, dan satu gerakan kamera.

## Persiapan

- Login Nexora jika diminta, lalu **Hubungkan Puter** melalui jendela resmi Puter.
- Login Puter terpisah dari login Nexora. Pemakaian mengikuti jatah akun Puter.
- Untuk Image to Video, siapkan satu JPG, PNG, atau WebP maksimal 10 MB.

## Pilih mode

| Mode | Kapan dipakai | Yang diisi |
| --- | --- | --- |
| **Text to Video** | Membuat adegan dari awal. | Prompt. |
| **Image to Video** | Menggerakkan atau mengembangkan satu gambar. | Gambar awal dan prompt gerakan. |

## Langkah pertama

1. Pilih **Text to Video**.
2. Tulis adegan yang jelas: subjek, gerakan, tempat, cahaya, dan gerakan kamera.
3. Pilih model yang tersedia untuk mode tersebut.
4. Pilih durasi pada **Durasi yang diminta**.
5. Jika rasio ditampilkan, pilih 9:16 untuk tegak atau 16:9 untuk mendatar.
6. Tekan **Generate Video** satu kali.
7. Tunggu proses selesai, lalu putar video sebelum mengunduh.

Contoh prompt:

> Seekor kucing duduk di dekat jendela saat hujan. Kucing perlahan menoleh ke luar, cahaya hangat dari lampu meja, kamera diam, gerakan alami.

Untuk Image to Video, pilih gambarnya dahulu, lalu gunakan arahan seperti:

> Pertahankan karakter dan pakaian dari gambar awal. Gerakkan rambut pelan tertiup angin, kamera mendekat perlahan, latar tetap konsisten.

## Model dan pengaturan

| Pilihan dalam source | Durasi yang tersedia | Keterangan |
| --- | --- | --- |
| **Wan 2.7 · Text** | 5, 8, 10, 15 detik | Untuk Text to Video; pilihan 9:16 atau 16:9, 720p. |
| **Wan 2.7 · Image** | 5, 8, 10, 15 detik | Untuk Image to Video; pilihan 9:16 atau 16:9, 720p. |
| **Veo 3.1 Lite / Veo 3.1** | 4, 6, 8 detik | Mendukung dua mode; rasio dan resolusi mengikuti pengaturan penyedia, sehingga kontrol tertentu disembunyikan. |

Daftar yang benar-benar bisa dipakai mengikuti akun dan penyedia saat digunakan. Model yang gagal dikenali dapat dinonaktifkan selama sesi.

Kolom prompt dibatasi 3.000 karakter. Jangan meminta terlalu banyak perubahan adegan sekaligus untuk percobaan pertama. Pilihan durasi adalah permintaan ke layanan; periksa durasi hasilnya.

## Hasil dan tombol

- Player tidak memutar video otomatis; tekan Play.
- **Download Video** mengambil hasil yang sudah ada.
- **Open Video** membuka sumber video. Gunakan menu simpan browser jika unduhan langsung dibatasi.
- **Generate Again** merupakan permintaan baru, bukan mengunduh ulang.
- **Hubungkan Ulang Puter** digunakan saat koneksi akun perlu diperbaiki.

Pembuatan video dapat memerlukan beberapa menit. Jika batas tunggu antarmuka terlewati, pekerjaan Puter bisa masih berjalan. Tombol tetap dibatasi sampai status permintaan tersebut selesai; memuat ulang atau mengirim lagi dapat membuat pekerjaan baru.

## Jika bermasalah

Jika Image to Video tidak bisa dijalankan, pastikan gambar sudah dimuat dan model mendukung mode itu. Jika muncul masalah kuota, periksa jatah Puter. Jika video tidak bisa diputar di HP tetapi tautannya ada, coba Open Video atau perangkat dengan dukungan codec yang sesuai.

Untuk menyusun arahan video yang lebih terstruktur, gunakan [Prompt Studio](promptgenerate.md), lalu salin teksnya ke sini.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/puter-runtime.js) · [Daftar semua tool](README.md)
