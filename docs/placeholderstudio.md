# Nexora Placeholder Studio

Membuat gambar pengisi untuk contoh desain, thumbnail, banner, atau halaman website. Ada dua cara:

- **Classic:** gambar sederhana dengan teks dan warna yang kamu tentukan; preview dibuat di perangkat.
- **Prompt:** meminta gambar berdasarkan deskripsi ke layanan publik placeholdr.dev.

Gunakan Classic jika hanya butuh kotak bertuliskan “Foto Produk”. Gunakan Prompt jika ingin gambar suasana atau ilustrasi. Untuk pilihan model AI yang lebih lengkap, gunakan [Nexora AI Image](aiimage.md).

## 1. Mulai dengan Classic

Contoh: membuat gambar pengisi katalog produk.

1. Buka kartu **Nexora Placeholder Studio**.
2. Pastikan tab **Classic** dipilih.
3. Pilih preset **Square 1:1**, atau isi Width 600 dan Height 400.
4. Isi **Teks** dengan “Foto Produk”.
5. Pilih **Background** berwarna abu-abu dan **Warna teks** putih.
6. Biarkan **Auto-fit teks** aktif dan **Skala** 1×.
7. Periksa preview yang berubah setelah pengaturan diedit.
8. Beri **Nama file**, lalu gunakan **Download** untuk menyimpan preview.

**Catatan audit versi ini:** tombol Download pada Classic menyimpan **SVG preview lokal**, termasuk ketika pilihan Format menunjukkan PNG. Ini sudah diperiksa melalui unduhan di browser lokal. Jika memerlukan PNG/JPG dari penyedia, gunakan URL asli atau Open Original sesuai penjelasan bagian 5.

## 2. Preset ukuran: pilih sesuai kebutuhan

| Preset | Ukuran | Contoh pemakaian |
| --- | --- | --- |
| **Square 1:1** | 1080 × 1080 | Posting persegi atau kartu katalog. |
| **Landscape 16:9** | 1280 × 720 | Gambar mendatar. |
| **Portrait 4:5** | 1080 × 1350 | Poster atau posting tegak. |
| **Story 9:16** | 1080 × 1920 | Story atau konten vertikal HP. |
| **OG Image** | 1200 × 630 | Gambar kartu saat tautan dibagikan. |
| **Hero** | 1600 × 900 | Gambar besar pembuka halaman website. |
| **Banner** | 1500 × 500 | Spanduk mendatar. |
| **Thumbnail** | 1280 × 720 | Gambar sampul video. |
| **Custom** | Diisi sendiri | Ukuran khusus. |

**Width** berarti lebar; **Height** berarti tinggi, dalam piksel. Misalnya 600 × 400 berarti 600 piksel ke samping dan 400 ke bawah.

Classic menerima ukuran **10–4.000 piksel** per sisi. Prompt menerima **128–2.048 piksel** per sisi. Ukuran besar lebih berat untuk perangkat dan tidak otomatis membuat isi gambar lebih bagus.

## 3. Arti pengaturan Classic

| Pengaturan | Kegunaan |
| --- | --- |
| **Teks** | Tulisan yang tampil pada placeholder, misalnya “Banner Promo” atau “600 × 400”. |
| **Background** | Warna dasar gambar. Gunakan pemilih warna atau kode warna seperti #1c1c1e. |
| **Warna teks** | Warna tulisannya. Pilih warna yang cukup berbeda dari latar agar terbaca. |
| **Background transparan** | Menghilangkan warna dasar pada preview lokal. Gunakan SVG untuk mempertahankan hasil transparan pada versi ini. |
| **Auto-fit teks** | Menyesuaikan ukuran teks secara otomatis pada preview lokal. Tetap periksa tulisan yang sangat panjang. |
| **Format** | Format yang dicantumkan pada URL penyedia: PNG, JPEG, WebP, SVG, AVIF, atau GIF. Lihat keterbatasan unduhan lokal di bagian 5. |
| **Font** | Jenis huruf, misalnya Lato, Poppins, atau Montserrat. |
| **Skala** | Permintaan 1×, 2×, atau 3× pada URL penyedia; misalnya ukuran dasar 600 × 400 pada 2× meminta raster dua kali lebih besar. SVG preview lokal tetap memakai ukuran dasarnya. |
| **Perataan teks** | Rata tengah, kiri, atau kanan pada preview lokal. |
| **Tukar** | Menukar lebar dan tinggi. |
| **Kunci rasio** | Menjaga perbandingan lebar dan tinggi ketika ukuran Classic diubah. |

