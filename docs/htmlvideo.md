# HTML / WebGL to MP4

Mengubah satu dokumen HTML beserta animasi tampilannya menjadi video MP4. Cocok untuk animasi judul, efek visual HTML/CSS, shader WebGL, atau adegan Three.js yang bisa dijalankan browser.

## Apa yang harus disiapkan?

Siapkan **HTML lengkap**, bukan hanya potongan kalimat atau kode CSS. Dokumen sebaiknya memuat struktur halaman serta CSS dan JavaScript yang diperlukan.

Jika dokumen memakai gambar, font, atau pustaka dari internet, pastikan aset dapat dimuat oleh preview. File yang hanya ada di folder komputermu tidak otomatis ikut tersedia saat kode ditempel.

## Langkah pemakaian

1. Buka **HTML / WebGL to MP4**.
2. Tempel dokumen pada editor atau gunakan **Pilih .html**.
3. Tekan **Jalankan pratinjau**.
4. Tunggu hingga tampilan terlihat dan status preview siap.
5. Periksa apakah semua gambar, huruf, dan animasi muncul.
6. Tekan **Buat Video** ketika preview sudah diterima.
7. Tunggu perekaman dan encoding selesai.
8. Putar hasil untuk memeriksa gerakannya, lalu unduh MP4 melalui aksi hasil.

Jika ada bagian hilang pada preview, perbaiki HTML atau asetnya dahulu. Ekspor tidak otomatis membangun kembali halaman yang belum berhasil ditampilkan.

## Contoh HTML sederhana

Tempel contoh berikut sebagai satu dokumen:

~~~html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<style>
html, body { margin: 0; height: 100%; }
body {
  display: grid; place-items: center;
  background: #080808; color: #c084fc;
  font: bold 72px Arial;
}
h1 { animation: naik 2s ease-in-out infinite alternate; }
@keyframes naik {
  from { transform: translateY(30px); opacity: .4; }
  to { transform: translateY(-30px); opacity: 1; }
}
</style>
</head>
<body><h1>NEXORA</h1></body>
</html>
~~~

Ini contoh latihan untuk mengenali alur preview dan ekspor. Ganti teks, warna, dan gerakan setelah alurnya dipahami.

## Batas penting

- Engine pada versi ini menyiapkan **8 detik, 30 FPS, 240 frame**, lalu MP4 H.264.
- Preview, pengambilan frame, dan encoding berjalan di browser. Perangkat tetap perlu cukup memori dan kemampuan grafis.
- **Hentikan** menghentikan tampilan preview yang aktif.
- Mengedit dokumen memerlukan pemeriksaan preview lagi sebelum membuat video.
- Tool ini mengubah tampilan halaman; ia bukan perekam layar seluruh HP dan tidak otomatis memasukkan semua isi website dari sebuah URL.
- Dukungan WebGL, font, aset jaringan, dan codec mengikuti perangkat/browser.

Jika pembuatan terasa berat, coba contoh HTML sederhana dahulu. Jika contoh bisa tetapi proyekmu gagal, periksa aset luar, error kode, atau kerumitan adegan. Untuk membuat video dari deskripsi AI, gunakan [AI Video Generator](aivideo.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/html-video-engine/src/app.tsx) · [Daftar semua tool](README.md)
