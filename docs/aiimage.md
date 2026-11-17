# Nexora AI Image

Studio untuk membuat gambar baru, mengedit gambar, atau membuat gambar dengan acuan visual. Ada empat mode; langkahnya berbeda sesuai mode yang dipilih.

**Mulai paling mudah:** pilih **Generate**, hubungkan akun Puter, tulis gambar yang diinginkan, gunakan model rekomendasi, lalu tekan **Buat Gambar**.

## 1. Persiapan: hubungkan Puter

1. Buka kartu **Nexora AI Image** dari dashboard. Login Nexora jika diminta.
2. Tunggu sampai daftar model dan tombol koneksi siap.
3. Tekan **Hubungkan** atau tombol besar **Hubungkan Puter**.
4. Selesaikan login pada jendela resmi Puter. Izinkan pop-up jika browser memblokirnya.
5. Kembali ke studio. Status akan menunjukkan akun Puter yang terhubung.

**Akun Nexora dan akun Puter berbeda.** Login Nexora mengatur akses ke tool; akun Puter menyediakan layanan AI dan jatah pemakaiannya. Keanggotaan Nexora tidak otomatis menambah jatah Puter.

Jika penekanan pertama hanya membuka login, setelah terhubung periksa kembali pengaturan dan tekan tombol pembuatan untuk memulai.

## 2. Pilih mode yang sesuai

| Mode | Dipakai ketika | Gambar yang perlu disiapkan |
| --- | --- | --- |
| **Generate** | Membuat gambar baru dari tulisan. | Tidak perlu gambar. |
| **Edit** | Mengubah gambar yang sudah ada. | Satu gambar sumber. |
| **Reference** | Membuat adegan baru dengan gambar sebagai acuan karakter, produk, pakaian, gaya, atau suasana. | Satu gambar acuan. |
| **Multi** | Menggabungkan acuan dari beberapa gambar. | Minimal dua, maksimal sesuai petunjuk studio; antarmuka membatasi sampai empat gambar. |

Daftar model menyesuaikan mode. Model yang muncul pada Generate belum tentu mendukung Edit atau Reference. Contohnya, Leonardo Lucid Origin pada katalog ini hanya mendukung Generate; Qwen Image mendukung acuan tunggal, bukan Multi.

### Generate: gambar baru dari tulisan

1. Pilih **Generate**.
2. Isi **Ide gambarmu** dengan subjek, tempat, gaya, cahaya, dan komposisi.
3. Jika perlu, tekan salah satu **Quick style**.
4. Pilih model, rasio, dan kualitas.
5. Tekan **Buat Gambar** satu kali dan tunggu hasilnya.

Contoh siap dicoba:

> Foto produk sebotol kopi susu di atas meja kayu, latar kedai kopi yang sedikit buram, cahaya pagi dari sisi kiri, warna hangat, botol menjadi fokus utama, tanpa tulisan tambahan.

Pengaturan awal yang mudah: model **GPT Image 2.5 Flare** jika tersedia, rasio **1:1**, dan kualitas bawaan. Ini titik awal untuk mencoba, bukan jaminan hasil tertentu.

### Edit: ubah bagian tertentu pada gambar

1. Pilih **Edit**, lalu tambahkan satu gambar.
2. Gunakan PNG, JPG, atau WebP sesuai pemilih file; ukuran setiap file maksimal 15 MB.
3. Pada **Instruksi edit**, jelaskan apa yang diubah dan apa yang tetap.
4. Pilih model yang tersedia pada mode ini.
5. Tekan **Edit Gambar**.

Contoh:

> Ubah latar belakang menjadi studio abu-abu terang. Pertahankan orang, wajah, warna pakaian, pose, dan posisi kamera. Jangan tambahkan objek baru.

Kalimat seperti “buat bagus” terlalu luas. Instruksi yang menyebut bagian tertentu lebih mudah diarahkan. Hasil AI tetap perlu diperiksa, termasuk wajah, tulisan, tangan, dan detail produk.

