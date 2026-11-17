# Nexora ElevenLabs Studio

An audio studio with **five menus**, including cloud voices and voices processed in the browser. First decide whether you want to create speech, change a voice, transcribe speech, make an effect, or prepare mouth-movement data.

## Choose the right menu

| Menu | Input | Output |
| --- | --- | --- |
| **Text to Speech** | Text. | Spoken reading. |
| **Lip Sync** | English text. | WAV audio and timing data for words, phonemes, and mouth shapes. |
| **Voice Changer** | An audio recording and a target voice choice. | Audio with a changed voice character. |
| **Speech to Text** | Audio or video. | Transcript text; SRT when timing data is available. |
| **Sound FX** | A description of a sound. | A sound effect. |

## Text to Speech: narration from text

1. Open **Text to Speech**.
2. In **TTS Engine**, choose **ElevenLabs** or **Kokoro**.
3. Write one or two sentences for a first try.
4. Choose a voice. For ElevenLabs, also choose an available model.
5. Adjust the speed if needed, then press the available voice-generation button.
6. Listen to the result and download it before switching menus.

Example:

> Selamat datang di Nexora. Hari ini kita akan membuat animasi pertama. ("Welcome to Nexora. Today we'll make our first animation.")

### How ElevenLabs and Kokoro differ

**ElevenLabs — CLOUD** uses an online service set up by Nexora's administrators. The voice and model lists follow that service. If it says **ElevenLabs Cloud belum tersedia** (ElevenLabs Cloud not yet available), the Retry button only checks the service again; it doesn't automatically fix the server configuration.

**Kokoro — LOCAL • PRIVATE** processes text in the browser. Choose an available voice and set the **Speaking speed**. The engine, model, and voice files need to be downloaded on first use. Local text is limited to 1,000 characters. Choose short sentences first, especially on a phone.

The local label doesn't mean all model files are available without internet. Language capability follows the chosen voice/model; use an example in a language that suits the voice for your first try.

### Cloud voice settings

| Setting | What it means |
| --- | --- |
| **Voice** | The voice character you want to use. |
| **Model** | The voice engine that supports the job. |
| **Stability** | Guidance on how steady the voice delivery is. |
| **Similarity** | Guidance on how closely it resembles the chosen voice. |
| **Style** | Guidance on how strong the character or stylistic expression is. |
| **Speed** | Reading speed. |

Start from the default values, then change one option and compare the results. The cloud text length limit follows the chosen model and the counter shown.

## Lip Sync: audio with mouth-movement timing

1. Open **Lip Sync**.
2. Enter **English** dialogue, as supported by HeadTTS in this tool.
3. Choose a voice and Speaking speed.
4. Press **Generate Lip Sync**; wait for the first model load.
5. Listen to the resulting audio.
6. Save with **Download WAV** and **Download Lip Sync JSON**.

Example:

> Hello, welcome to Nexora. Let's make something creative today.

The JSON contains timing data for words, sounds, and mouth shapes. **The output of this menu is not a video of a character already talking.** The audio and data need to be used in an app or animation process that can read that data.

HeadTTS runs locally in the browser, preferring WebGPU and using a WASM fallback when possible. If the model fails to load or there isn't enough memory, shorten the text and close heavy tabs. The tool rejects invalid timing output; don't assume a JSON is always available just because there's audio.

## Voice Changer: change a voice's character

1. Choose **Voice Changer**.
2. Upload audio, for example MP3, WAV, M4A, or WebM, as allowed by the file picker.
3. Play **Original preview** to make sure the recording is right.
4. Choose a Voice and a model that supports voice conversion.
5. Press **Convert Voice**.
6. Compare the original delivery with the result, then download the MP3.

This feature takes audio as input. It differs from Text to Speech, which reads text. The upload limit follows the information on the form at the time of use.

## Speech to Text: transcripts or subtitles

1. Choose **Speech to Text**.
2. Upload a supported audio or video file.
3. Choose **Language**: Auto Detect, Bahasa Indonesia, or English.
4. Turn on **Detect speakers** if you want to try telling speakers apart.
5. Press **Transcribe**.
6. Read and correct the result against the recording.
7. Use Copy or TXT. The **SRT** button only appears if the service provides timing data.

Speaker detection gives labels if it succeeds; it doesn't guarantee the speakers' real names are known. SRT is a timed subtitle file, not a video with the text burned in.

## Sound FX: sound effects from a description

1. Choose **Sound FX**.
2. Fill in **Describe Sound** with a specific sound.
3. Choose a Duration or Auto.
4. Turn on **Loop sound** if you want a sound that can repeat.
5. Press **Generate Sound**, listen, then download.

Example:

> Gentle rain hitting a wooden roof at night, with distant thunder and no music.

The description field is limited to 1,000 characters. Duration options include 3, 5, 10, 15, or 30 seconds; the result still depends on the service.

## Saving results and solving issues

- **Download MP3/WAV** saves the existing result.
- **Generate Again** processes again and may use the service again.
- Switching menus can clear temporary results; download first.
- If a cloud menu isn't available yet, check its status message. Kokoro and local Lip Sync are different options, not an automatic recovery of the cloud service.
- For local processing, wait for the initial model download to finish. Use a modern browser and short text if your device feels slow.

To make a full song from a description, use [AI Song Generator](aisong.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/elevenlabs-studio.js) · [List of all tools](README.md)
