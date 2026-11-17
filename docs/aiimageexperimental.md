# AI Image Eksperimental

Tempat mencoba **lima kelompok layanan** dengan pekerjaan yang berbeda. Sebagian membuat gambar lewat internet; sebagian menganalisis atau mengolah gambar secara lokal di browser.

Jangan menganggap semua pilihan menghasilkan gambar baru dari tulisan.

## Pilih kelompok sesuai kebutuhan

| Kelompok | Fungsinya | Tempat proses |
| --- | --- | --- |
| **AI Horde** | Membuat gambar melalui worker komunitas; dapat memakai gambar awal jika mode tersedia. | Layanan online. |
| **Pollinations** | Membuat gambar melalui layanan Classic publik. | Layanan online. |
| **Transformers** | Klasifikasi, deteksi objek, segmentasi, atau perkiraan kedalaman. | Browser. |
| **MediaPipe** | Deteksi wajah/tangan/pose, efek, atau pemisahan objek/orang. | Browser. |
| **ONNX** | Mask objek, fokus objek dengan latar buram, atau pembesaran khusus. | Browser. |

## Percobaan pertama

Untuk mencoba pembuatan gambar, pilih AI Horde atau Pollinations dan tulis deskripsi singkat. Untuk memisahkan orang dari latar, pilih MediaPipe dan tugas segmentasi orang.

Berkas gambar untuk workspace ini dibatasi **8 MB** dan **16 juta piksel**. Gambar besar dapat dikecilkan sesuai kemampuan mode dan perangkat. Ini berbeda dari Vecto yang mempertahankan input aslinya.

## AI Horde: gambar baru

1. Pilih **AI Horde**.
2. Muat daftar model melalui tombol model jika diperlukan.
3. Pilih model aktif yang tersedia.
4. Tulis prompt, pilih ukuran, dan periksa Steps.
5. Jika memakai gambar awal, aktifkan pilihan terkait dan unggah gambarnya.
6. Tekan **Generate gambar**.
7. Tunggu antrean dan proses selesai, lalu periksa serta unduh hasilnya.

**Steps** adalah jumlah tahap pengerjaan model. Formulir menyediakan 4–30, dengan nilai awal 20. Nilai lebih besar tidak menjamin gambar lebih cocok dan bisa menambah waktu.

Contoh:

> A quiet Indonesian village after rain, warm afternoon sunlight, detailed illustration, no text.

Antrean komunitas bisa lama atau model sedang tidak tersedia. Status antrean belum berarti gambar sudah berhasil dibuat.

## Pollinations: layanan Classic publik

1. Pilih **Pollinations**.
2. Isi prompt dan pengaturan yang ditampilkan.
3. Jalankan Generate gambar.
4. Tunggu gambar final; simpan hasil jika tersedia.

Mode ini memakai satu pilihan model dari penyedia, bukan daftar banyak model yang bebas dipilih. Ada jeda minimal **45 detik per IP** pada integrasi ini. Logo penyedia dapat muncul dan hasil dapat disimpan dalam cache publik penyedia. Jika muncul 401/403 atau Authentication Required, layanan anonim tersebut sedang tidak tersedia untuk permintaan itu.

## Transformers: membaca isi gambar

1. Pilih **Transformers**.
2. Pilih tugas, lalu unggah gambar.
3. Untuk segmentasi, tentukan target jika kolomnya ditampilkan.
4. Tekan **Proses di perangkat** dan tunggu model dimuat.
5. Baca hasil analisis atau periksa hasil visualnya.

| Tugas | Cara memahami hasil |
| --- | --- |
| **Klasifikasi gambar** | Label perkiraan isi utama gambar. |
| **Deteksi objek** | Objek beserta posisi atau kotaknya. |
| **Segmentasi dan mask objek** | Area piksel yang diperkirakan termasuk objek. |
| **Estimasi depth relatif** | Perkiraan bagian dekat dan jauh; bukan pengukuran jarak dalam meter. |

## MediaPipe: wajah, pose, dan mask

Pilih tugas sebelum memproses:

- **Deteksi wajah / filter kacamata:** menemukan wajah atau menempatkan efek.
- **Face landmarks:** menampilkan titik acuan wajah.
- **Hand landmarks:** titik acuan tangan.
- **Pose landmarks / efek neon:** titik atau efek mengikuti pose tubuh.
- **Segmentasi orang:** memisahkan area orang menjadi PNG transparan.
- **Mask objek — tap pada gambar:** ketuk objek pada preview dahulu, baru tekan Proses.

Pilihan ini mengolah gambar statis; tidak otomatis membuka kamera atau membuat video langsung.

## ONNX: mask, fokus, atau pembesaran

1. Pilih **ONNX**.
2. Pilih tugas dan tambahkan gambar.
3. Jalankan Proses di perangkat.
4. Bandingkan hasil sebelum mengunduh.

**U²-NetP mask** mencoba memisahkan objek. **Fokus objek** memakai mask untuk memburamkan latar. **ESPCN** pada integrasi ini membuat pembesaran x3 dari sumber yang dibatasi sampai sisi 224 piksel; ini bukan layanan pembesaran foto besar dengan detail asli yang dijamin kembali.

## Hasil dan kendala umum

Gunakan preview pembanding, lalu **Download** untuk gambar. Unduhan JSON, jika tersedia, menyimpan informasi hasil analisis, bukan gambar.

Model lokal diunduh saat dibutuhkan. Jangan menutup tab selama pemuatan atau pemrosesan. Jika memori habis, pakai gambar lebih kecil dan tutup tab berat. Batalkan jika ingin menghentikan penantian di halaman. Kegagalan cloud tidak otomatis berpindah ke model lokal karena pekerjaan keduanya bisa berbeda.

Untuk pilihan yang lebih terarah, gunakan [AI Image](aiimage.md) untuk generasi gambar atau [Smart Cutout](smartcutout.md) untuk memilih objek.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/ai-image-experimental/workspace.mjs) · [Daftar semua tool](README.md)
