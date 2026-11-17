# Nexora Document AI

Membantu membaca dokumen melalui ringkasan, analisis, catatan belajar, pengambilan tabel, dan tanya jawab tentang isinya.

## Bahan yang dapat dipakai

Formulir menerima **PDF, JPG, PNG, WebP, TXT, MD, dan CSV**. Dokumen maksimal **3 MB**; foto kamera dapat sampai **12 MB sebelum optimasi**. Gambar besar akan disiapkan lebih ringan oleh halaman.

## Cara mulai

1. Tekan **Pilih File** dan tambahkan satu dokumen.
2. Periksa nama dan ukuran yang ditampilkan.
3. Pilih mode analisis.
4. Tekan **Analisis Dokumen**.
5. Tunggu status selesai, lalu baca tab Ringkasan, Poin, Teks, dan Tabel sesuai hasil.
6. Jika ingin bertanya lebih lanjut, buka **Tanya AI** dan tulis pertanyaan tentang dokumen tersebut.
7. Simpan bagian yang dibutuhkan melalui pilihan ekspor.

## Pilih mode sesuai tujuan

| Mode | Untuk apa |
| --- | --- |
| **Smart Summary** | Mendapat inti dokumen dan fakta penting. |
| **Deep Analysis** | Membaca konteks, risiko, dan tindakan yang disarankan. |
| **Study Notes** | Membuat catatan belajar yang lebih terstruktur. |
| **Table Extract** | Mengambil data tabel agar dapat ditinjau atau disimpan sebagai CSV. |

Contoh: untuk materi kuliah, pilih Study Notes. Untuk laporan yang ingin dibaca cepat, pilih Smart Summary. Untuk tabel penjualan, coba Table Extract lalu bandingkan angka dengan sumber.

## Bertanya tentang dokumen

Analisis dokumen dahulu. Setelah hasil tersedia, tulis pertanyaan spesifik seperti:

> Apa tiga kesimpulan utama dalam dokumen ini? Sebutkan bagian yang mendukungnya.

Pertanyaan yang mengacu pada bagian tertentu lebih mudah diperiksa daripada “jelaskan semuanya”. Jika mengganti dokumen, lakukan analisis terhadap dokumen baru sebelum menggunakan hasilnya.

## Ekspor dan pemeriksaan

Pilihan umum meliputi **TXT**, **JSON**, dan **Word**. Tabel yang benar-benar ditemukan dapat memiliki tombol **CSV** sendiri. Word adalah keluaran laporan yang disiapkan tool, bukan jaminan tata letak asli dokumen tetap persis.

AI dapat salah membaca atau merangkum. Cocokkan nomor, tanggal, nama, dan isi tabel dengan file asli. Tidak muncul tabel bisa berarti tabel tidak ditemukan, bukan ada CSV kosong yang harus diunduh.

Jika tombol belum aktif, pastikan file berhasil dimuat. Jika ukuran ditolak, pilih file sesuai batas. Layanan AI online perlu siap; ini berbeda dari [PDF Lab Local](pdflab.md) yang mengolah struktur PDF di perangkat tanpa analisis AI.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/document-ai.js) · [Daftar semua tool](README.md)
