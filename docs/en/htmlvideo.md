# HTML / WebGL to MP4

Turns a single HTML document and its on-screen animation into an MP4 video. Suitable for title animations, HTML/CSS visual effects, WebGL shaders, or Three.js scenes that a browser can run.

## What do you need to prepare?

Prepare **complete HTML**, not just a snippet of text or CSS code. The document should contain the page structure plus the CSS and JavaScript it needs.

If the document uses images, fonts, or libraries from the internet, make sure the preview can load those assets. Files that exist only in a folder on your computer aren't automatically available when you paste the code.

## How to use it

1. Open **HTML / WebGL to MP4**.
2. Paste the document into the editor or use **Pilih .html** (Choose .html).
3. Press **Jalankan pratinjau** (Run preview).
4. Wait until the display is visible and the preview status is ready.
5. Check that all images, fonts, and animations appear.
6. Press **Buat Video** (Create Video) once you're happy with the preview.
7. Wait for recording and encoding to finish.
8. Play the result to check the motion, then download the MP4 through the result actions.

If something is missing in the preview, fix the HTML or its assets first. Exporting doesn't automatically rebuild a page that didn't display successfully.

## A simple HTML example

Paste the following as a single document:

~~~html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<style>
html, body { margin: 0; height: 100%; }
body {
  display: grid; place-items: center;
  background: #080808; color: #c084fc;
  font: bold 72px Arial;
}
h1 { animation: naik 2s ease-in-out infinite alternate; }
@keyframes naik {
  from { transform: translateY(30px); opacity: .4; }
  to { transform: translateY(-30px); opacity: 1; }
}
</style>
</head>
<body><h1>NEXORA</h1></body>
</html>
~~~

This is a practice example for learning the preview and export flow. Change the text, colors, and motion once you understand the flow.

## Important limits

- The engine in this version prepares **8 seconds, 30 FPS, 240 frames**, then an H.264 MP4.
- Preview, frame capture, and encoding run in the browser. Your device still needs enough memory and graphics capability.
- **Hentikan** (Stop) stops the active preview.
- Editing the document requires checking the preview again before creating a video.
- This tool converts a page's display; it is not a screen recorder for your whole phone and doesn't automatically include all of a website's content from a URL.
- Support for WebGL, fonts, network assets, and codecs depends on the device/browser.

If creating the video feels heavy, try the simple HTML example first. If the example works but your project fails, check external assets, code errors, or scene complexity. To create video from an AI description, use [AI Video Generator](aivideo.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/html-video-engine/src/app.tsx) · [List of all tools](README.md)
