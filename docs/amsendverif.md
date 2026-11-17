# AM Send & Verif

Mengirim **magic link**, yaitu tautan autentikasi Alight Motion yang diterima melalui email, lalu mengirim tautan tersebut untuk diverifikasi melalui layanan yang terhubung ke Nexora.

Tool ini menangani alur autentikasi. Hasil verifikasi tidak otomatis membuktikan langganan Premium aktif.

## Sebelum mulai

Gunakan alamat email yang memang akan dipakai pada Alight Motion dan kotak masuk yang bisa kamu buka. Login Nexora jika diminta.

## Tahap 1 — Kirim Magic Link

1. Isi **Alamat email** dengan format yang benar.
2. Tekan **Kirim Magic Link** satu kali.
3. Tunggu pesan dari layanan.
4. Jika pengiriman diterima layanan, periksa inbox dan folder spam.
5. Salin tautan autentikasi lengkap dari email yang benar.

Jangan mengirim ulang hanya karena email belum terlihat beberapa detik. Nexora menerapkan jeda pengiriman; jika timeout, periksa kotak masuk dahulu karena layanan mungkin sudah menerima permintaan.

## Tahap 2 — Verifikasi Link

1. Pastikan **Email yang digunakan** sama dengan email tahap pertama.
2. Tempel magic link lengkap pada kolom **Magic link**.
3. Gunakan tautan HTTPS yang valid dari email, bukan judul email atau teks yang terpotong.
4. Tekan **Verifikasi Link**.
5. Tunggu dan baca status hasil.

Magic link dibersihkan dari formulir setelah permintaan. Jika perlu mencoba ulang, pastikan kamu memiliki tautan yang masih valid dan ikuti status layanan.

## Hasil dan batasnya

Panel hasil menjelaskan apakah permintaan diterima atau gagal menurut respons layanan yang memenuhi format. Respons HTTP 200 saja bukan bukti seluruh proses akun selesai.

Tool tidak menampilkan ID token, refresh token, atau kredensial. Tidak ada langkah untuk menyalin token hasil ke tempat lain.

**Ulangi proses** membersihkan masukan dan mengembalikan alur awal.

## Jika gagal

- Email kosong atau salah format: perbaiki sebelum mengirim.
- Link kosong atau bukan HTTPS: salin tautan lengkap dari email.
- Terlalu banyak permintaan: tunggu jeda yang diberitahukan.
- Provider belum tersedia atau timeout: periksa pesan dan inbox dahulu; jangan menekan berulang kali.
- Status diterima layanan: periksa keadaan autentikasi melalui alur Alight Motion yang sah jika diperlukan.

[Alight Motion Premium 1 Tahun](alightpremium.md) adalah tool terpisah, bukan nama lain dari fitur ini.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/am-send-verif.js) · [Daftar semua tool](README.md)
