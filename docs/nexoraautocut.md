# NEXORA Auto Cut

Memisahkan bagian gambar menjadi beberapa PNG transparan dan menyiapkan XML agar lapisan tersebut dapat dipakai di Alight Motion. Hasilnya cocok sebagai bahan animasi potongan, bukan otomatis membuat gerakan karakter lengkap.

## Siapkan bahan

- Satu gambar karakter atau objek dengan bagian yang cukup jelas.
- XML Alight Motion referensi jika ingin membawa pengaturan waktu dan transformasi dari proyek sumber. XML ini opsional.
- Alight Motion untuk mengimpor dan mengolah hasil.

## Cara pakai

1. Pilih gambar pada bagian **Input**.
2. Jika memiliki XML referensi, masukkan melalui **XML Alight referensi**.
3. Perhatikan pilihan **AI otomatis setelah upload**. Jika aktif, penghapusan latar dapat dimulai setelah gambar masuk.
4. Jika belum diproses, tekan **Auto Cut**.
5. Periksa preview dan daftar **Layer hasil**.
6. Jika mask kurang tepat, gunakan **Edit manual / rapikan hasil**.
7. Setelah hasil benar, tekan **Download XML + PNG**.

XML referensi dipakai agar timing dan transformasi sumber dapat dipertahankan oleh alurnya. Ini tidak berarti semua proyek XML apa pun pasti cocok; baca pesan jika sumber tidak dapat diproses.

## Apa yang didapat?

Satu **ZIP** berisi:

- XML Alight Motion.
- Beberapa file PNG transparan, masing-masing untuk lapisan potongan.
- Petunjuk singkat dalam paket.

XML menyusun lapisan hasil ke dalam satu grup. Ekstrak ZIP, simpan semua PNG dan XML, lalu impor XML ke Alight Motion. Jika aplikasi meminta media, gunakan PNG hasil dari paket yang sama.

## Contoh penggunaan

Untuk karakter dengan beberapa bagian yang terpisah jelas, jalankan pemotongan, periksa hasil lapisan, lalu atur gerak masing-masing lapisan di Alight Motion. Jika dua bagian menyatu pada gambar asal, jangan berharap keduanya selalu dikenali sebagai potongan terpisah.

## Jika hasil belum sesuai

- Jika latar masih ikut, rapikan mask sebelum mengunduh.
- Jika bagian objek ikut hilang, pulihkan area melalui editor manual.
- Jika tidak ada lapisan yang bisa diekspor, periksa kembali gambar dan hasil penghapusan latar.
- Jika gambar belum selesai diproses, tunggu status akhir sebelum Download.
- Setelah mengubah masukan atau koreksi, periksa ulang hasil yang akan dipakai.

Untuk hanya memisahkan satu objek menjadi satu PNG, [Smart Cutout](smartcutout.md) mungkin lebih sederhana.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora-auto-cut.js) · [Daftar semua tool](README.md)
