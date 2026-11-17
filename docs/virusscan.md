# Nexora Virus Scan

Memeriksa ciri yang patut dicurigai pada URL, file, hash, domain, atau IP **secara lokal di browser**. Ini bukan pemindaian banyak antivirus cloud atau pemeriksaan reputasi internet lengkap.

Pemeriksaan lokal berarti tool melihat ciri yang dapat diperiksa dari masukan, misalnya ekstensi ganda, jenis file, atau susunan URL.

## Pilih menu dan jalankan

| Menu | Masukan | Yang diperiksa |
| --- | --- | --- |
| **URL** | Tautan HTTP/HTTPS. | Susunan tautan, HTTPS, IP langsung, encoding, ekstensi unduhan, dan ciri lain. |
| **File** | File yang didukung, maksimal 32 MB. | Nama/ekstensi, jenis file, signature dasar, dan pola pada sampel. |
| **Hash** | MD5, SHA-1, atau SHA-256. | Keabsahan format hash; bukan daftar malware cloud. |
| **Domain** | Nama domain. | Susunan nama dan ciri lokal yang dapat dianalisis. |
| **IP** | IPv4 atau IPv6. | Format dan klasifikasi jaringan. |

1. Pilih tab sesuai masukan.
2. Isi atau pilih file.
3. Tekan **Analisis URL**, **Analisis File**, **Validasi Hash**, atau tombol menu terkait.
4. Baca tingkat risiko **bersama detail pemeriksaannya**.
5. Simpan melalui Download JSON atau Bagikan Ringkasan jika perlu.

## Cara memahami hasil

- **LOW:** sedikit ciri risiko yang ditemukan oleh pemeriksaan ini; bukan bukti bersih dari malware.
- **MEDIUM / HIGH:** ada ciri yang perlu diperiksa lebih lanjut; bukan vonis pasti bahwa file berbahaya.
- **UNKNOWN:** belum dapat ditentukan oleh pemeriksaan yang tersedia.

Contoh: nama “foto.jpg.exe” dapat memunculkan penanda ekstensi ganda. Sebaliknya, file yang namanya normal tetap bisa berbahaya meskipun pola lokal tidak menemukannya.

## Khusus Hash

Masukkan hash heksadesimal yang benar:

- MD5: 32 karakter.
- SHA-1: 40 karakter.
- SHA-256: 64 karakter.

Hash valid hanya berarti susunannya benar. Tool tidak menghubungkan hash itu ke database ancaman, sehingga hasil risikonya tetap UNKNOWN. **Validasi Hash** tidak sama dengan “file ini aman”.

## Batas yang perlu dipahami

File tidak diunggah untuk analisis ini dan tidak dijalankan oleh pemindai. Analisis file hanya menggunakan ciri serta sampel yang dibaca, bukan membuka seluruh perilaku program atau membongkar setiap isi arsip secara menyeluruh.

Menu URL tidak otomatis mengunjungi seluruh situs dan memeriksa semua unduhan di dalamnya. Menu IP juga tidak mendeteksi siapa pemilik pribadi alamat tersebut.

Jika format ditolak, periksa masukan dan batas file. Jika tertulis engine lokal gagal dimuat, gunakan Coba lagi atau buka ulang setelah aset tersedia. Untuk file yang benar-benar akan dijalankan, gunakan juga perlindungan keamanan perangkat yang sesuai.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/apps/virus-scan/engine.js) · [Daftar semua tool](README.md)
