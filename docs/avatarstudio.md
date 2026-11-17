# Nexora Avatar Studio

Membuat avatar dari berbagai gaya karakter, lalu menyesuaikan detailnya tanpa menggambar dari nol. Hasil dapat diunduh sebagai SVG atau gambar biasa.

## Cara mulai

1. Buka **Nexora Avatar Studio**.
2. Pada **Choose a base style**, pilih satu gaya yang disukai. Gunakan Search style jika daftarnya panjang.
3. Pada **Avatar controls**, ubah detail yang tersedia untuk gaya tersebut.
4. Lihat perubahan pada **Live Preview**.
5. Untuk avatar yang langsung mudah dipakai, pilih **Download PNG**. Untuk berkas vektor, pilih **Download SVG**.

Jika ingin cepat, gunakan **Randomize Avatar / Shuffle Avatar** atau **Random Style**, lalu sesuaikan hasilnya.

## Memahami Seed dan pengaturan

**Seed** adalah teks atau angka acuan untuk menyusun avatar. Seed yang sama dengan gaya dan pengaturan yang sama membantu membuat susunan yang sama lagi. Seed bukan nomor akun.

**Random Seed** mengganti acuan variasi. **Copy** pada bagian seed menyalinnya. Mengganti gaya dapat memunculkan pengaturan yang berbeda; sebuah gaya belum tentu punya pilihan rambut, mata, atau pakaian yang sama.

Gunakan **Search settings** untuk mencari kontrol, misalnya “Hair” atau “Background”. Mulai dari warna, latar, dan bagian wajah yang memang tersedia di gaya tersebut.

## Format dan ukuran

| Pilihan | Dipakai untuk |
| --- | --- |
| **SVG** | Avatar vektor yang dapat diperbesar dalam penggunaan yang mendukung SVG. |
| **PNG** | Gambar umum, termasuk kebutuhan transparansi jika hasil mendukungnya. |
| **JPG** | Gambar tanpa transparansi. |
| **WebP / AVIF** | Format gambar modern; dukungan mengikuti browser. |
| **JSON** | Konfigurasi atau informasi avatar, bukan foto avatar. |

**Raster size** menentukan ukuran keluaran gambar biasa. Pilihan 512 atau 1024 pada antarmuka dibuat melalui pengolahan browser; sumber API raster memiliki batas yang berbeda. Unduh melalui Download selected jika memakai format yang dipilih pada daftar.

## Menyimpan agar bisa dipakai lagi

- **Save Preset** menyimpan pilihan di browser perangkat itu.
- **Copy Config JSON** menyimpan susunan pengaturan; cocok untuk dipakai kembali melalui Import Config.
- **Copy SVG URL / Copy Image URL** menyalin tautan sumber.
- **Copy &lt;img&gt; / Copy Markdown** menyalin cara menyisipkan gambar pada halaman atau dokumen.
- **Share Config** membantu membagikan pengaturan yang dapat diulang.

Contoh: buat gaya yang disukai, isi Seed “nexora-kopi”, simpan preset, lalu unduh PNG untuk foto profil. Simpan konfigurasi jika ingin mengulangnya di perangkat lain.

Jika gagal ekspor format tertentu, coba SVG atau PNG. **License Info** menampilkan informasi gaya; periksa ketika hasil akan dipakai pada produk yang dibagikan.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/avatar-studio.js) · [Daftar semua tool](README.md)
