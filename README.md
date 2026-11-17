# Nexora Tools

User guides for the 65 Nexora tools, in English and Indonesian.

**English**

- [List of all tools](docs/en/README.md)
- [Guide to choosing a tool](docs/en/PANDUAN_MEMILIH_TOOL.md)

**Bahasa Indonesia**

- [Daftar semua tool](docs/README.md)
- [Panduan memilih tool](docs/PANDUAN_MEMILIH_TOOL.md)

The Indonesian guides in `docs/` are copied as-is from the Google Drive folder "Panduan lengkap (all tools nexora)". The English translations in `docs/en/` use the same file names.

## Toolbench website

`site/index.html` is a one-page website with eight of these tools, rebuilt from scratch:

| Tool | Needs |
| --- | --- |
| Password generator | Browser only |
| QR code maker (link, text, Wi-Fi, WhatsApp, email, contact) | Browser only |
| Morse code (text ⇄ Morse, with sound) | Browser only |
| Quote image (JPG / PNG) | Browser only |
| Placeholder image (PNG, JPG, WebP, SVG) | Browser only |
| Text to PDF (A4 / A5, sections, page numbers) | Browser only |
| Page lock (password-protected HTML, AES-256-GCM) | Browser only |
| Prompt writer (image and video prompts) | An AI model: works when the page is opened on claude.ai, using the viewer's Claude account |

To use it, open `site/index.html` in a browser, or host the `site` folder on any static host such as GitHub Pages. It loads two libraries from jsDelivr (`qrcode-generator` 1.4.4 and `jspdf` 2.5.1) and its fonts from Google Fonts; nothing else leaves the browser.