**Contoh warna:** #ffffff adalah putih, #000000 adalah hitam. Gunakan pemilih warna jika tidak terbiasa dengan kode tersebut.

JPEG tidak mendukung latar transparan. Memilih JPEG bersamaan dengan Background transparan akan ditolak oleh validasi.

## 4. Menggunakan mode Prompt

Contoh: membuat ilustrasi sementara untuk banner kedai kopi.

1. Pilih tab **Prompt**.
2. Pilih preset **Landscape 16:9** atau isi Width 1280 dan Height 720.
3. Ganti contoh pada kolom Prompt dengan deskripsi yang kamu inginkan:

   > Cozy coffee shop interior, morning sunlight through the window, wooden counter, warm brown and cream colors, no text.

4. Pilih **Style: Photographic**.
5. Gunakan **Seed: 1** untuk percobaan pertama.
6. Tekan **Generate Prompt**.
7. Tunggu sampai gambar hasil benar-benar terlihat. Tulisan “Generating” atau “Processing” dari penyedia belum merupakan hasil final.
8. Jika berhasil, gunakan Download atau salin URL hasilnya.

Di Placeholder, **Generate Prompt meminta gambar dari penyedia**. Ini berbeda dari tombol Generate Prompt pada [Prompt Studio](promptgenerate.md), yang menghasilkan teks instruksi.

### Pilihan Style

| Style | Gaya yang diminta |
| --- | --- |
| **Photographic** | Tampilan seperti foto. |
| **Artistic** | Tampilan karya seni. |
| **Anime** | Ilustrasi bergaya anime. |
| **Oil Painting** | Gaya lukisan cat minyak. |
| **3D Render** | Tampilan render tiga dimensi. |
| **Cartoon** | Ilustrasi kartun. |

### Apa itu Seed?

Seed adalah pilihan variasi pada permintaan gambar. Di tool ini nilainya hanya **1, 2, atau 3**. Tombol **Acak seed** memilih salah satu dari tiga angka tersebut.

Untuk meminta variasi, ubah seed lalu jalankan lagi. Menggunakan seed yang sama bukan jaminan mutlak hasil identik; layanan publik dapat mengubah atau menyimpan hasilnya sendiri.

Kolom Prompt dibatasi **1.000 kata**, bukan 1.000 karakter. Tulisan yang melewati batas dipotong sampai batas tersebut oleh antarmuka. Periksa kalimat akhir jika menempelkan deskripsi panjang.

## 5. Bedakan preview, file lokal, dan URL publik

Ada tiga hal yang terlihat mirip tetapi fungsinya berbeda.

### Preview lokal Classic

Preview dibuat di browser dan dapat tampil tanpa menunggu layanan gambar. Perataan, Auto-fit, dan transparansi berlaku pada preview ini.

**Grid**, **Gelap**, dan **Terang** hanya mengganti latar area pemeriksaan. Mengganti Grid ke Gelap tidak otomatis mengubah warna file gambar.

### File dari tombol Download

Pada versi source yang diaudit, Classic menyimpan SVG preview lokal. Memilih PNG pada daftar Format belum membuat tombol tersebut mengunduh PNG. Nama file mengikuti kolom Nama file, sedangkan ekstensinya mengikuti file yang benar-benar diunduh.

