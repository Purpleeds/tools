# QR Generator

Creates QR codes for several kinds of information. Choose the right type so scanner apps understand the content, rather than just showing raw text.

## Getting started with a website link

1. Choose **Tautan** (Link) as the QR type.
2. Enter the destination website address.
3. Leave the QR color dark and the background light.
4. Choose an export size.
5. Press **Buat QR** (Create QR).
6. Scan it with another phone's camera to make sure the destination is correct.
7. Save it through **Unduh PNG** (Download PNG) or **Unduh SVG** (Download SVG).

## Choose a QR type

| Type | What to fill in | When scanned |
| --- | --- | --- |
| **Tautan** (Link) | A website URL. | Opens or offers the link. |
| **Teks** (Text) | A message or information. | Shows the text. |
| **Wi-Fi** | Network name, security type, and password if any. | Helps connect to the network on supported devices. |
| **WhatsApp** | A number with country code and an optional opening message. | Opens a WhatsApp chat. |
| **Email** | Address, subject, and optional body. | Prepares an email; doesn't send it automatically. |
| **Kontak** (Contact) | The name and contact details requested. | Prepares contact information to be saved. |

For Indonesian numbers on WhatsApp, use the country code prefix **62** as instructed, rather than guessing a number without a country code.

A Wi-Fi QR contains the network information, including the password needed. Give that QR only to people who are allowed to access the network.

## Appearance and error correction

**Ukuran ekspor** (Export size) is available at 512, 1024, or 2048 pixels for raster results. **SVG** suits cases where the image needs to be scaled up in a design that supports vectors.

**Koreksi kesalahan** (Error correction) L/M/Q/H sets how well the QR withstands partial damage. M is a balanced starting point; higher levels use more space, so the code can become denser.

Use good contrast. Colors that are too similar between the QR and the background can make scanning difficult. A nice-looking design doesn't prove the QR is readable; always test-scan the downloaded result.

## Results and issues

**Salin gambar** (Copy image) copies the image if the browser's clipboard supports it. **Salin isi** (Copy content) only copies the data you entered. Generation happens locally; the content isn't sent to a server to create the QR.

This QR is not a dynamic redirect service. To change the destination, create a new QR; old files don't change automatically.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/vendor/qr-generator-engine.js) · [List of all tools](README.md)
