# Vecto

Mengubah PNG, JPG, atau WebP menjadi SVG melalui **engine asli Vecto 0.4.4** di VPS Nexora. Vecto memiliki kartu dan halaman sendiri di **/vecto**, terpisah dari AUTO TRACE.

## Cara mulai

1. Buka kartu **Vecto** dan login jika diminta.
2. Pilih atau jatuhkan gambar maksimal 12 MB.
3. Mulai dengan **Style: Auto**, **Detail: Medium**, dan **Warna: Auto**.
4. Biarkan parameter engine lanjutan pada nilai awal.
5. Tekan **Buat SVG** satu kali.
6. Tunggu status selesai dan hasil Vector tersedia.
7. Bandingkan Original dan Vector, lalu unduh SVG melalui tombol hasil.

Contoh latihan yang mudah: logo PNG sederhana dengan tiga atau empat warna. Setelah alurnya dipahami, coba ilustrasi yang lebih rumit.

## Arti pengaturan utama

| Pengaturan | Kegunaan |
| --- | --- |
| **Style: Auto** | Membiarkan engine memilih penanganan sesuai input. |
| **Crisp** | Pilihan gaya untuk mencoba tepi atau bentuk yang lebih tegas. |
| **Blended** | Pilihan gaya untuk mencoba perpaduan bentuk atau warna. |
| **Photo** | Pilihan gaya yang disediakan untuk gambar foto. |
| **Detail: Low / Medium / High** | Tingkat detail yang diminta pada engine; mulai dari Medium lalu bandingkan sesuai kebutuhan. |
| **Warna: Auto** | Engine menentukan warna dalam batas Auto yang diatur. |
| **Warna: 1–64** | Meminta jumlah warna tertentu. Banyak warna tidak selalu membuat file lebih sederhana. |

Pilihan Style dan Detail adalah parameter engine, bukan penggantian versi engine. Input diproses tanpa resize atau encode ulang oleh integrasi Vecto ini.

## Parameter engine asli

Buka **Parameter engine asli** jika memerlukan kontrol lebih lanjut:

- **Auto: maks. warna:** batas warna ketika memakai Auto; rentang 1–64 dan nilai awal 16.
- **Seed:** angka awal untuk proses yang melibatkan variasi; nilai awal 1. Ubah hanya ketika ingin membandingkan variasi.
- **Geometri: Kurva asli:** pilihan normal untuk hasil kurva.
- **Poligon (debug):** pilihan bentuk poligon untuk pemeriksaan khusus; tidak perlu dipilih untuk penggunaan awal.
- **Epsilon poligon:** parameter penyederhanaan poligon; nilai awal -1 mengikuti penanganan bawaan engine.

Menaikkan semua parameter sekaligus menyulitkan perbandingan. Ubah satu hal, jalankan lagi, lalu periksa bentuk dan ukuran hasil.

## Memakai preview

- **Original / Vector:** berpindah antara gambar sumber dan hasil SVG.
- **+ / −:** memperbesar atau memperkecil tampilan.
- **Fit:** menyesuaikan tampilan ke area preview.
- Geser preview untuk melihat bagian tertentu ketika diperbesar.

Gerakan dan zoom preview tidak mengubah isi SVG unduhan. Kotak-kotak pada latar membantu memeriksa transparansi; pola itu bukan bagian dari gambar hasil.

## Menyimpan dan mengatasi kendala

Unduh SVG sebelum menekan **Bersihkan** atau meninggalkan halaman. File hasil memakai SVG dari engine yang telah diperiksa identitas dan hash-nya.

Jika Buat SVG belum aktif, pastikan gambar sudah dipilih, layanan terkonfigurasi, dan tidak ada pekerjaan yang masih berjalan. Jika server sibuk atau memberi batas permintaan, tunggu giliran. Jika timeout atau hash hasil ditolak, permintaan belum menghasilkan keluaran yang bisa dipakai; baca status dan coba kembali setelah penyebabnya selesai.

**Batalkan permintaan** menghentikan penantian browser; jangan menganggap itu selalu langsung menghentikan semua pekerjaan engine. Jika ingin hasil XML untuk Alight Motion, lanjutkan SVG yang sudah diperiksa ke [SVG → Alight XML](svgalight.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/vecto/page.mjs) · [Daftar semua tool](README.md)
