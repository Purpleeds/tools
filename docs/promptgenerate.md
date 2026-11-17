# Nexora Prompt Studio

Membantu mengubah ide menjadi instruksi AI yang lebih lengkap dan terarah. Hasil utamanya adalah **teks prompt**, bukan gambar atau video. Prompt tersebut kemudian disalin ke layanan pembuat gambar atau video yang kamu gunakan.

**Prompt** berarti arahan untuk AI. **Reference** berarti gambar contoh. **Blueprint** berarti rincian rencana visual, seperti subjek, latar, cahaya, dan komposisi.

## 1. Percobaan pertama: buat prompt gambar sederhana

1. Pilih mode **Image**.
2. Pada **Apa yang ingin kamu buat?**, tulis:

   > Poster minuman kopi susu untuk promosi kedai. Botol kopi berada di tengah meja kayu, cahaya pagi hangat, warna cokelat krem. Sisakan bagian atas untuk judul.

3. Pilih **Style: Photorealistic** atau biarkan **Auto**.
4. Pilih **Aspect ratio: 4:5** untuk poster tegak.
5. Biarkan pengaturan **Basic**. Tidak perlu membuka semua pengaturan.
6. Pada **Target profile**, pilih **Universal** jika belum tahu akan memakai model apa.
7. Pilih **Language** sesuai bahasa prompt yang ingin diterima.
8. Tekan **Generate Prompt**.
9. Baca hasil **Production Prompt**, lalu tekan **Copy** atau **Copy Prompt**.
10. Buka [Nexora AI Image](aiimage.md) atau layanan gambar pilihanmu, tempel prompt, lalu buat gambar di sana.

Langkah terakhir penting: menekan Generate Prompt di studio ini belum menghasilkan gambar.

## 2. Memilih workflow

Enam pilihan utama tampil sebagai tombol. Pilihan lain ada pada **Workflow lainnya**. Pilih berdasarkan pekerjaan yang ingin dilakukan, bukan hanya berdasarkan nama AI tujuan.

| Workflow | Kegunaan | Gambar referensi |
| --- | --- | --- |
| **Image** | Menulis prompt gambar dari ide. | Tidak digunakan. |
| **Video** | Menulis arahan gerakan dari gambar yang sudah ada. | 1–4 gambar. |
| **Edit** | Menyusun arahan untuk mempertahankan dan mengubah bagian gambar. | 1–4 gambar. |
| **Reverse** | Membaca gambar menjadi uraian dan prompt. | 1–4 gambar. |
| **Product** | Menyusun foto produk atau materi iklan. | Opsional, sampai 4. |
| **Character** | Menyusun arahan dengan ciri karakter yang konsisten. | 1–4 gambar. |
| **Text → Video** | Merancang adegan video dari tulisan. | Tidak digunakan. |
| **Image Edit** | Menyusun instruksi pengeditan gambar. | 1–4 gambar. |
| **Style Transfer** | Memisahkan gambar subjek dan contoh gaya yang ingin ditiru. | 2–4 gambar, termasuk acuan berperan Style. |
| **First → Last** | Merencanakan perubahan dari frame awal ke frame akhir. | Tepat 2 gambar: Start Frame dan End Frame. |
| **Storyboard** | Menyusun beberapa adegan yang saling berhubungan. | Opsional, sampai 4. |
| **Photography** | Membuat prompt fotografi dengan arahan kamera dan cahaya. | Opsional, sampai 4. |
| **Anime** | Menyusun arahan ilustrasi anime. | Opsional, sampai 4. |
| **3D / CGI** | Menyusun arahan render, material, dan objek tiga dimensi. | Opsional, sampai 4. |
| **Architecture** | Menyusun gambar bangunan atau interior. | Opsional, sampai 4. |
| **Enhance Prompt** | Memperjelas prompt yang sudah kamu punya. | Tidak digunakan. |
| **Convert Target** | Menyesuaikan prompt untuk layanan AI lain. | Tidak digunakan. |
| **Prompt Debugger** | Memeriksa konflik atau kekurangan dalam prompt. | Opsional, sampai 4. |

