# Text to Vector

Mengubah tulisan menjadi bentuk huruf vektor dan menyiapkan XML Alight Motion. Setelah menjadi bentuk, huruf tidak lagi sekadar kolom teks biasa yang mudah diganti isinya.

## Cara mulai

1. Isi **Teks** dengan kata pendek, misalnya “NEXORA”.
2. Pilih Font lokal, misalnya Poppins, dan Style yang tersedia untuk font tersebut.
3. Biarkan **Mode: Character**, **Vector Style: Fill + Stroke**, **Contour: AM Fix A**, dan **Path: Cubic Bézier** untuk percobaan awal.
4. Atur warna Fill dan Stroke.
5. Tekan Generate XML.
6. Periksa preview vektor yang dibuat setelah Generate.
7. Unduh XML dan impor ke Alight Motion.

## Pengaturan yang paling penting

| Pengaturan | Artinya |
| --- | --- |
| **Font / Style** | Bentuk huruf dan ketebalannya. Daftar Style menyesuaikan font. |
| **Font Size** | Ukuran geometri huruf yang dibuat. |
| **Letter Spacing** | Jarak antarhuruf. |
| **Padding** | Ruang tambahan di sekitar teks. |
| **Mode: Character / Word** | Mengatur pengelompokan per huruf atau per kata. |
| **Fill Only** | Hanya isi bentuk. |
| **Stroke Only** | Hanya garis tepi bentuk. |
| **Fill + Stroke** | Isi dan garis tepi sekaligus. |
| **Stroke Width** | Ketebalan garis tepi. |
| **Contour: AM Fix A/B/Original** | Pilihan penanganan kontur huruf untuk kebutuhan kompatibilitas; mulai dari bawaan. |
| **Path: Cubic Bézier / Flatten** | Kurva atau pendekatan segmen yang lebih terpecah. |
| **Duration / FPS** | Waktu dan frame rate proyek XML. |

## Contoh penggunaan

Untuk tulisan putih dengan garis ungu, pilih Fill + Stroke, Fill putih, Stroke ungu, lalu gunakan ketebalan garis awal yang tidak terlalu besar. Jika hanya ingin outline, pilih Stroke Only.

Huruf seperti “O”, “B”, atau “A” memiliki ruang kosong di dalam. Periksa ruang tersebut pada preview dan impor Alight Motion. Jika tampil berbeda, bandingkan pilihan Contour, bukan langsung mengubah semua parameter.

## Hasil dan kendala

Pemrosesan font dilakukan lokal melalui worker browser. Tunggu font dan pekerjaan selesai sebelum mengunduh. Jika Style font tidak tersedia, pilih salah satu ketebalan yang benar-benar muncul setelah font diganti.

Nama file dapat diubah terpisah dari nama proyek. Setelah teks atau font diganti, jalankan Generate XML lagi. Jika yang dibutuhkan adalah gambar SVG dari PNG/JPG, gunakan [Vecto](vecto.md); tool ini khusus mengubah tulisan/font menjadi bentuk Alight Motion.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [Daftar semua tool](README.md)
