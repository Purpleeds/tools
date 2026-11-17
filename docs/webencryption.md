# Web Enkripsi V2

Melindungi HTML dengan kata sandi, atau membuka kembali file HTML Nexora yang terenkripsi. Proses berjalan di perangkat; sumber yang didekripsi ditampilkan sebagai teks di Nexora.

## Mengenkripsi HTML

1. Pilih **Operasi: Enkripsi HTML**.
2. Tempel HTML asli pada editor atau pilih file.
3. Isi **Judul / nama file**.
4. Buat **Passphrase** atau kata sandi panjang minimal 12 karakter.
5. Tekan **Enkripsi HTML**.
6. Tunggu hasil, lalu gunakan **Download HTML**.
7. Buka file hasil dan uji kata sandinya sebelum dibagikan.

Simpan sumber asli dan kata sandi di tempat yang dapat kamu kelola. Mengetahui nama file saja tidak cukup untuk membuka hasil tanpa kata sandi.

## Mendekripsi file Nexora

1. Pilih **Dekripsi file Nexora**.
2. Unggah atau tempel file HTML/payload Nexora yang terenkripsi.
3. Masukkan kata sandi asli.
4. Tekan tombol dekripsi.
5. Jika valid, sumber akan ditampilkan sebagai teks dan dapat disalin atau diunduh.

Mode ini tidak membuka semua jenis HTML terenkripsi dari aplikasi lain. Dukungan format mengikuti format Nexora yang dikenali, termasuk format lama yang didukung engine.

## Batas masukan dan hasil

- Pemilih file menerima HTML, HTM, TXT, atau JSON yang berisi sumber teks.
- Batas enkripsi 5 MB; batas dekripsi 8 MB.
- Hasil enkripsi adalah HTML mandiri dengan halaman pembuka berpassword.
- **Copy output** menyalin teks hasil.
- **Reset** membersihkan atau membatalkan pekerjaan yang sedang ditangani halaman.

Nama kata sandi pada formulir adalah Passphrase: gunakan rangkaian kata yang panjang dan unik, bukan teks contoh yang sama untuk semua file. Setelah proses sukses, kata sandi dibersihkan dari formulir.

## Contoh dan kendala

Jika ingin membagikan halaman HTML kepada anggota tim, enkripsi file, uji hasilnya, lalu bagikan file dan kata sandi melalui cara yang sesuai kebutuhanmu.

Jika browser menyatakan Web Crypto tidak tersedia, gunakan browser modern dan akses Nexora melalui HTTPS. Jika dekripsi gagal, periksa file serta kata sandi asli; mengganti judul atau ekstensi tidak memperbaiki kata sandi yang salah.

Enkripsi melindungi isi saat tersimpan. Orang yang diberi kata sandi tetap dapat membaca sumber setelah membukanya; fitur ini bukan jaminan sumber tidak bisa disalin oleh penerimanya.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/web-encryption.js) · [Daftar semua tool](README.md)