Jika mode wajib memakai gambar, tombol belum dapat dipakai sampai syarat gambar terpenuhi. Keterangan dekat tombol menjelaskan apa yang kurang.

## 3. Menambahkan reference dengan benar

1. Pilih workflow yang mendukung reference.
2. Tekan **Tambah** atau area **Tap atau jatuhkan gambar di sini**.
3. Pilih JPG, PNG, atau WebP. Maksimal empat gambar secara umum; mode First → Last hanya dua.
4. Setiap file sumber maksimal 12 MB. Studio mengecilkan gambar lokal sebelum dikirim; jika masih terlalu besar, pilih file yang lebih ringan.
5. Periksa gambar yang masuk, lalu tentukan perannya pada pilihan di kartu gambar.
6. Tulis arahan yang menjelaskan hubungan gambar dan hasil yang diinginkan.

| Peran reference | Maksudnya |
| --- | --- |
| **Subject** | Orang, produk, hewan, atau objek yang menjadi subjek utama. |
| **Style** | Acuan gaya gambar, warna, atau perlakuan visual. |
| **Composition** | Acuan penataan posisi objek dan sudut pandang. |
| **Environment** | Acuan tempat atau suasana latar. |
| **Start Frame** | Tampilan yang menjadi awal video pada First → Last. |
| **End Frame** | Tampilan yang menjadi akhir video pada First → Last. |

Contoh Style Transfer: gambar pertama adalah foto sepatu, gambar kedua ilustrasi cat air. Beri peran **Subject** pada sepatu dan **Style** pada ilustrasi. Tulis “pertahankan bentuk sepatu, gunakan sapuan cat air seperti acuan gaya.”

Gambar hanya berperan sebagai bahan analisis penyusunan prompt. Jika nanti memakai AI lain, layanan tersebut mungkin tetap memerlukan gambar yang sama diunggah kembali.

## 4. Apa yang perlu diisi?

### Ide dan preset

Kolom ide dibatasi 4.000 karakter. Untuk workflow berbasis tulisan, isi sedikitnya tiga karakter; sebaiknya berupa kalimat yang jelas.

Pola yang mudah:

> Apa subjeknya + sedang apa + di mana + gaya visual + pencahayaan + hal yang wajib dipertahankan atau dihindari.

Preset seperti **Portrait**, **Commercial**, **Perfume**, atau **TikTok 9:16** memberi arah awal. Preset tidak menggantikan penjelasan idemu. Tetap baca pilihan Style dan Aspect ratio setelah memilihnya.

### Style dan Aspect ratio

**Style** mengatur arah visual: misalnya Photorealistic untuk tampilan foto, Anime untuk ilustrasi anime, atau Vector Art untuk gaya grafis vektor.

**Aspect ratio** mengatur bentuk bingkai. Gunakan 1:1 untuk persegi, 4:5 untuk poster tegak, 9:16 untuk video HP, atau 16:9 untuk video mendatar. Auto membiarkan penyusunan menyesuaikan konteks.

Memilih Vector Art menghasilkan arahan bergaya vektor; itu tidak menjamin generator gambar tujuan mengeluarkan file SVG. Untuk konversi gambar menjadi SVG, gunakan [Vecto](vecto.md) atau [AUTO TRACE](imagevectorizer.md).

## 5. Basic, Advanced, dan Pro

Ketiganya membuka kelompok pengaturan. Mulai dengan Basic, lalu buka kelompok lain hanya jika dibutuhkan. Sebagian kontrol hanya muncul pada workflow tertentu.

### Basic: pilihan dasar

| Kolom | Cara memakainya |
| --- | --- |
| **Subject** | Jenis subjek: orang, karakter, produk, kendaraan, bangunan, dan sebagainya. Auto boleh digunakan jika belum perlu spesifik. |
| **Detail** | Clean untuk arahan lebih bersih, Balanced untuk seimbang, Detailed atau Maximum untuk rincian lebih banyak. |

### Advanced: arah visual

