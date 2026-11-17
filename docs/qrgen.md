# QR Generator

Membuat QR untuk beberapa jenis informasi. Pilih jenis yang benar agar aplikasi pemindai dapat memahami isinya, bukan hanya menampilkan tulisan mentah.

## Cara mulai untuk tautan website

1. Pilih **Tautan** pada jenis QR.
2. Isi alamat website tujuan.
3. Biarkan warna QR gelap dan background terang.
4. Pilih ukuran ekspor.
5. Tekan **Buat QR**.
6. Pindai dengan kamera HP lain untuk memastikan tujuan benar.
7. Simpan melalui **Unduh PNG** atau **Unduh SVG**.

## Pilih jenis QR

| Jenis | Yang diisi | Saat dipindai |
| --- | --- | --- |
| **Tautan** | URL website. | Membuka atau menawarkan tautan. |
| **Teks** | Pesan atau informasi. | Menampilkan tulisan. |
| **Wi-Fi** | Nama jaringan, jenis keamanan, dan password jika ada. | Membantu menghubungkan jaringan pada perangkat yang mendukung. |
| **WhatsApp** | Nomor dengan kode negara dan pesan awal opsional. | Membuka percakapan WhatsApp. |
| **Email** | Alamat, subjek, dan isi opsional. | Menyiapkan email; tidak mengirim otomatis. |
| **Kontak** | Nama dan data kontak yang diminta. | Menyiapkan informasi kontak untuk disimpan. |

Untuk nomor Indonesia pada WhatsApp, gunakan awalan kode negara **62** sesuai petunjuk, bukan menebak nomor tanpa kode negara.

QR Wi-Fi berisi informasi jaringan termasuk kata sandi yang diperlukan. Berikan QR tersebut kepada orang yang memang boleh mengakses jaringan.

## Tampilan dan koreksi kesalahan

**Ukuran ekspor** tersedia 512, 1024, atau 2048 piksel untuk hasil raster. **SVG** cocok ketika gambar perlu diperbesar pada desain yang mendukung vektor.

**Koreksi kesalahan** L/M/Q/H mengatur ketahanan QR terhadap sebagian kerusakan. M adalah titik awal seimbang; tingkat lebih tinggi memakai ruang lebih banyak, sehingga kode dapat lebih padat.

Gunakan kontras yang baik. Warna yang terlalu mirip antara QR dan latar dapat menyulitkan pemindaian. Tampilan indah belum membuktikan QR dapat dibaca; selalu uji pindai hasil unduhan.

## Hasil dan kendala

**Salin gambar** menyalin gambar bila clipboard browser mendukungnya. **Salin isi** hanya menyalin data yang dimasukkan. Pembuatan berlangsung lokal; isi tidak dikirim ke server untuk membuat QR.

QR ini bukan layanan pengalihan dinamis. Untuk mengganti tujuan, buat QR baru; file lama tidak otomatis ikut berubah.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/vendor/qr-generator-engine.js) · [Daftar semua tool](README.md)
