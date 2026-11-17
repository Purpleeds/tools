# Trimpath Generator

Membuat animasi huruf yang garisnya terlihat ditelusuri atau digambar secara bertahap untuk Alight Motion. Cocok untuk judul bergaya tulisan yang muncul mengikuti jalur.

## Langkah awal

1. Isi **Tulis di Sini** dengan kata pendek yang mudah diuji.
2. Pilih **Trimpath Biasa**.
3. Biarkan Aktifkan Style mati untuk melihat gerakan dasar.
4. Gunakan ukuran, jarak, dan timing bawaan.
5. Tekan Generate XML, unduh, lalu putar hasil di Alight Motion.
6. Setelah alurnya cocok, tambahkan warna atau Style.

## Pilihan dan istilah

| Pengaturan | Artinya |
| --- | --- |
| **Pilih Animasi** | Trimpath Biasa atau variasi gerak seperti Move In, Move In Up, In Up Move, dan Move From Left. |
| **Aktifkan Style / Style** | Efek visual tambahan di luar animasi dasar. |
| **Ukuran Font / Jarak antar Huruf / Line Gap** | Ukuran dan jarak tulisan. |
| **Italic** | Arahan tulisan miring. |
| **Stagger (ms)** | Jeda mulai antarhuruf; angka kecil membuat kemunculan lebih rapat. |
| **End Hold (ms)** | Waktu tulisan bertahan setelah gerakan. |
| **Extend Layer** | Pilihan memperpanjang keberadaan lapisan. |
| **Layer Graph** | Laju perubahan gerakan, misalnya Smooth atau Linear. |
| **Aktifkan Color Mapping** | Memakai pola pembagian warna dari palet. |

Mode Mapping **Single** menggunakan satu warna; **Linear**, **Mirror**, dan **Repeat** menerapkan susunan warna berbeda. **Repeat every** mengatur interval pengulangan pada mode yang memakainya. Mapping Style mengatur warna efek tambahan, terpisah dari warna dasar huruf.

## Contoh yang mudah

Gunakan “NEXORA”, Trimpath Biasa, warna dasar putih, dan Stagger 30 ms. Setelah melihat hasil di Alight Motion, coba Style Orange agar perubahannya mudah dikenali.

Jangan mengubah banyak nilai sekaligus. Jika gerakan terasa terlalu lambat atau terlalu ramai, ubah satu pengaturan waktu atau gaya, Generate ulang, lalu bandingkan.

## Batas dan hasil

Engine memakai data huruf yang sudah tersedia. Jika muncul pesan **Karakter belum tersedia di engine**, ganti karakter yang disebut; emoji atau semua bentuk huruf tidak otomatis didukung.

Hasil adalah XML, bukan video final. Preview web membantu membaca teks, sedangkan gerakan lengkap perlu diperiksa pada proyek impor. Riwayat dan palet custom disimpan lokal di perangkat.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [Daftar semua tool](README.md)