| Kolom | Penjelasan sederhana |
| --- | --- |
| **Shot** | Seberapa dekat kamera: Close-up untuk wajah atau detail; Full body untuk seluruh tubuh; Wide untuk lingkungan yang luas. |
| **Lighting** | Sumber atau suasana cahaya: Natural, Golden hour, Studio, Neon, dan pilihan lainnya. |
| **Composition** | Penataan gambar: Centered untuk subjek di tengah; Rule of thirds untuk penempatan menyamping; Negative space untuk ruang kosong. |
| **Mood** | Suasana, misalnya tenang, ceria, tegang, atau mewah. |
| **Palette** | Warna utama, misalnya “krem, cokelat kopi, putih hangat”. |
| **Preserve / Do not drift** | Bagian dari reference yang ingin tetap: wajah, pose, pakaian, latar, dan sebagainya. |
| **Transform** | Bagian yang ingin diubah: gaya, tempat, pencahayaan, pakaian, dan sebagainya. |

Hindari memilih bagian yang sama untuk dipertahankan dan diubah tanpa penjelasan. Contohnya, jangan meminta pakaian tetap sama sekaligus diganti total.

Pada mode **Product**, tersedia pengaturan tambahan:

- **Product type:** jenis produk, misalnya parfum atau sepatu.
- **Output variant:** arah hasil, seperti Product Hero, Social Ad, atau Clean E-commerce.
- **Pedestal / support:** alas atau tempat produk.
- **Reflections / material:** pantulan dan sifat permukaan.
- **Background:** latar yang diinginkan.
- **Safe zones:** ruang kosong untuk headline atau logo. Ini menyiapkan ruang, bukan otomatis memasang logo.

Pada workflow video, tersedia arahan gerakan:

- **Subject motion:** gerak subjek, misalnya berjalan atau menoleh.
- **Camera motion:** gerak kamera. Pan berarti menoleh mendatar; Dolly in mendekat dengan kamera; Orbit mengitari subjek.
- **Environment:** gerak lingkungan, misalnya hujan, angin, atau asap.
- **Speed:** kecepatan gerak yang diinginkan.
- **Stability:** kamera diam, stabil, handheld, atau dinamis.
- **Duration intent:** durasi yang ingin disebut dalam prompt.
- **Motion strength:** kuat-lemahnya arahan gerakan.

Durasi dan gerakan di sini adalah **isi instruksi**. Kemampuan sebenarnya mengikuti layanan video tempat prompt dijalankan.

### Pro: detail khusus

- **Camera angle:** contoh “eye level” untuk sejajar mata atau “low angle” untuk pandangan dari bawah.
- **Focal length:** contoh “50mm” untuk arahan karakter lensa.
- **Aperture / depth:** contoh “f/2.8, latar lembut” untuk kedalaman fokus.
- **Realism:** tingkat tampilan realistis atau bergaya.
- **Exact text:** tulisan yang harus dimasukkan secara persis dalam instruksi.
- **Font character:** sifat huruf, misalnya sans-serif tebal.
- **Placement:** letak tulisan, misalnya bagian atas.
- **Timeline builder:** arahan per bagian waktu untuk workflow video. Aktifkan, lalu isi adegan pada kolom waktu yang tersedia.

Exact text membantu mempertahankan ejaan dalam prompt. AI gambar tujuan tetap dapat salah menggambar huruf; periksa hasil akhirnya.

## 6. Target profile, Language, dan Negative prompt

**Target profile** memberi tahu studio bagaimana menyusun prompt:

- Untuk gambar: Universal, Midjourney, FLUX, Stable Diffusion / SDXL, atau Ideogram.
- Untuk video: Universal Video, Runway, Veo, Kling, Hailuo, atau Luma.

Pilih target yang sesuai dengan layanan yang akan kamu gunakan. Memilih target bukan berarti studio telah menghubungkan akun atau menjalankan generasi pada layanan itu.

**Language** memilih bahasa prompt hasil: English atau Bahasa Indonesia. Ide awal tetap dapat ditulis dengan bahasa yang kamu pahami.

