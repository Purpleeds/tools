# PDF Lab Local

Mengolah PDF langsung di perangkat. Pilihan pekerjaannya mencakup menyusun halaman, menggabungkan, memisahkan, membuat PDF dari gambar, menambah watermark atau tulisan, mengubah informasi dokumen, dan mengisi formulir.

## Cara mulai

1. Pilih **operasi** terlebih dahulu.
2. Tambahkan file pada area unggah.
3. Tunggu halaman atau daftar file muncul.
4. Atur perubahan sesuai operasi.
5. Tekan **Export PDF**.
6. Buka file hasil untuk memeriksa halaman dan isinya.

Perubahan seperti hapus dan putar diterapkan pada hasil ekspor. File asli di perangkat tidak ditimpa otomatis.

## Pilih operasi yang sesuai

| Operasi | Langkah khusus |
| --- | --- |
| **Organize** | Ketuk halaman untuk memilih. Gunakan panah pada halaman untuk mengubah urutan, Hapus untuk menghapus dari hasil, dan Rotate +90° untuk memutar. |
| **Merge** | Tambahkan minimal dua PDF. Hasil digabung sesuai urutan daftar file. Periksa urutan sebelum Export. |
| **Split / Extract** | Isi kolom Rentang untuk memilih halaman yang dipisahkan. |
| **Images → PDF** | Tambahkan PNG/JPG/WebP. Pilih Page size mengikuti gambar atau A4, lalu atur Margin mm. |
| **Watermark** | Isi tulisan watermark, ukuran, kepekatan, dan sudutnya. |
| **Add Text** | Isi tulisan, ukuran, dan posisi X/Y dalam persen. |
| **Metadata** | Ubah Title, Author, Subject, atau Keywords. Clear metadata membersihkan informasi tersebut. |
| **Fill Form** | Isi kolom formulir interaktif yang ditemukan dalam PDF. |

### Contoh Split / Extract

Untuk mengambil halaman 1 sampai 3 dan halaman 5 menjadi satu file, isi:

> 1-3,5

Untuk membuat dua file terpisah, gunakan titik koma:

> 1-3,5; 6-10

Bagian sebelum titik koma menjadi satu hasil, bagian sesudahnya menjadi hasil lain. Nomor halaman dimulai dari **1**, bukan 0.

### Watermark dan Add Text

**Target halaman: Semua halaman** menerapkan perubahan ke seluruh dokumen. Untuk **Halaman terpilih**, ketuk minimal satu halaman pada preview sebelum Export.

Pada watermark, **Opacity** kecil membuat tulisan lebih transparan; **Angle** mengatur kemiringan. Pada Add Text, X/Y mengatur letak tulisan; gunakan hasil ekspor untuk memeriksa apakah posisinya sesuai.

### Mengisi formulir

Fill Form hanya mengenali kolom PDF interaktif atau **AcroForm**. PDF hasil scan biasa tidak otomatis berubah menjadi formulir.

**Flatten form** menyatukan nilai formulir ke tampilan halaman agar tidak lagi menjadi kolom yang mudah diedit. Periksa isian sebelum memilihnya.

## Contoh pemakaian

Ingin mengirim halaman penting dari dokumen 20 halaman:

1. Pilih Split / Extract.
2. Tambahkan PDF.
3. Isi “1-2,8” jika yang dibutuhkan halaman 1, 2, dan 8.
4. Export PDF.
5. Buka hasil dan pastikan hanya tiga halaman tersebut yang ada.

## Penyimpanan dan kendala

Pemrosesan memakai browser, bukan mengunggah dokumen ke server Nexora. Namun pustaka atau aset aplikasi tetap perlu tersedia saat dibuka.

Batas per file pada kode adalah 250 MB, dengan pemberitahuan untuk file di atas 80 MB. Batas itu bukan jaminan HP sanggup mengolahnya; mulai dari dokumen lebih kecil.

Jika Export belum aktif, pastikan file sudah dibaca. Merge membutuhkan lebih dari satu PDF. Jika PDF tidak bisa dibaca, periksa apakah file rusak, terenkripsi, atau memakai fitur yang tidak didukung.

**Add Text menambahkan tulisan baru; tidak otomatis mengedit paragraf lama di dalam PDF.** Untuk membaca teks dari scan, gunakan [OCR Intelligence](ocrintel.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/pdf-lab/src/workspace.js) · [Daftar semua tool](README.md)
