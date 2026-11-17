# Choose a Tool and Follow the Right Workflow

Use this page when you know the result you want but not which tool to open. The links go to each tool's full step-by-step guide.

## 1. You want to make an AI poster from an idea

1. Open [Prompt Studio](promptgenerate.md) if you need help writing instructions.
2. Choose Image, write your idea, use the Universal target profile, then press Generate Prompt.
3. Copy the Production Prompt.
4. Open [AI Image](aiimage.md), choose Generate, and connect Puter.
5. Paste the prompt, choose an aspect ratio and an available model, then press **Buat Gambar** (Create Image).
6. Check the text and details in the result, then download it.

If you can already write your own instructions, start straight from AI Image. Prompt Studio is not a required step.

## 2. You want to change a photo or use several references

In [AI Image](aiimage.md):

- **Edit:** one image to be changed. Describe the changes and also the parts that should stay the same.
- **Reference:** one reference for creating a new scene that follows a character or style.
- **Multi:** two to four references, within the limit shown. State the role of the first image, the second, and so on.

Example Multi instruction: "the character from the first image, the outfit from the second image, the atmosphere from the third image". Don't use Generate when you expect reference images to be used; Generate takes no image input.

## 3. You want a filler image for a design, not a complex illustration

Open [Placeholder Studio](placeholderstudio.md):

- **Classic:** simple colors, text, and size; the preview updates automatically.
- **Prompt:** an image from a description, through a public service.

Check the download section of its guide. In the audited version, Classic Download saves the SVG preview, while the Format option is also used for the service URL. Don't rename an SVG extension to PNG without converting it.

## 4. You want an image logo to be usable in Alight Motion

1. If the source is still PNG/JPG/WebP, open [Vecto](vecto.md) or [AUTO TRACE](imagevectorizer.md) to make an SVG.
2. Check the SVG and download it.
3. Open [SVG → Alight XML](svgalight.md) to create the XML.
4. Import the XML into Alight Motion and check its layers.
5. Add motion or export the video from that app.

If the SVG already contains SMIL/CSS animation, use [SVG Animasi → Alight XML](svganimation.md). If you only need a logo template, [Logo Animate](logoanimate.md) uses sample media that you replace after importing.

## 5. You want to separate an object from its background

- [Remove Background](removebg.md): background removal, with a brush editor for Erase/Restore.
- [Smart Cutout](smartcutout.md): select the object by tapping with Select + and Remove −, then Extract.
- [NEXORA Auto Cut](nexoraautocut.md): prepares several PNG layers and XML as animation material.

A single transparent PNG, several cut-out layers, and an SVG are different results. Choose the tool that matches the final result you need.

## 6. You want to work with documents

| Need | Tool and result |
| --- | --- |
| Turn text into a new PDF | [Auto PDF](autopdf.md): enter text/chapters, then create a preview and PDF. |
| Merge or arrange PDFs | [PDF Lab](pdflab.md): choose an operation and files, then Export PDF. |
| Extract text from a photo/scan | [OCR Intelligence](ocrintel.md): OCR text output; a searchable PDF when available. |
| Understand and ask questions about a document | [Document AI](documentai.md): AI summaries, analysis, or answers. |

PDF Lab's Add Text adds text; it does not automatically change the original paragraphs. Document AI is not a substitute for checking figures against the source document.

## 7. You want to make video or audio

- [AI Video Generator](aivideo.md): video from text or an image, through Puter.
- [HTML / WebGL to MP4](htmlvideo.md): video from HTML you prepare.
- [Text Match Cut](textmatchcut.md): newspaper-style video; BPM and word areas on custom images are set manually.
- [Motion Control](motioncontrol.md): choose an external service, then do the work on the provider's site.
- [AI Song Generator](aisong.md): a song from a description.
- [ElevenLabs Studio](elevenlabs.md): narration, voice changing, transcripts, sound effects, or audio with lip-sync data.

In ElevenLabs Studio, Lip Sync produces a WAV and a JSON of mouth-movement timings, not a finished character video. In AI video, Download fetches the existing result; Generate Again makes a new request.

## 8. You want help with security or information

[Web Intelligence](webintel.md) checks websites; [IP & ASN Intelligence](ipintel.md) looks up network information; [Virus Scan](virusscan.md) checks local traits of the input. The three are not the same tool, and none of them proves absolute safety.

[BMKG](bmkg.md) uses an ADM4 code for regional weather. [Space Explorer](spaceexplorer.md) covers outer space, not local rain forecasts. [CariFakta](carifakta.md) gives AI analysis that needs to be compared with the original sources.