### Reference: gambar sebagai acuan

1. Pilih **Reference**, lalu tambahkan satu gambar.
2. Tulis adegan baru yang ingin dibuat.
3. Sebutkan unsur yang perlu mengikuti acuan.
4. Tekan **Buat dari Reference**.

Contoh untuk gambar karakter:

> Gunakan karakter pada gambar acuan, pertahankan gaya rambut dan warna pakaiannya. Buat adegan karakter berdiri di halte saat hujan malam hari, pencahayaan sinematik, sudut pandang seluruh tubuh.

Reference memberi arah pada AI. Fitur ini tidak menjamin semua detail gambar awal akan disalin persis.

### Multi: beberapa acuan dalam satu gambar

1. Pilih **Multi**.
2. Tambahkan minimal dua gambar. Baca petunjuk jumlah maksimum yang tampil; batas studio bisa lebih kecil daripada kemampuan umum model.
3. Perhatikan urutannya pada daftar **Reference 1**, **Reference 2**, dan seterusnya.
4. Jelaskan peran masing-masing gambar pada **Prompt komposisi**.
5. Tekan **Gabungkan Reference**.

Contoh:

> Gunakan karakter dari gambar pertama, pakaian dari gambar kedua, dan suasana ruangan dari gambar ketiga. Buat satu adegan yang menyatu dengan cahaya alami. Pertahankan identitas karakter dari gambar pertama.

Jika salah memasukkan gambar, hapus gambar itu atau gunakan **Hapus semua**, lalu tambahkan kembali sesuai urutan. Memilih model dengan batas acuan lebih kecil dapat mengurangi gambar yang dipertahankan studio; cek daftarnya sebelum membuat hasil.

## 3. Memahami pengaturan

| Pengaturan | Artinya dan cara memilih |
| --- | --- |
| **Ide gambarmu / Instruksi edit / Prompt komposisi** | Tulisan yang menjadi arahan utama AI. Wajib sedikitnya 3 karakter; kolom dibatasi 2.000 karakter. |
| **Acak ide** | Membantu mengisi ide contoh. Jika kolom sudah berisi tulisan, ide tambahan dapat ikut ditambahkan; baca ulang sebelum menjalankan. |
| **Quick style** | Menambahkan frasa gaya ke tulisanmu, seperti Anime, Cinematic, Product Photo, atau Minimal. Frasanya bisa diedit langsung di kolom prompt. |
| **Model** | Mesin AI yang mengerjakan permintaan. Pilih berdasarkan kebutuhan dan model yang sedang tersedia. |
| **Lihat semua model** | Membuka pilihan tambahan di luar kartu rekomendasi. |
| **Rasio gambar** | Bentuk gambar: persegi, tegak, atau mendatar. Ini tidak menentukan isi adegan. |
| **Quality** | Pilihan mutu atau ukuran yang diteruskan ke model. Nama dan jumlah pilihannya berbeda antarmodel; ikuti yang tampil di layar. |

Panduan rasio:

- **1:1:** persegi, misalnya gambar profil atau posting persegi.
- **3:4:** foto atau ilustrasi tegak.
- **4:3:** gambar mendatar dengan ruang cukup lebar.
- **9:16:** konten vertikal seperti Story atau wallpaper HP.
- **16:9:** gambar mendatar seperti thumbnail atau ilustrasi layar lebar.

Jangan menganggap label **1K**, **high**, dan **1 MP** berarti hal yang sama. Masing-masing mengikuti cara kerja model. Pilihan kualitas juga tidak membuktikan harga atau jatah yang akan digunakan; informasi tersebut mengikuti Puter.

### Memilih model tanpa harus menghafal semuanya

Keterangan singkat di kartu membantu memilih:

