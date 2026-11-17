# Pilih Tool dan Ikuti Alur yang Tepat

Gunakan halaman ini jika tahu hasil yang diinginkan tetapi belum tahu harus membuka tool mana. Tautan menuju panduan langkah lengkap masing-masing tool.

## 1. Ingin membuat poster AI dari ide

1. Buka [Prompt Studio](promptgenerate.md) bila perlu bantuan menulis arahan.
2. Pilih Image, tulis ide, gunakan Target profile Universal, lalu Generate Prompt.
3. Salin Production Prompt.
4. Buka [AI Image](aiimage.md), pilih Generate, dan hubungkan Puter.
5. Tempel prompt, pilih rasio serta model yang tersedia, lalu Buat Gambar.
6. Periksa tulisan dan detail pada hasil, kemudian unduh.

Jika sudah bisa menulis instruksi sendiri, mulai langsung dari AI Image. Prompt Studio bukan langkah wajib.

## 2. Ingin mengubah foto atau memakai beberapa acuan

Di [AI Image](aiimage.md):

- **Edit:** satu gambar yang akan diubah. Tulis perubahan sekaligus bagian yang ingin tetap.
- **Reference:** satu acuan untuk membuat adegan baru dengan arah karakter atau gaya.
- **Multi:** dua sampai empat acuan sesuai batas yang tampil. Sebutkan peran gambar pertama, kedua, dan seterusnya.

Contoh arahan Multi: “karakter dari gambar pertama, pakaian dari gambar kedua, suasana dari gambar ketiga”. Jangan memakai Generate ketika berharap gambar acuan ikut dipakai; Generate tidak memerlukan input gambar.

## 3. Ingin gambar pengisi desain, bukan ilustrasi rumit

Buka [Placeholder Studio](placeholderstudio.md):

- **Classic:** warna, tulisan, dan ukuran sederhana; preview otomatis.
- **Prompt:** gambar dari deskripsi melalui layanan publik.

Periksa bagian unduhan pada panduannya. Pada versi yang diaudit, Download Classic menyimpan SVG preview, sedangkan pilihan Format juga dipakai untuk URL layanan. Jangan mengubah ekstensi SVG menjadi PNG tanpa konversi.

## 4. Ingin logo gambar bisa dipakai di Alight Motion

1. Jika sumber masih PNG/JPG/WebP, buka [Vecto](vecto.md) atau [AUTO TRACE](imagevectorizer.md) untuk membuat SVG.
2. Periksa SVG dan unduh.
3. Buka [SVG → Alight XML](svgalight.md) untuk membuat XML.
4. Impor XML ke Alight Motion dan periksa lapisannya.
5. Buat gerakan atau ekspor video dari aplikasi tersebut.

Jika SVG sudah mempunyai animasi SMIL/CSS, gunakan [SVG Animasi → Alight XML](svganimation.md). Jika hanya memerlukan template logo, [Logo Animate](logoanimate.md) memakai media contoh yang diganti setelah impor.

## 5. Ingin memisahkan objek dari latar

- [Remove Background](removebg.md): penghapusan latar dengan editor kuas untuk Hapus/Pulihkan.
- [Smart Cutout](smartcutout.md): pilih objek melalui ketukan Select + dan Remove −, kemudian Extract.
- [NEXORA Auto Cut](nexoraautocut.md): menyiapkan beberapa lapisan PNG dan XML untuk bahan animasi.

Satu PNG transparan, beberapa lapisan potongan, dan SVG adalah hasil yang berbeda. Pilih tool sesuai hasil akhir yang diperlukan.

## 6. Ingin mengolah dokumen

| Kebutuhan | Tool dan hasil |
| --- | --- |
| Tulisan menjadi PDF baru | [Auto PDF](autopdf.md): masukkan teks/bab lalu buat preview dan PDF. |
| Menggabungkan atau menyusun PDF | [PDF Lab](pdflab.md): pilih operasi, file, dan Export PDF. |
| Mengambil tulisan dari foto/scan | [OCR Intelligence](ocrintel.md): teks hasil OCR; PDF searchable jika tersedia. |
| Memahami dan bertanya tentang dokumen | [Document AI](documentai.md): ringkasan, analisis, atau jawaban AI. |

PDF Lab Add Text menambahkan tulisan; tidak otomatis mengubah paragraf asli. Document AI bukan pengganti pemeriksaan angka terhadap dokumen sumber.

## 7. Ingin membuat video atau audio

- [AI Video Generator](aivideo.md): video dari tulisan atau gambar melalui Puter.
- [HTML / WebGL to MP4](htmlvideo.md): video dari HTML yang kamu siapkan.
- [Text Match Cut](textmatchcut.md): video bergaya koran; BPM dan area kata pada gambar custom diatur manual.
- [Motion Control](motioncontrol.md): memilih layanan eksternal, lalu mengerjakannya di situs penyedia.
- [AI Song Generator](aisong.md): lagu dari deskripsi.
- [ElevenLabs Studio](elevenlabs.md): narasi, pengubahan suara, transkrip, efek suara, atau audio beserta data lip-sync.

Pada ElevenLabs Studio, Lip Sync menghasilkan WAV dan JSON waktu gerak mulut, bukan video karakter yang langsung selesai. Pada video AI, Download mengambil hasil lama; Generate Again membuat permintaan baru.

## 8. Ingin bantuan keamanan atau informasi

[Web Intelligence](webintel.md) memeriksa website; [IP & ASN Intelligence](ipintel.md) mencari informasi jaringan; [Virus Scan](virusscan.md) memeriksa ciri lokal pada masukan. Ketiganya bukan alat yang sama dan tidak membuktikan keamanan mutlak.