## Quick list by need

The sections below still cover every tool, so other names are easy to find.

## Images, logos, and vectors

- Remove the background of a whole image: [Remove Background](removebg.md).
- Select one object to separate: [Nexora Smart Cutout](smartcutout.md).
- Enlarge an image: [Image HD Enhancer V4](enhancer.md) or [Perbesar Gambar 4x](bigjpg-nexora.md) (Enlarge Image 4x).
- Convert an image to SVG: [Vecto](vecto.md) or [AUTO TRACE](imagevectorizer.md). They are separate tools with different engines.
- Make an avatar or a design filler image: [Avatar Studio](avatarstudio.md) or [Placeholder Studio](placeholderstudio.md).
- Share an image as a link: [Foto To Link](fotolink.md).

## Alight Motion

- Move a static SVG into Alight Motion: [SVG → Alight XML](svgalight.md).
- Move an animated SVG: [SVG Animasi → Alight XML](svganimation.md).
- Split an image into layers for animation: [NEXORA Auto Cut](nexoraautocut.md).
- Make text and logos: [2D Text Animate](text2d.md), [3D Text Animate](text3d.md), [Text FX Animation](textfxanimation.md), [Text to Vector](textvector.md), [Trimpath Generator](trimpath.md), or [Logo Animate](logoanimate.md).
- Find presets shared on TikTok: [Cari Preset AM](presetfinder.md) (Find AM Presets).
- Send and verify an authentication link: [AM Send & Verif](amsendverif.md).
- Premium application flow through a provider: [Alight Motion Premium 1 Tahun](alightpremium.md) (1 Year). Authentication verification and subscription status are two different things.

## AI, voice, and video

- Create images: [Nexora AI Image](aiimage.md). To try other services and models, open [AI Image Eksperimental](aiimageexperimental.md).
- Turn anime illustrations into a realistic style: [Anime to Real](animetoreal.md).
- Create AI video: [AI Video Generator](aivideo.md).
- Make songs or process voice: [AI Song Generator](aisong.md) or [ElevenLabs Studio](elevenlabs.md).
- Write AI instructions or use several AIs: [Prompt Studio](promptgenerate.md) or [Multi-AI](multiai.md).
- Make a newspaper-clipping video: [Text Match Cut](textmatchcut.md).
- Record an HTML display as video: [HTML / WebGL to MP4](htmlvideo.md).
- Find character motion-transfer services: [Motion Control](motioncontrol.md).

## Documents and writing

- Create a PDF from text: [Nexora Auto PDF](autopdf.md).
- Merge or arrange PDFs: [PDF Lab Local](pdflab.md).
- Extract text from photos or PDFs: [OCR Intelligence](ocrintel.md).
- Summarize or ask about a document: [Document AI](documentai.md).

## Content, reading, and games

- Download TikTok or Instagram videos: [Social Downloader](socialdownloader.md).
- Make quotes or message images: [Quote Generator](quotegenerator.md), [Windows Quotes](winquotes.md), [Nokia Message](nokiamsg.md), or [Quote TikTok](ttquote.md).
- Make entertainment images: [Sertifikat Custom](sertifikat.md) (Custom Certificate), [E-KTP Generator](ektp.md), [Fake Lobby](fakelobby.md), or [Fake OVO](fakeovo.md). Each page explains its simulation format.
- Read comics or classic literature: [Baca Komik](comicreader.md) (Read Comics) or [World Classics Reader](worldclassics.md).
- Browse anime illustrations or GIFs: [Danbooru Search](danbooru.md) or [Anime Discover](animegallery.md).
- View game information and calculate win rates: [FF Tools](fftools.md) or [ML Tools](mltools.md).

## Websites and everyday utilities

- Check a website, network, or file: [Web Intelligence](webintel.md), [IP & ASN Intelligence](ipintel.md), or [Virus Scan](virusscan.md).
- Fetch a website's HTML or protect your own HTML: [Get Code HTML](getcode.md) or [Web Enkripsi V2](webencryption.md) (Web Encryption V2).
- Find the destination of a Safelinku link: [Safelinku Bypass](safelinku.md).
- Receive temporary email: [GenMail](genmail.md).
- Make passwords, QR codes, or Morse code: [Password Generator](pwgen.md), [QR Generator](qrgen.md), or [Morse Code](morse.md).
- Read weather, space, or market data: [BMKG Indonesia](bmkg.md), [Space Explorer](spaceexplorer.md), or [Crypto Market Scanner](cryptomarket.md).
- Help assess claims or news: [CariFakta](carifakta.md).

[See the full list of 65 tools](README.md)
