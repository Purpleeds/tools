# SVG Animasi → Alight XML

Mengubah animasi di dalam SVG menjadi bentuk dan keyframe XML untuk Alight Motion. Tool ini membaca animasi **SMIL atau CSS** yang didukung, bukan mengubah MP4 menjadi animasi vektor.

**Keyframe** adalah penanda nilai pada waktu tertentu, misalnya posisi objek pada awal dan akhir gerakan.

## Percobaan pertama

1. Buka **SVG Animasi → Alight XML**.
2. Tekan **Coba contoh animasi vektor** untuk mengenali alur dengan contoh bawaan.
3. Tekan **Preview kode animasi**.
4. Gunakan **Putar**, **Awal**, dan penggeser timeline untuk memeriksa gerakan.
5. Pilih **Maximum Fidelity** sebagai titik awal.
6. Atur ukuran, nama proyek, FPS, serta durasi sesuai kebutuhan.
7. Tekan **Convert ke XML**.
8. Baca peringatan, unduh XML, lalu impor dan periksa di Alight Motion.

Setelah contoh dipahami, ganti dengan kode SVG animasimu sendiri.

## Menyiapkan sumber sendiri

Tempel seluruh kode SVG pada **Tempel kode SVG animasi**, termasuk elemen SVG pembukanya, bentuk yang dianimasikan, dan aturan animasinya. Jika memiliki file, gunakan pemilih SVG; batas sumber adalah 2 MB.

Pastikan sumber benar-benar berisi animasi SVG/CSS. Menempelkan alamat website, video, atau potongan JavaScript saja tidak menghasilkan animasi yang dapat dikonversi.

Jika ingin mencoba kode sederhana:

~~~xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 200">
  <circle cy="100" r="30" fill="#a855f7">
    <animate attributeName="cx" from="50" to="350"
             dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
~~~

Contoh ini meminta lingkaran bergerak mendatar. Dukungan ekspor tetap perlu dilihat dari laporan konversinya.

## Pengaturan yang perlu dipahami

| Bagian | Artinya |
| --- | --- |
| **Timeline sumber** | Memeriksa animasi sebelum konversi. |
| **FPS dan Durasi** | Pengaturan waktu proyek hasil. |
| **Daftar layer** | Bentuk yang akan disertakan; pilihan Semua, Tidak Ada, atau Balik membantu seleksi. |
| **Flat / Nested Groups** | Cara struktur bentuk disusun dalam XML. |
| **Maximum Fidelity** | Menjaga sumber semaksimal mungkin. |
| **Smart Color Groups** | Mengelompokkan warna solid sambil memeriksa susunan visual. |
| **Small Patch Cleanup** | Membersihkan serpihan bidang kecil dengan pengaturan perlindungan detail tipis. |
| **Izinkan XML partial dengan peringatan** | Mengizinkan hasil sebagian ketika ada animasi yang tidak sepenuhnya didukung. |

**Partial** berarti sebagian unsur dapat hilang, dibatasi, atau didekati dengan sampel. Aktifkan hanya jika kamu sudah membaca peringatannya dan menerima keterbatasan hasil. Pilihan ini bukan jaminan semua animasi akan sama persis.

## Menyimpan hasil

Nama proyek di Alight Motion dan nama file unduhan dapat diatur terpisah. Setelah sukses, pilih **Download XML** atau **Salin XML**. Periksa gerakan di aplikasi tujuan, terutama rotasi, urutan tumpukan, dan perubahan bentuk.

Preview yang bergerak membuktikan sumber dapat dipratinjau di browser; belum otomatis membuktikan semua gerakan didukung Alight Motion. Gunakan laporan hasil konversi sebagai acuan.

Untuk SVG logo tanpa animasi, [SVG → Alight XML](svgalight.md) lebih sesuai.

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/svg-animation-alight.js) · [Daftar semua tool](README.md)
