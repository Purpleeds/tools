# Nexora OCR Intelligence

Mengambil tulisan dari foto atau PDF agar bisa disalin dan dicari. **OCR** berarti pembacaan tulisan pada gambar; hasilnya tetap perlu dikoreksi jika sumber buram atau sulit dibaca.

## Cara mulai

1. Tambahkan JPG, PNG, GIF, BMP, TIFF, atau PDF **maksimal 1 MB**.
2. Jika ingin mengambil foto baru, gunakan **Kamera** lalu ikuti pemilih kamera browser/perangkat.
3. Pilih **Bahasa dokumen** yang tersedia, atau Auto detect.
4. Untuk percobaan pertama, gunakan **Engine 2 · balanced**.
5. Aktifkan Searchable PDF atau Table mode jika dibutuhkan.
6. Tekan **Ekstrak & analisis**.
7. Baca hasil sambil membandingkan dengan dokumen asli.
8. Gunakan Copy, TXT, JSON, atau unduhan PDF jika hasilnya tersedia.

## Pilihan yang perlu dipahami

| Pilihan | Kegunaan |
| --- | --- |
| **Engine 2 · balanced** | Pilihan awal yang seimbang. |
| **Engine 3 · handwriting** | Mencoba pekerjaan dengan tulisan tangan; ketepatannya tidak dijamin. |
| **Engine 1 · fastest** | Pilihan yang berorientasi kecepatan. |
| **Searchable PDF** | Meminta PDF dengan lapisan teks agar tulisan hasil OCR bisa dicari. |
| **Table mode** | Membantu penanganan susunan tabel, invoice, atau struk. |
| **Cari di dokumen** | Mencari kata dalam teks hasil yang sudah dibaca. |

Daftar bahasa mengikuti pilihan yang benar-benar ada di formulir. Bahasa Indonesia tidak dicantumkan sebagai pilihan tersendiri pada antarmuka ini; gunakan pilihan yang sesuai atau coba Auto detect, lalu periksa hasilnya.

## Contoh

Untuk struk belanja, unggah foto yang lurus dan terbaca, pilih Table mode, lalu Ekstrak & analisis. Periksa terutama angka harga, jumlah, dan pemisah desimal.

Untuk scan dokumen yang ingin dapat dicari, aktifkan Searchable PDF sebelum memproses. Hasilnya bukan otomatis dokumen Word dengan tata letak yang sama.

## Jika hasil kurang baik

Ambil foto dengan cahaya rata, hindari bayangan dan kemiringan besar, lalu coba ulang. Jangan menurunkan ukuran sampai huruf tidak terbaca hanya demi batas file.

Jika PDF atau gambar melebihi 1 MB, siapkan bagian yang dibutuhkan dalam file lebih ringan. Jika hanya ingin meringkas isi setelah teks terbaca, gunakan [Document AI](documentai.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/ocr-intelligence.js) · [Daftar semua tool](README.md)