Jika sudah ada hasil Prompt, tombol Download menyimpan file gambar hasil yang diterima. Jika pengambilan langsung dibatasi layanan, halaman dapat membuka sumber asli sebagai gantinya.

### URL asli dan Open Original

URL Classic mengarah ke placeholderimage.co. URL Prompt mengarah ke placeholdr.dev. Tautan ini berguna untuk memasang gambar pada website atau membagikannya.

**URL Classic tidak membawa semua pengaturan preview lokal.** Perataan dan Auto-fit tidak dicantumkan pada URL. Saat Background transparan aktif, tool tidak menghasilkan URL Classic.

Karena itu:

- Untuk menyimpan bentuk preview lokal, gunakan Download SVG.
- Untuk mencoba format PNG/JPG/WebP dari penyedia, pilih Format, salin URL asli atau tekan Open Original, lalu simpan hasil dari sumber tersebut jika tersedia.
- Bandingkan hasil sumber dengan preview; tampilan huruf dan penataan dapat berbeda.
- Jangan sekadar mengganti ekstensi file SVG menjadi PNG; itu tidak mengubah format gambarnya.

## 6. Tombol hasil dan kapan memakainya

| Tombol | Yang disalin atau dibuka |
| --- | --- |
| **Download** | File hasil yang saat ini tersedia; perhatikan catatan Classic di atas. |
| **Copy URL** | Tautan gambar dari layanan publik. |
| **HTML** | Potongan tag gambar untuk halaman HTML. |
| **Markdown** | Potongan teks penyisipan gambar untuk dokumen Markdown. |
| **CSS** | Potongan pengaturan background-image untuk CSS website. |
| **SVG** | Kode SVG lokal pada mode Classic; tombol ini tidak tersedia untuk Prompt. |
| **Open Original** | Membuka URL sumber gambar di tab lain. |
| **Refresh** | Meminta ulang hasil Prompt dengan konfigurasi yang ada. |
| **Batalkan** | Menghentikan penantian atau permintaan yang sedang ditangani halaman. |

**Nama file** mengatur nama unduhan. Mengubahnya tidak mengganti isi gambar atau alamat layanan.

**Recent** berisi konfigurasi yang telah tersimpan di browser perangkat tersebut. Permintaan Prompt dicatat ketika dijalankan. Memilih catatan Prompt mengisi setelannya kembali; tekan Generate Prompt jika ingin menjalankannya. **Clear** membersihkan riwayat lokal.

## 7. Jika hasil belum sesuai

| Masalah | Yang perlu diperiksa |
| --- | --- |
| Classic tidak punya tombol Buat | Normal: preview Classic diperbarui otomatis setelah pengaturan berubah. |
| Gambar yang diunduh SVG padahal memilih PNG | Perilaku versi yang diaudit; gunakan URL sumber untuk mencoba format penyedia. |
| URL kosong saat transparan | Transparansi hanya tersedia pada hasil lokal, bukan URL Classic. |
| Preview dan Open Original berbeda | Tidak semua pengaturan lokal dibawa ke URL CDN. Gunakan hasil yang sesuai kebutuhanmu. |
| Ukuran ditolak | Classic 10–4.000; Prompt 128–2.048 piksel per sisi. |
| Seed ditolak | Isi 1, 2, atau 3. |
| Provider masih Processing | Tunggu; jika batas waktu habis, gunakan Refresh atau Open Original. |
| Copy URL/HTML/CSS tidak bekerja | Pastikan sudah ada URL hasil. Opsi ini tidak dapat memakai preview yang hanya tersimpan lokal. |
| Huruf terlalu panjang atau susah dibaca | Pendekkan teks, perbesar area, dan gunakan warna dengan kontras yang cukup. |

Prompt mode dikirim sebagai bagian dari URL layanan publik. Gunakan deskripsi yang memang layak dibagikan pada layanan tersebut.

[Sumber antarmuka yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/placeholder-studio.js) · [Daftar semua tool](README.md)
