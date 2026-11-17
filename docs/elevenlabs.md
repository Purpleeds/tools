# Nexora ElevenLabs Studio

Studio audio dengan **lima menu**, termasuk pilihan suara cloud dan suara yang diproses di browser. Tentukan dahulu apakah kamu ingin membuat suara, mengubah suara, menyalin ucapan, membuat efek, atau menyiapkan data gerak mulut.

## Pilih menu yang tepat

| Menu | Masukan | Hasil |
| --- | --- | --- |
| **Text to Speech** | Tulisan. | Suara pembacaan. |
| **Lip Sync** | Tulisan bahasa Inggris. | Audio WAV dan data waktu kata, fonem, serta bentuk mulut. |
| **Voice Changer** | Rekaman audio dan pilihan suara tujuan. | Audio dengan karakter suara yang diubah. |
| **Speech to Text** | Audio atau video. | Teks transkrip; SRT bila data waktu tersedia. |
| **Sound FX** | Deskripsi bunyi. | Efek suara. |

## Text to Speech: narasi dari tulisan

1. Buka **Text to Speech**.
2. Pada **TTS Engine**, pilih **ElevenLabs** atau **Kokoro**.
3. Tulis satu atau dua kalimat untuk percobaan awal.
4. Pilih suara. Untuk ElevenLabs, pilih juga model yang tersedia.
5. Atur kecepatan bila perlu, lalu tekan tombol pembuatan suara yang tersedia.
6. Dengarkan hasil dan unduh sebelum berpindah menu.

Contoh:

> Selamat datang di Nexora. Hari ini kita akan membuat animasi pertama.

### Bedanya ElevenLabs dan Kokoro

**ElevenLabs — CLOUD** memakai layanan online yang disiapkan pengelola Nexora. Daftar suara dan model mengikuti layanan tersebut. Jika tertulis **ElevenLabs Cloud belum tersedia**, tombol Retry hanya mengecek layanan lagi; itu tidak otomatis memperbaiki konfigurasi server.

**Kokoro — LOCAL • PRIVATE** memproses teks di browser. Pilih suara yang tersedia dan atur **Speaking speed**. Mesin, model, dan file suara perlu diunduh saat pemakaian awal. Teks lokal dibatasi 1.000 karakter. Pilih kalimat singkat dahulu, terutama pada HP.

Label lokal tidak berarti semua file model sudah tersedia tanpa internet. Kemampuan bahasa mengikuti suara/model yang dipilih; gunakan contoh bahasa yang sesuai suara untuk percobaan pertama.

### Pengaturan suara cloud

| Pengaturan | Artinya |
| --- | --- |
| **Voice** | Karakter suara yang ingin dipakai. |
| **Model** | Mesin suara yang mendukung pekerjaan tersebut. |
| **Stability** | Arahan kestabilan pembawaan suara. |
| **Similarity** | Arahan kemiripan dengan suara yang dipilih. |
| **Style** | Arahan kuat-lemahnya karakter atau ekspresi gaya. |
| **Speed** | Kecepatan pembacaan. |

Mulai dari nilai bawaan, lalu ubah satu pilihan dan bandingkan hasilnya. Batas panjang teks cloud mengikuti model yang dipilih dan penghitung yang tampil.

## Lip Sync: audio beserta waktu gerak mulut

1. Buka **Lip Sync**.
2. Masukkan dialog **bahasa Inggris**, sesuai dukungan HeadTTS pada tool ini.
3. Pilih suara dan Speaking speed.
4. Tekan **Generate Lip Sync**; tunggu pemuatan model pertama.
5. Dengarkan audio hasil.
6. Simpan **Download WAV** dan **Download Lip Sync JSON**.

Contoh:

> Hello, welcome to Nexora. Let's make something creative today.

JSON memuat data waktu untuk kata, bunyi, dan bentuk mulut. **Hasil menu ini bukan video karakter yang sudah berbicara.** Audio dan datanya perlu digunakan pada aplikasi atau proses animasi yang dapat membaca data tersebut.

HeadTTS berjalan lokal di browser, mengutamakan WebGPU dan memakai pilihan cadangan WASM bila memungkinkan. Jika model gagal dimuat atau memori tidak cukup, pendekkan teks dan tutup tab berat. Tool menolak keluaran waktu yang tidak valid; jangan menganggap JSON selalu tersedia hanya karena audio ada.

## Voice Changer: ubah karakter suara

1. Pilih **Voice Changer**.
2. Unggah audio, misalnya MP3, WAV, M4A, atau WebM sesuai pemilih file.
3. Putar **Original preview** untuk memastikan rekamannya benar.
4. Pilih Voice dan model yang mendukung konversi suara.
5. Tekan **Convert Voice**.
6. Bandingkan pembawaan aslinya dengan hasil, lalu unduh MP3.

Fitur ini memakai audio sebagai masukan. Ia berbeda dari Text to Speech yang membaca tulisan. Batas unggah mengikuti informasi pada formulir saat dipakai.

## Speech to Text: transkrip atau subtitle

1. Pilih **Speech to Text**.
2. Unggah audio atau video yang didukung.
3. Pilih **Language**: Auto Detect, Bahasa Indonesia, atau English.
4. Aktifkan **Detect speakers** jika ingin mencoba membedakan pembicara.
5. Tekan **Transcribe**.
6. Baca dan koreksi hasil berdasarkan rekaman.
7. Gunakan Copy atau TXT. Tombol **SRT** hanya muncul jika layanan memberi data waktu.

Deteksi pembicara memberi label jika berhasil ditemukan; tidak menjamin nama asli pembicara diketahui. SRT adalah berkas subtitle dengan waktu, bukan video yang sudah ditempeli tulisan.

## Sound FX: efek suara dari deskripsi

1. Pilih **Sound FX**.
2. Isi **Describe Sound** dengan bunyi yang spesifik.
3. Pilih Duration atau Auto.
4. Aktifkan **Loop sound** bila menginginkan bunyi yang dapat berulang.
5. Tekan **Generate Sound**, dengarkan, lalu unduh.

Contoh:

> Gentle rain hitting a wooden roof at night, with distant thunder and no music.

Kolom deskripsi dibatasi 1.000 karakter. Pilihan durasi mencakup 3, 5, 10, 15, atau 30 detik; hasil tetap mengikuti layanan.

## Menyimpan hasil dan mengatasi kendala

- **Download MP3/WAV** menyimpan hasil yang sudah ada.
- **Generate Again** memproses ulang dan dapat menggunakan layanan lagi.
- Berpindah menu dapat membersihkan hasil sementara; unduh dahulu.
- Jika menu cloud belum tersedia, periksa pesan statusnya. Kokoro dan Lip Sync lokal merupakan pilihan berbeda, bukan pemulihan otomatis layanan cloud.
- Untuk lokal, tunggu unduhan model awal selesai. Gunakan browser modern dan teks pendek jika perangkat terasa berat.

Untuk membuat lagu utuh dari deskripsi, gunakan [AI Song Generator](aisong.md).

[Sumber fitur yang diaudit](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/elevenlabs-studio.js) · [Daftar semua tool](README.md)