- **GPT Image 2.5 Flare:** titik awal umum dengan label cepat dan seimbang.
- **GPT Image 2.5 Sunburst:** pilihan berorientasi detail.
- **FLUX.2 Klein 4B:** pilihan untuk artwork.
- **Gemini 3.1 Flash Image:** pilihan untuk prompt panjang dan acuan.
- **Grok Imagine 2.0:** pilihan kreatif dan komposisi.
- **Seedream 5 Pro:** pilihan realistis dan detail.
- **Qwen Image:** pilihan untuk poster dan teks; tetap periksa ejaannya.
- **Leonardo Lucid Origin:** desain dan ilustrasi pada mode Generate.

Katalog juga mengenal **GPT Image 2** dan **Seedream 5 Flash**. Flash baru muncul jika layanan Puter mengembalikannya sebagai tersedia. Daftar ini menjelaskan pilihan dalam source; ketersediaan nyata tetap mengikuti layanan saat dibuka.

## 4. Setelah gambar muncul

| Tombol | Apa yang terjadi |
| --- | --- |
| **Lihat penuh** | Membuka preview besar. Tutup dengan tombol tutup atau Escape di desktop. |
| **Unduh** | Mengunduh hasil yang sudah dibuat. Format file mengikuti gambar hasil layanan. |
| **Buat lagi** | Menjalankan permintaan generasi baru memakai pengaturan yang sedang ada. Ini menggunakan layanan AI lagi. |
| **Edit gambar** | Menyiapkan hasil sebagai gambar sumber pada mode Edit. Tulis perubahan, lalu jalankan saat siap. |
| **Jadi reference** | Menyiapkan hasil sebagai acuan pada mode Reference. |
| **Buat variasi** | Menyiapkan hasil sebagai acuan dan mengisi arahan variasi. Pada versi ini tombol tersebut menyiapkan formulir; tekan tombol pembuatan untuk menjalankannya. |
| **Edit prompt** | Mengarahkan kembali ke kolom prompt agar bisa diedit. |
| **Salin prompt** | Menyalin prompt hasil terakhir, atau isi kolom jika belum ada hasil terakhir. |

Simpan hasil yang ingin dipakai sebelum menutup tool. Studio tidak menyediakan riwayat proyek gambar permanen di Nexora.

## 5. Jika belum berhasil

| Gejala | Yang dapat dilakukan |
| --- | --- |
| Tombol masih menyiapkan atau Puter belum tersedia | Tunggu pemuatan awal; periksa koneksi dan pemblokir iklan. |
| Login tidak terbuka | Izinkan pop-up untuk situs Nexora, lalu tekan Hubungkan lagi. |
| Diminta konfirmasi email Puter | Selesaikan konfirmasi melalui Puter. |
| Edit atau Reference belum bisa dijalankan | Pastikan satu gambar valid sudah masuk. Multi memerlukan sedikitnya dua. |
| Model tidak terlihat setelah pindah mode | Pilih model yang mendukung mode tersebut dari daftar saat ini. |
| Allowance tidak cukup | Periksa jatah akun Puter. Mengulang tombol tidak menambah jatah. |
| Terlalu banyak permintaan | Tunggu sebelum mencoba kembali. |
| Prompt ditolak aturan AI | Ubah isi permintaan agar sesuai ketentuan layanan. |
| Hasil gagal diunduh | Periksa koneksi, lalu coba Unduh dari hasil yang masih tampil. |

Jika model tidak tersedia, studio dapat mencoba satu model pengganti yang kompatibel. Baca pesan model yang benar-benar dipakai. Penggantian ini tidak berlaku untuk semua jenis error, misalnya kuota habis atau penolakan keamanan.

**Bedanya dengan Prompt Studio:** AI Image menghasilkan gambar. [Prompt Studio](promptgenerate.md) membantu menyusun tulisan instruksi yang kemudian bisa dipakai di AI Image atau layanan lain.

[Sumber antarmuka yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/puter-image.js) · [Daftar semua tool](README.md)
