# SVG Animasi → Alight XML (Animated SVG → Alight XML)

Converts the animation inside an SVG into shapes and XML keyframes for Alight Motion. This tool reads supported **SMIL or CSS** animation; it doesn't turn an MP4 into vector animation.

A **keyframe** is a marker for a value at a particular time, for example an object's position at the start and end of a movement.

## First try

1. Open **SVG Animasi → Alight XML**.
2. Press **Coba contoh animasi vektor** (Try a vector animation example) to learn the flow with the built-in example.
3. Press **Preview kode animasi** (Preview animation code).
4. Use **Putar** (Play), **Awal** (Start), and the timeline slider to check the motion.
5. Choose **Maximum Fidelity** as a starting point.
6. Set the size, project name, FPS, and duration as needed.
7. Press **Convert ke XML** (Convert to XML).
8. Read the warnings, download the XML, then import and check it in Alight Motion.

Once you understand the example, replace it with your own animated SVG code.

## Preparing your own source

Paste the entire SVG code into **Tempel kode SVG animasi** (Paste animated SVG code), including the opening SVG element, the animated shapes, and the animation rules. If you have a file, use the SVG picker; the source limit is 2 MB.

Make sure the source really contains SVG/CSS animation. Pasting a website address, a video, or just a JavaScript snippet doesn't produce animation that can be converted.

If you want to try simple code:

~~~xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 200">
  <circle cy="100" r="30" fill="#a855f7">
    <animate attributeName="cx" from="50" to="350"
             dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
~~~

This example asks for a circle to move horizontally. You still need to check export support in the conversion report.

## Settings to understand

| Section | What it means |
| --- | --- |
| **Timeline sumber** (Source timeline) | Checks the animation before conversion. |
| **FPS and Durasi** (Duration) | The timing settings of the resulting project. |
| **Daftar layer** (Layer list) | The shapes to include; the Semua (All), Tidak Ada (None), or Balik (Invert) options help with selection. |
| **Flat / Nested Groups** | How the shape structure is arranged in the XML. |
| **Maximum Fidelity** | Preserves the source as much as possible. |
| **Smart Color Groups** | Groups solid colors while checking the visual arrangement. |
| **Small Patch Cleanup** | Cleans up small fragment areas, with a setting to protect thin details. |
| **Izinkan XML partial dengan peringatan** (Allow partial XML with warnings) | Allows a partial result when some animation isn't fully supported. |

**Partial** means some elements may be lost, limited, or approximated with samples. Turn it on only if you've read the warnings and accept the result's limitations. This option is no guarantee that all animation will be exactly the same.

## Saving the result

The project name in Alight Motion and the download file name can be set separately. After success, choose **Download XML** or **Salin XML** (Copy XML). Check the motion in the target app, especially rotation, stacking order, and shape changes.

A moving preview proves the source can be previewed in the browser; it doesn't automatically prove that all motion is supported by Alight Motion. Use the conversion report as your reference.

For a logo SVG without animation, [SVG → Alight XML](svgalight.md) is a better fit.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/svg-animation-alight.js) · [List of all tools](README.md)
