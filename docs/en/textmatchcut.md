# NEXORA Text Match Cut

Creates a newspaper-clipping video in which one word or phrase keeps its position while the pages change. The preview runs on your device, while the MP4 is rendered on Nexora's VPS.

## First try without your own images

1. Fill in **Kata / frasa** (Word / phrase), for example "NEXORA".
2. Choose **Mode: Auto Newspaper**.
3. Choose a **Gaya Auto** (Auto style) or leave it mixed.
4. Use **Jumlah klip: 12** (Number of clips).
5. Choose **Timing: Durasi per cut** (Duration per cut), then enter 500 ms.
6. Choose **Rasio: 9:16** (Ratio), 720p, and 30 FPS.
7. Press **Putar preview** (Play preview) to check how it looks.
8. When it looks right, press **Render MP4**, wait for processing to finish, then play and download the result.

With 12 clips × 500 ms, the base duration is about 6 seconds. This is an example setting, not a video that has already been made.

## Auto Newspaper and Custom Newspaper

**Auto Newspaper** builds newspaper-style pages from elements the tool creates.

**Custom Newspaper** uses your own images:

1. Switch to Custom Newspaper.
2. Upload the images you want to use. At most eight images; each image at most 5 MB and 12 megapixels.
3. Select each image.
4. In the selection area, mark where the word to be kept is. You can drag it by touch or set it through X, Y, Lebar (Width), and Tinggi (Height) as percentages.
5. Check all the images, then play the preview.

**The tool doesn't find the word's location with OCR.** Typing the word in the form doesn't automatically mark its location on the photo. If the area hasn't been selected correctly, a Custom render may be rejected.

## The settings with the most effect

| Setting | What it means |
| --- | --- |
| **Kata / frasa** (Word / phrase) | The focal text; 1–32 Latin characters. Capitalization is kept. |
| **Jumlah klip** (Number of clips) | How many page cuts, 2–24. |
| **Intensitas** (Intensity) | The motion style: Smooth, Classic, Fast, or Aggressive. |
| **Durasi per cut** (Duration per cut) | How long each cut lasts, in milliseconds. 1,000 ms = 1 second. |
| **BPM manual / 1 beat** | Each cut follows one beat of the BPM you enter. |
| **Rasio** (Ratio) | 9:16 portrait, 16:9 landscape, or 1:1 square. |
| **Highlight** | A box, an underline, or no word marker. |
| **Warna** (Color) | The highlight color. |
| **Zoom, pan & gerakan kamera** (Zoom, pan & camera movement) | Adds movement to the view. |
| **Seed layout / Acak halaman** (Seed layout / Shuffle pages) | Chooses a variation of the page arrangement. |

BPM example: 120 BPM means one beat is about 0.5 seconds. With 12 clips, the duration is about 6 seconds.

## Adding music

1. Upload an MP3, PCM WAV, or AAC M4A through the audio section.
2. Play the audio preview to make sure the right file is chosen.
3. Set the manual BPM or cut duration to match the music.
4. Render the MP4; the audio is merged into the result.

The audio limit in the form is 10 MB and 10 minutes. **There's no automatic beat detection.** Uploading a song doesn't automatically align all the cuts to its beat.

## Export and issues

30 FPS is the lighter starting option. The 60 FPS option is limited to 6 seconds. The suggested starting resolution is 720p; use the options actually available on the page.

**Preview siap** (Preview ready) doesn't always mean server rendering is active. If it says Render VPS belum aktif (Render VPS not yet active), you can still use the preview but can't create the MP4 yet. During the Queued status, wait your turn; during Rendering, don't start the same job repeatedly.

If rendering fails because of time or memory, reduce the duration, the number of clips, or the image load. For Custom, make sure each image's word area is valid. Server results are temporary, so download the video when it's done.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/text-match-cut/model.js) · [List of all tools](README.md)
