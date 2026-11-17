# 2D Text Animate / Text FX

Membuat XML animasi teks 2D untuk Alight Motion. Cocok untuk judul, intro tulisan, dan efek masuk tiap huruf atau kata.

## Percobaan pertama

1. Tulis satu atau dua baris teks pada **Teks (maks. 2 baris)**.
2. Pilih **Preset animasi**.
3. Biarkan **Aktifkan Style FX** mati dahulu agar mudah mengenali gerakan dasarnya.
4. Pilih **Layer per: Karakter** untuk efek per huruf atau **Kata** untuk efek per kata.
5. Pilih font dan warna.
6. Tekan **Generate XML**, lalu **Download** setelah hasil berhasil dibuat.
7. Impor XML ke Alight Motion dan putar proyeknya.

Contoh teks: “NEXORA” pada baris pertama dan “CREATIVE” pada baris kedua.

## Pengaturan utama

| Pengaturan | Artinya |
| --- | --- |
| **Preset animasi** | Pola gerakan yang digunakan. |
| **Style FX** | Gaya efek tambahan; aktifkan saklarnya jika ingin diterapkan. |
| **Font lokal / Style font** | Jenis huruf dan ketebalan, misalnya 400 lebih tipis daripada 700. |
| **Ukuran font** | Ukuran tulisan pada pengaturan engine, bukan ukuran preview halaman. |
| **Spacing / Line height** | Jarak antarhuruf dan jarak antarbaris. |
| **Stagger (ms)** | Jeda mulai antara huruf atau kata. 1.000 ms = 1 detik. |
| **Spread (ms)** | Pengaturan sebaran waktu mulai pada animasi. |
| **Durasi layer / Extend layer** | Lama keberadaan lapisan dan pilihan memperpanjangnya. |
| **Kurva Bézier** | Karakter perubahan gerak, misalnya Smooth atau Linear. |
| **Random (%) / Seed** | Variasi waktu yang disediakan engine dan angka acuan variasinya. |

Untuk awal, gunakan waktu bawaan dan ubah Stagger saja jika ingin huruf muncul lebih rapat atau lebih renggang.

## Warna dan hasil

**Single** menggunakan warna tunggal. Mode Linear, Mirror, dan Repeat membagi warna dari palet dengan pola berbeda. **Repeat every** mengatur interval pengulangan ketika mode terkait dipakai.

Pilih palet bawaan atau tambahkan warna seperti “#7C3AED, #22D3EE, #FFFFFF”. Maksimal 15 palet custom disimpan di browser. Riwayat lokal menyimpan sampai 10 hasil per generator; Download All dapat memicu beberapa unduhan.

Nama project Alight Motion dan nama file download dapat diatur terpisah. Preview halaman membantu memeriksa tulisan, tetapi pemeriksaan gerakan lengkap tetap dilakukan pada XML di Alight Motion. Setelah mengubah pengaturan, Generate XML lagi sebelum mengunduh hasil baru.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [Daftar semua tool](README.md)