**Negative prompt** berisi hal yang ingin dihindari, misalnya “teks acak, objek ganda, gambar buram”. Pilihan ini hanya tampil untuk target yang kompatibel. Salin ke kolom negatif layanan tujuan jika layanan tersebut menyediakan kolom terpisah.

## 7. Contoh pekerjaan yang lebih rumit

### Membuat arahan video dari foto produk

1. Pilih **Video** dan tambahkan satu foto produk.
2. Tulis:

   > Kamera mendekati botol parfum secara perlahan. Pertahankan bentuk botol, label, warna, dan susunan latar. Tambahkan pantulan cahaya halus, tanpa mengubah produk.

3. Pada Advanced, pilih **Camera motion: Dolly in**, **Subject motion: Still**, dan kecepatan **Slow**.
4. Pilih rasio serta Target profile layanan video yang akan dipakai.
5. Generate Prompt, salin hasilnya, lalu gunakan bersama foto produk pada layanan video tersebut.

### Merencanakan dua frame

1. Pilih **Workflow lainnya → First → Last**.
2. Tambahkan dua gambar: keadaan awal dan keadaan akhir.
3. Pastikan peran **Start Frame** dan **End Frame** benar.
4. Jelaskan bagaimana perubahan berlangsung, termasuk bagian yang harus konsisten.
5. Generate Prompt lalu baca bagian Motion Plan dan Continuity Notes jika tersedia.

## 8. Membaca dan menggunakan hasil

| Bagian hasil | Untuk apa |
| --- | --- |
| **Production Prompt** | Teks utama yang disalin ke AI tujuan. |
| **Negative Prompt** | Arahan yang dihindari, bila target mendukung. |
| **Parameters** | Pengaturan yang disusun untuk target. |
| **Visual Blueprint** | Uraian subjek, tempat, kamera, cahaya, warna, dan gaya. |
| **Motion Plan** | Rencana gerakan untuk video, jika ada. |
| **Continuity Notes** | Pengingat agar identitas, pakaian, latar, atau arah gerak konsisten. |
| **Warnings & Diagnostics** | Konflik atau hal yang perlu diperiksa. |
| **Meaningful Variants** | Alternatif prompt; masing-masing dapat disalin. |
| **Prompt Quality** | Skor kelengkapan unsur prompt, bukan peluang kebenaran atau jaminan kualitas gambar. |

**Improve**, **More Cinematic**, **More Realistic**, dan pilihan Refine lain menjalankan penyusunan ulang. Gunakan ketika memang ingin perubahan; itu merupakan permintaan AI baru.

Untuk menyimpan:

- **Copy Prompt:** hanya teks prompt utama.
- **Copy All:** teks gabungan hasil yang tersedia.
- **TXT / Markdown / JSON:** unduhan sesuai format yang dipilih.
- **History:** sampai 20 hasil di browser perangkat tersebut, dengan Open, Duplicate, dan Favorite.

History dan ekspor permintaan tidak menyimpan isi gambar reference. **Duplicate** mengisi kembali ide dan workflow, bukan memulihkan seluruh pengaturan dan semua gambar secara lengkap.

## 9. Jika tombol belum aktif atau hasil belum muncul

- **Tulis ide sedikitnya 3 karakter:** lengkapi kolom ide.
- **Tambahkan reference:** unggah jumlah gambar yang diwajibkan workflow.
- **Tetapkan Start Frame dan End Frame:** perbaiki peran kedua gambar.
- **Tambahkan reference dengan role Style:** ubah peran salah satu acuan menjadi Style.
- **Reference terlalu besar:** pilih gambar lebih ringan; format yang diterima JPG, PNG, dan WebP.
- **Engine belum dikonfigurasi:** layanan AI pada Nexora belum siap; mengganti isi prompt tidak memperbaiki konfigurasi tersebut.
- **Prompt ada tetapi gambar belum ada:** salin prompt ke [AI Image](aiimage.md) atau layanan tujuan untuk membuat gambar.

[Sumber antarmuka yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/prompt-generator.js) · [Daftar semua tool](README.md)
