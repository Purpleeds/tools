# AUTO TRACE

Mengubah gambar PNG/JPG/WebP menjadi SVG dengan engine **Vector Ink**. Hasil dibuat dari penelusuran bentuk dan warna gambar, sehingga paling mudah dipahami dengan logo atau ilustrasi sederhana terlebih dahulu.

AUTO TRACE dan [Vecto](vecto.md) adalah dua tool terpisah dengan engine berbeda.

## Langkah pertama

1. Siapkan PNG, JPG, atau WebP maksimal 12 MB.
2. Unggah melalui **Drop atau pilih gambar**.
3. Untuk percobaan awal, gunakan pengaturan bawaan: Color Detail 6/8, Smoothness 70, Noise Removal 14.
4. Tekan **Trace dengan Vector Ink**.
5. Tunggu sampai SVG benar-benar tersedia.
6. Bandingkan tampilan **Original**, **Split**, dan **Vector**.
7. Jika sesuai, tekan **Download SVG**.

Memperbesar preview tidak mengembalikan detail yang tidak ada pada gambar sumber. Foto dengan banyak gradasi dapat menghasilkan SVG yang lebih rumit daripada logo beberapa warna.

## Tiga pengaturan utama

| Pengaturan | Cara memahaminya |
| --- | --- |
| **Color Detail** | Arahan banyaknya detail warna yang dipertahankan. Ubah sedikit demi sedikit lalu bandingkan. |
| **Smoothness** | Arahan keluwesan bentuk/kurva pada hasil. Nilai terlalu tinggi dapat membuat sudut atau detail terasa berbeda. |
| **Noise Removal** | Arahan pengurangan bintik kecil. Gunakan hati-hati jika gambar memiliki detail kecil yang penting. |

Tiga kontrol ini berkaitan dengan parameter lanjutan. Setelah mengubah nilai, **jalankan Trace lagi** untuk membuat hasil baru; menggeser kontrol tidak otomatis mengganti SVG yang sudah selesai.

## Advanced Settings

Jika belum memahami parameter teknis, tetap gunakan nilai bawaan. Parameter yang tersedia mencakup:

- **Speckle:** ukuran bintik kecil yang menjadi sasaran pengurangan.
- **Color Precision:** ketelitian pembedaan warna.
- **Corner Threshold:** arahan penanganan sudut.
- **Segment Length / Splice Threshold:** arahan pembentukan dan penyambungan segmen.
- **Max Iterations:** batas pengulangan proses pada parameter yang disediakan.
- **Path Precision:** ketelitian koordinat path.

Pengaruh akhirnya mengikuti cara engine memproses permintaan, bukan jaminan bahwa setiap angka akan membuat hasil selalu lebih bagus. **Reset Settings** mengembalikan parameter awal.

## Hasil dan Ungroup

**Ungroup** mencoba melepas grup SVG agar bentuk lebih mudah dipilih terpisah pada editor lain. Ini bukan fitur memotong karakter menjadi bagian tubuh atau memisahkan setiap warna dengan hasil yang dijamin sempurna.

Beberapa grup dapat dilewati demi mempertahankan tampilan. Baca catatan hasil Ungroup, dan gunakan **Undo Ungroup** untuk kembali. Unduhan menggunakan versi SVG hasil yang sedang aktif.

- **Copy SVG:** menyalin kode SVG.
- **View code:** melihat kode hasil.
- **Download SVG:** menyimpan berkas SVG.
- **Reset:** membersihkan pekerjaan untuk gambar berikutnya.
- **Retry Vector Ink:** mencoba ulang permintaan yang gagal.

Jika layanan Vector Ink bermasalah, baca pesan kegagalannya. Berhasil mengunggah atau melihat gambar Original saja belum berarti proses trace sudah selesai. Simpan SVG sebelum menutup tool.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/image-vectorizer.js) · [Daftar semua tool](README.md)
