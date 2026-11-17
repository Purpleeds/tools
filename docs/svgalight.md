# SVG → Alight XML

Mengubah SVG statis menjadi XML yang bisa diimpor ke Alight Motion. Cocok ketika logo atau ilustrasi vektor ingin dipakai sebagai bentuk di proyek animasi.

**SVG** adalah gambar berbasis bentuk. **XML** di sini adalah hasil untuk Alight Motion, bukan gambar PNG atau video.

## Cara mulai

1. Siapkan file SVG maksimal 2 MB. PNG/JPG tidak langsung diterima sebagai SVG.
2. Buka **SVG → Alight XML** dan pilih atau jatuhkan file.
3. Tunggu preview serta daftar lapisan terbaca.
4. Untuk percobaan awal, pilih **Maximum Fidelity**.
5. Atur ukuran proyek, nama proyek, FPS, dan durasi.
6. Periksa bentuk yang dipilih pada daftar lapisan.
7. Tekan **Convert ke XML**.
8. Baca status dan peringatan, lalu gunakan **Download XML**.
9. Impor hasil melalui fitur impor proyek XML di Alight Motion dan periksa tampilannya.

Jika sumber masih PNG/JPG, buat SVG lebih dahulu melalui [Vecto](vecto.md) atau [AUTO TRACE](imagevectorizer.md).

## Pilih mode konversi

| Mode | Tujuan | Perlu diperhatikan |
| --- | --- | --- |
| **Maximum Fidelity** | Mempertahankan detail dan susunan sumber semaksimal mungkin. | Pilihan awal ketika kesetiaan bentuk lebih penting. |
| **Smart Color Groups** | Mengelompokkan bentuk dengan warna solid yang sama. | Baca laporan urutan tumpukan dan konflik; tidak semua bentuk dapat dikelompokkan tanpa perubahan tampilan. |
| **Small Patch Cleanup** | Mengurangi bidang kecil yang dianggap serpihan. | Detail kecil yang memang penting perlu diperiksa kembali. |

Pada Cleanup, **Small Patch Threshold** menentukan batas area kecil dan **Protect Thin Details** membantu melindungi detail tipis. Mulai dari nilai bawaan dan bandingkan hasil, terutama mata, garis, atau celah kecil.

## Pengaturan proyek dan bentuk

- **Asli / 1:1 / 16:9 / 9:16 dan lainnya:** pilihan ukuran atau rasio kanvas.
- **Dimensi custom:** lebar dan tinggi yang diisi sendiri.
- **FPS:** jumlah frame per detik proyek; bukan tingkat detail gambar.
- **Durasi:** panjang proyek dalam detik.
- **Semua / Tidak Ada / Balik:** mengatur pilihan bentuk pada daftar.
- **Flat:** bentuk disusun langsung.
- **Nested Groups:** mempertahankan susunan grup dalam struktur hasil.
- **Detect Primitive Shapes:** mencoba memakai bentuk dasar yang kompatibel ketika memungkinkan; sisanya tetap berupa path.

**Rekonstruksi overlap fill** adalah pilihan tambahan pada Maximum Fidelity untuk menangani bidang yang saling menutupi. Bentuk kurva dapat berubah; gunakan hanya bila perlu dan bandingkan hasilnya.

## Preview dan hasil

Tombol **− / + / Fit** hanya membantu melihat preview; bukan mengubah ukuran ekspor. **Nama project Alight Motion** berbeda dari **Nama file download**: yang pertama nama dalam proyek, yang kedua nama berkas XML di perangkat.

**Salin XML** menyalin teks hasil. **Tampilkan penuh** membuka hasil yang panjang. Jika memilih bentuk atau mengubah pengaturan setelah konversi, jalankan konversi lagi agar hasil sesuai pilihan terbaru.

## Jika belum berhasil

Jika pilihan engine dinonaktifkan, layanan tidak menyediakan pilihan itu saat pemeriksaan; gunakan **Cek ulang** setelah layanan siap. Jika SVG tidak terbaca, periksa formatnya dan hindari file yang hanya berganti ekstensi dari PNG ke SVG. Jika tampilan di Alight Motion berbeda, periksa bentuk, efek, gradient, dan peringatan kompatibilitas.

Untuk gerakan yang sudah berada dalam kode SVG, gunakan [SVG Animasi → Alight XML](svganimation.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/svg-alight.js) · [Daftar semua tool](README.md)
