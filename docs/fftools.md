# FF Tools Nexora

Kumpulan utilitas Free Fire untuk mencari pemain, melihat statistik, memeriksa laporan ban, menghitung target winrate, dan membaca informasi akun yang tersedia.

## Pilih menu

| Menu | Yang dibutuhkan | Hasil |
| --- | --- | --- |
| **Search** | Nama pemain dan region. | Pemain yang ditemukan. |
| **Stats** | UID, region, mode BR/CS, dan jenis pertandingan. | Statistik yang disediakan layanan. |
| **Ban Check** | UID dan region jika diminta. | Laporan status ban yang tersedia. |
| **Winrate** | Total pertandingan, jumlah kemenangan, dan target persentase. | Kemenangan tambahan yang diperlukan. |
| **Stalk FF** | UID dan region. | Ringkasan akun atau account intelligence yang tersedia. |

**UID** adalah ID angka pemain. **Region** adalah wilayah/server akun; pilih sesuai akun, bukan lokasi kamu sedang membuka Nexora.

## Mencari dan melihat statistik

1. Untuk pencarian, buka Search, isi nama minimal tiga karakter, pilih region, lalu **CARI PEMAIN**.
2. Untuk statistik, buka Stats dan isi UID yang tepat.
3. Pilih **Battle Royale** atau **Clash Squad**.
4. Pilih lingkup **Career**, **Ranked**, atau **Normal** sesuai kebutuhan.
5. Tekan **ANALISIS STATISTIK** dan baca bagian yang benar-benar terisi.

Statistik mode berbeda tidak boleh langsung dianggap sama. Data kosong dapat berarti penyedia tidak memberi informasi tersebut, bukan berarti nilainya pasti nol.

## Menghitung winrate

1. Buka Winrate.
2. Isi TOTAL pertandingan.
3. Isi **jumlah kemenangan**, bukan persentase WR, pada kolom kemenangan.
4. Isi target WR.
5. Tekan **HITUNG WINRATE**.

Contoh: 100 pertandingan dan 50 kemenangan berarti WR 50%. Untuk mencapai 60% tanpa kalah lagi, diperlukan 25 kemenangan beruntun: 75 kemenangan dari 125 pertandingan = 60%.

Perhitungan ini tidak memprediksi hasil pertandingan berikutnya dan tidak mengubah akun.

## Ban Check dan kendala

Masukkan UID lalu tekan CEK STATUS BAN. Baca status dan sumber hasilnya. Jika pemeriksaan gagal, status akun **belum diketahui**; jangan menganggap gagal mengambil data berarti akun bebas ban.

Stalk FF menampilkan data yang berhasil didapat layanan, bukan akses ke password, inventori privat, atau semua aktivitas pemain. Jika akun tidak ditemukan, periksa UID dan region sebelum mencoba kembali.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/apps/ff-tools/index.html) · [Daftar semua tool](README.md)
