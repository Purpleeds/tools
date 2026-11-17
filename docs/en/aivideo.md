# Nexora AI Video Generator

Creates video from text or from a single starting image through a Puter account. If you're just trying it out, start with a simple scene, a short duration, and one camera movement.

## Setup

- Log in to Nexora if asked, then **Hubungkan Puter** (Connect Puter) through Puter's official window.
- The Puter login is separate from the Nexora login. Usage counts against your Puter account's allowance.
- For Image to Video, prepare one JPG, PNG, or WebP of at most 10 MB.

## Choose a mode

| Mode | When to use it | What to fill in |
| --- | --- | --- |
| **Text to Video** | Creating a scene from scratch. | A prompt. |
| **Image to Video** | Animating or extending a single image. | A starting image and a motion prompt. |

## First steps

1. Choose **Text to Video**.
2. Write a clear scene: subject, motion, place, lighting, and camera movement.
3. Choose a model available for that mode.
4. Choose a duration in **Durasi yang diminta** (Requested duration).
5. If an aspect ratio is shown, choose 9:16 for portrait or 16:9 for landscape.
6. Press **Generate Video** once.
7. Wait for processing to finish, then play the video before downloading.

Example prompt:

> A cat sits by the window while it rains. The cat slowly turns to look outside, warm light from a desk lamp, static camera, natural movement.

For Image to Video, choose the image first, then use a direction such as:

> Keep the character and outfit from the starting image. Make the hair move gently in the wind, the camera slowly pushes in, the background stays consistent.

## Models and settings

| Option in the source | Available durations | Notes |
| --- | --- | --- |
| **Wan 2.7 · Text** | 5, 8, 10, 15 seconds | For Text to Video; 9:16 or 16:9 options, 720p. |
| **Wan 2.7 · Image** | 5, 8, 10, 15 seconds | For Image to Video; 9:16 or 16:9 options, 720p. |
| **Veo 3.1 Lite / Veo 3.1** | 4, 6, 8 seconds | Supports both modes; aspect ratio and resolution follow the provider's settings, so some controls are hidden. |

The list you can actually use depends on your account and the provider at the time. A model that fails to be recognized may be disabled for the session.

The prompt field is limited to 3,000 characters. Don't ask for too many scene changes at once on a first try. The duration option is a request to the service; check the duration of the result.

## Results and buttons

- The player doesn't play the video automatically; press Play.
- **Download Video** fetches the existing result.
- **Open Video** opens the video source. Use the browser's save menu if direct downloads are restricted.
- **Generate Again** is a new request, not a re-download.
- **Hubungkan Ulang Puter** (Reconnect Puter) is used when the account connection needs fixing.

Video generation can take several minutes. If the interface's wait limit passes, the Puter job may still be running. The button stays restricted until that request's status finishes; reloading or sending again can create a new job.

## If something goes wrong

If Image to Video won't run, make sure the image has loaded and the model supports that mode. If a quota problem appears, check your Puter allowance. If the video won't play on your phone but the link exists, try Open Video or a device with suitable codec support.

To write a more structured video direction, use [Prompt Studio](promptgenerate.md), then copy the text here.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/puter-runtime.js) · [List of all tools](README.md)
