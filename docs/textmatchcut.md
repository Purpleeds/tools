# NEXORA Text Match Cut

Membuat video potongan koran dengan satu kata atau frasa yang posisinya dipertahankan saat halaman berganti. Preview berjalan di perangkat, sedangkan MP4 dirender di VPS Nexora.

## Percobaan pertama tanpa gambar sendiri

1. Isi **Kata / frasa**, misalnya “NEXORA”.
2. Pilih **Mode: Auto Newspaper**.
3. Pilih **Gaya Auto** atau biarkan campuran.
4. Gunakan **Jumlah klip: 12**.
5. Pilih **Timing: Durasi per cut**, lalu isi 500 ms.
6. Pilih **Rasio: 9:16**, 720p, dan 30 FPS.
7. Tekan **Putar preview** untuk memeriksa tampilan.
8. Jika sudah sesuai, tekan **Render MP4**, tunggu proses selesai, lalu putar dan unduh hasil.

Dengan 12 klip × 500 ms, durasi dasarnya sekitar 6 detik. Ini contoh pengaturan, bukan hasil video yang sudah dibuat.

## Auto Newspaper dan Custom Newspaper

**Auto Newspaper** menyusun halaman bergaya koran dari elemen yang dibuat tool.

**Custom Newspaper** memakai gambar milikmu:

1. Pindah ke Custom Newspaper.
2. Unggah gambar yang ingin dipakai. Maksimal delapan gambar; setiap gambar maksimal 5 MB dan 12 megapiksel.
3. Pilih masing-masing gambar.
4. Pada area pemilih, tandai letak kata yang akan dipertahankan. Bisa digeser dengan sentuhan atau diatur lewat X, Y, Lebar, dan Tinggi dalam persen.
5. Periksa semua gambar, lalu putar preview.

**Tool tidak mencari letak kata dengan OCR.** Menulis kata pada formulir tidak otomatis menandai lokasinya pada foto. Jika area belum dipilih dengan benar, render Custom dapat ditolak.

## Pengaturan yang paling berpengaruh

| Pengaturan | Artinya |
| --- | --- |
| **Kata / frasa** | Teks pusat perhatian; 1–32 karakter Latin. Kapitalisasi dipertahankan. |
| **Jumlah klip** | Banyaknya potongan halaman, 2–24. |
| **Intensitas** | Gaya gerakan Smooth, Classic, Fast, atau Aggressive. |
| **Durasi per cut** | Lama setiap potongan dalam milidetik. 1.000 ms = 1 detik. |
| **BPM manual / 1 beat** | Setiap potongan mengikuti satu ketukan dari BPM yang kamu isi. |
| **Rasio** | 9:16 tegak, 16:9 mendatar, atau 1:1 persegi. |
| **Highlight** | Kotak, garis bawah, atau tanpa penanda kata. |
| **Warna** | Warna highlight. |
| **Zoom, pan & gerakan kamera** | Menambahkan gerak tampilan. |
| **Seed layout / Acak halaman** | Memilih variasi susunan halaman. |

Contoh BPM: 120 BPM berarti satu ketukan sekitar 0,5 detik. Dengan 12 klip, durasinya sekitar 6 detik.

## Menambahkan musik

1. Unggah MP3, WAV PCM, atau M4A AAC melalui bagian audio.
2. Putar audio preview agar file yang dipilih benar.
3. Atur BPM manual atau durasi cut sesuai musik.
4. Render MP4; audio ikut digabungkan dalam hasil.

Batas audio pada formulir adalah 10 MB dan 10 menit. **Tidak ada deteksi beat otomatis.** Mengunggah lagu tidak otomatis menyelaraskan semua potongan dengan ketukannya.

## Ekspor dan kendala

30 FPS adalah pilihan awal yang lebih ringan. Pilihan 60 FPS dibatasi sampai 6 detik. Resolusi awal yang disarankan 720p; gunakan pilihan yang benar-benar tersedia di halaman.

**Preview siap** tidak selalu berarti render server aktif. Jika tertulis Render VPS belum aktif, preview masih dapat dipakai tetapi MP4 belum bisa dibuat. Saat status Queued, tunggu giliran; saat Rendering, jangan memulai pekerjaan sama berulang kali.

Jika render gagal karena waktu atau memori, kurangi durasi, jumlah klip, atau beban gambar. Untuk Custom, pastikan area kata setiap gambar valid. Hasil server bersifat sementara, jadi unduh ketika video selesai.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/text-match-cut/model.js) · [Daftar semua tool](README.md)
