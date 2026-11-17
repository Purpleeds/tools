# Get Code HTML

Mengambil HTML halaman publik, melihat preview, dan memeriksa aset yang ditemukan. Ada juga **SiteGrabber** untuk menangkap satu halaman atau lebih banyak bagian website menjadi paket unduhan.

## Pilih pekerjaan yang dibutuhkan

| Kebutuhan | Pilihan |
| --- | --- |
| Hanya ingin melihat atau menyimpan HTML satu URL. | **Extract HTML**. |
| Ingin memeriksa link aset dan endpoint yang ditemukan. | Laporan statis dan **Run Live Audit**. |
| Ingin paket halaman beserta aset yang bisa ditangkap layanan. | **Capture via SiteGrabber X**. |

HTML halaman yang dapat dibaca publik berbeda dari kode backend atau database. Tool ini tidak memberikan isi server yang tidak dipublikasikan.

## Mengambil HTML

1. Isi alamat halaman pada kolom URL.
2. Tekan **Extract HTML**.
3. Tunggu status sukses dan kode muncul.
4. Gunakan **Copy HTML** atau **Download HTML**.
5. Tekan **Preview** jika ingin melihat hasilnya.
6. Pilih Desktop, Tablet, atau Mobile untuk memeriksa ukuran preview.

**Clear Result** membersihkan hasil. Riwayat dapat membantu mengulang URL yang pernah diperiksa.

Contoh: masukkan alamat halaman contoh milikmu sendiri, ekstrak, lalu lihat apakah elemen utama dan tautan asetnya muncul.

## Memahami preview dan laporan

Preview menjalankan HTML dalam ruang terbatas. Tampilan dapat berbeda jika halaman bergantung pada login, JavaScript khusus, aset yang tidak dapat diambil, atau aturan situs sumber.

Laporan statis menunjukkan aset dan endpoint yang ditemukan dari HTML. **Run Live Audit** melakukan pemeriksaan jaringan terbatas pada temuan tersebut, misalnya status HTTP, pengalihan, jenis file, dan respons lintas domain.

Endpoint yang terdeteksi bukan bukti kamu dapat mengakses seluruh datanya. Gunakan Copy JSON atau Download JSON untuk menyimpan laporan yang tersedia.

## SiteGrabber: paket website

1. Gunakan URL target yang memang boleh kamu tangkap.
2. Pada bagian SiteGrabber, pilih **Capture Mode**:
   - **Maximum Fidelity · Full Website:** permintaan penangkapan lebih menyeluruh.
   - **Single Page · Faster:** fokus satu halaman.
3. Centang pernyataan izin target pada formulir.
4. Tekan **Capture via SiteGrabber X**.
5. Tunggu pekerjaan selesai dan baca metrik Pages, Assets, Failed, dan Size.
6. Gunakan **Download Clone ZIP**.
7. Simpan laporan melalui Copy Report JSON atau Reports ZIP bila diperlukan.

Jumlah Failed perlu diperiksa. ZIP yang berhasil dibuat tidak berarti semua halaman, aset, atau fungsi situs berhasil ditangkap.

## Jika belum berhasil

- URL harus berupa halaman HTTP/HTTPS yang dapat diakses.
- Jika hanya perlu HTML, jangan memulai capture website penuh.
- Jika SiteGrabber belum tersedia, statusnya perlu dipulihkan oleh layanan terkait; Extract HTML adalah alur berbeda.
- Halaman login, aplikasi yang membutuhkan data privat, dan fungsi backend tidak otomatis menjadi website offline lengkap.
- Jika preview berbeda, periksa aset dan laporan kegagalan sebelum menganggap sumber sudah sama persis.

Untuk pemeriksaan SEO, kecepatan, dan keamanan halaman tanpa mengambil paket website, gunakan [Web Intelligence](webintel.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/get-code.js) · [Daftar semua tool](README.md)
