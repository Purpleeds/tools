# Text FX Animation

Membuat XML animasi teks dari preset efek untuk Alight Motion. Pilihan ini cocok jika ingin memulai dari efek yang sudah disiapkan dan menyesuaikan isi tulisan.

## Langkah pemakaian

1. Isi **Teks**, misalnya “selamat datang”.
2. Pilih **Preset FX** dari daftar yang tampil.
3. Pilih **Mode: Per character** untuk efek tiap huruf, atau **Per word** untuk efek tiap kata.
4. Pilih **Font lokal** dan **Style font**.
5. Atur Font Size dalam rentang yang disediakan.
6. Pilih palet jika ingin mengganti warna preset.
7. Isi nama proyek dan nama file jika perlu.
8. Tekan Generate XML, Download, lalu impor ke Alight Motion.

## Arti pengaturan

**Per character** membuat pembagian efek lebih terperinci. Untuk tulisan panjang, jumlah lapisan dan pengolahannya bisa lebih besar daripada Per word.

**Style font** adalah ketebalan font, bukan pilihan efek animasinya. Efek ditentukan pada Preset FX.

**Font Size** pada formulir ini memiliki rentang **8–12**. Itu adalah skala yang disediakan engine ini; jangan menyamakan angkanya langsung dengan ukuran font di aplikasi desain lain.

## Warna dan riwayat

Tanpa perubahan palet, engine dapat mempertahankan warna bawaan preset. Jika memilih palet, periksa hasil warna setelah Generate. Palet custom menerima kode warna dan dibatasi 15 di browser perangkat.

Riwayat lokal menyimpan sampai 10 hasil untuk generator ini. Download All mengunduh hasil yang tersimpan, bukan membuat satu video gabungan.

## Contoh dan kendala

Mulai dengan dua kata, satu preset, dan font bawaan. Impor XML dan putar di Alight Motion sebelum membuat tulisan panjang. Bila efek tidak cocok, ubah preset lalu Generate lagi.

Hasil bukan MP4. Jika membutuhkan video final, selesaikan penyesuaian dan ekspor videonya dari Alight Motion. Untuk kontrol timing lebih banyak, lihat [2D Text Animate](text2d.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [Daftar semua tool](README.md)