[BMKG](bmkg.md) memakai kode ADM4 untuk cuaca wilayah. [Space Explorer](spaceexplorer.md) membahas antariksa, bukan cuaca hujan setempat. [CariFakta](carifakta.md) memberi analisis AI yang perlu dibandingkan dengan sumber asli.

## Daftar cepat berdasarkan kebutuhan

Bagian berikut tetap mencakup semua tool agar nama lain mudah ditemukan.

## Gambar, logo, dan vektor

- Menghapus latar seluruh gambar: [Remove Background](removebg.md).
- Memilih satu objek untuk dipisahkan: [Nexora Smart Cutout](smartcutout.md).
- Memperbesar gambar: [Image HD Enhancer V4](enhancer.md) atau [Perbesar Gambar 4x](bigjpg-nexora.md).
- Mengubah gambar menjadi SVG: [Vecto](vecto.md) atau [AUTO TRACE](imagevectorizer.md). Keduanya tool terpisah dengan engine berbeda.
- Membuat avatar atau gambar pengisi desain: [Avatar Studio](avatarstudio.md) atau [Placeholder Studio](placeholderstudio.md).
- Membagikan gambar sebagai tautan: [Foto To Link](fotolink.md).

## Alight Motion

- Memindahkan SVG statis ke Alight Motion: [SVG → Alight XML](svgalight.md).
- Memindahkan SVG dengan animasi: [SVG Animasi → Alight XML](svganimation.md).
- Memisahkan gambar menjadi lapisan untuk animasi: [NEXORA Auto Cut](nexoraautocut.md).
- Membuat teks dan logo: [2D Text Animate](text2d.md), [3D Text Animate](text3d.md), [Text FX Animation](textfxanimation.md), [Text to Vector](textvector.md), [Trimpath Generator](trimpath.md), atau [Logo Animate](logoanimate.md).
- Mencari preset yang dibagikan di TikTok: [Cari Preset AM](presetfinder.md).
- Mengirim dan memverifikasi tautan autentikasi: [AM Send & Verif](amsendverif.md).
- Alur pengajuan Premium ke penyedia: [Alight Motion Premium 1 Tahun](alightpremium.md). Verifikasi autentikasi dan status langganan adalah dua hal berbeda.

## AI, suara, dan video

- Membuat gambar: [Nexora AI Image](aiimage.md). Untuk mencoba layanan dan model lain, buka [AI Image Eksperimental](aiimageexperimental.md).
- Mengubah ilustrasi anime ke gaya realistis: [Anime to Real](animetoreal.md).
- Membuat video AI: [AI Video Generator](aivideo.md).
- Membuat lagu atau mengolah suara: [AI Song Generator](aisong.md) atau [ElevenLabs Studio](elevenlabs.md).
- Menyusun instruksi AI atau memakai beberapa AI: [Prompt Studio](promptgenerate.md) atau [Multi-AI](multiai.md).
- Membuat video potongan koran: [Text Match Cut](textmatchcut.md).
- Merekam tampilan HTML menjadi video: [HTML / WebGL to MP4](htmlvideo.md).
- Mencari layanan pemindahan gerakan karakter: [Motion Control](motioncontrol.md).

## Dokumen dan tulisan

- Membuat PDF dari teks: [Nexora Auto PDF](autopdf.md).
- Menggabungkan atau mengatur PDF: [PDF Lab Local](pdflab.md).
- Mengambil teks dari foto atau PDF: [OCR Intelligence](ocrintel.md).
- Meringkas atau bertanya tentang dokumen: [Document AI](documentai.md).

## Konten, bacaan, dan game

- Mengunduh video TikTok atau Instagram: [Social Downloader](socialdownloader.md).
- Membuat kutipan atau gambar pesan: [Quote Generator](quotegenerator.md), [Windows Quotes](winquotes.md), [Nokia Message](nokiamsg.md), atau [Quote TikTok](ttquote.md).
- Membuat gambar hiburan: [Sertifikat Custom](sertifikat.md), [E-KTP Generator](ektp.md), [Fake Lobby](fakelobby.md), atau [Fake OVO](fakeovo.md). Halaman masing-masing menjelaskan bentuk simulasinya.
- Membaca komik atau sastra klasik: [Baca Komik](comicreader.md) atau [World Classics Reader](worldclassics.md).
- Menjelajahi ilustrasi anime atau GIF: [Danbooru Search](danbooru.md) atau [Anime Discover](animegallery.md).
- Melihat informasi game dan hitung winrate: [FF Tools](fftools.md) atau [ML Tools](mltools.md).

## Website dan utilitas harian

- Memeriksa website, jaringan, atau berkas: [Web Intelligence](webintel.md), [IP & ASN Intelligence](ipintel.md), atau [Virus Scan](virusscan.md).
- Mengambil HTML website atau melindungi HTML sendiri: [Get Code HTML](getcode.md) atau [Web Enkripsi V2](webencryption.md).
- Mencari tujuan tautan Safelinku: [Safelinku Bypass](safelinku.md).
- Menerima email sementara: [GenMail](genmail.md).
- Membuat kata sandi, QR, atau kode Morse: [Password Generator](pwgen.md), [QR Generator](qrgen.md), atau [Morse Code](morse.md).
- Membaca data cuaca, antariksa, atau pasar: [BMKG Indonesia](bmkg.md), [Space Explorer](spaceexplorer.md), atau [Crypto Market Scanner](cryptomarket.md).
- Membantu menilai klaim atau berita: [CariFakta](carifakta.md).

[Lihat daftar lengkap 65 tool](README.md)
