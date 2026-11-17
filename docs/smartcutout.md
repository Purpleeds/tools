# Nexora Smart Cutout

Memilih objek tertentu pada foto dan mengekspornya sebagai PNG transparan. Kamu membantu AI dengan mengetuk bagian yang dipertahankan atau dibuang.

## Langkah pemakaian

1. Tekan **Upload Image** dan pilih JPG, PNG, atau WebP maksimal 20 MB.
2. Tunggu gambar dan model siap.
3. Biarkan **Select +** aktif, lalu ketuk bagian tengah objek yang ingin dipertahankan.
4. Periksa mask atau penanda area pada preview.
5. Tambahkan ketukan Select + jika bagian objek belum lengkap.
6. Jika latar ikut terpilih, pilih **Remove −**, lalu ketuk area yang ingin dibuang.
7. Pilih tepi **Soft** atau **Sharp**.
8. Tekan **Extract Object**.
9. Periksa Result, lalu **Download PNG**.

## Pengaturan dan istilah

**Mask** adalah peta bagian yang dipertahankan dan dibuang. Mask PNG bukan gambar objek final; gunakan Download PNG untuk objek berwarna dengan transparansi.

**Soft** membuat tepi lebih lembut. **Sharp** memakai tepi yang lebih tegas. Cocokkan dengan kebutuhan, misalnya rambut sering memerlukan pemeriksaan tepi lebih teliti.

**Crop to Object** memotong kanvas mendekati objek dengan tambahan ruang sekitar 3%. Matikan jika ingin mempertahankan area kanvas sumber untuk hasil.

**Undo** membatalkan langkah pilihan terakhir; **Reset** menghapus pilihan mask untuk memulai seleksi lagi. **Ganti** memilih gambar baru.

## Contoh

Pada foto meja yang berisi cangkir dan buku, pilih Select + lalu ketuk cangkir. Jika buku ikut masuk, pindah ke Remove − dan ketuk buku. Setelah preview sesuai, Extract Object dan simpan PNG.

Di HP, cubit untuk zoom dan geser saat diperbesar agar titik lebih tepat. Zoom hanya membantu pemilihan, bukan menambah detail gambar.

## Jika belum berhasil

Tombol Extract belum aktif jika mask belum siap. Tunggu model dan tambahkan titik pada objek. Jika hasil masih salah, ubah titik seleksi lalu ekstrak ulang. Model diunduh saat diperlukan, tetapi pemilihan dan pemrosesan gambar berjalan di browser.

Untuk menghapus latar dengan alur otomatis dan editor kuas, lihat [Remove Background](removebg.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/smart-cutout-core.js) · [Daftar semua tool](README.md)
