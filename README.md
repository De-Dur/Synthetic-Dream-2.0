# Synthetic Dream N° 2.0

**pink current blue gold**

An interactive, browser-based generative artwork by **Denisa Durica**. Houdini-inspired procedural geometry unfolds into smooth pink filaments, with gold light traveling along the curves and a soft blue glow at the center.

## Play the app

👉 **[Open Synthetic Dream N° 2.0](https://github.com/De-Dur/Synthetic-Dream-N-2.0)**

Download `Synthetic_Dream_Blue_Current_Geometry.html` and open it in a modern browser. For GitHub Pages, publish the HTML as `index.html`.

## What this project does

Synthetic Dream draws layered, wing-like forms on an HTML canvas. Time animates the curves, the sliders change how they fold and ripple, and moving the pointer or dragging across the canvas bends the filaments. You can work with one wing, mirror it around a movable axis, or cycle through four silhouettes.

## Controls

| Control | Effect |
| --- | --- |
| **Controls** | Opens the geometry and lighting sliders. |
| **New form** | Morphs to the next wing silhouette. |
| **Symmetry On / Off** | Adds or removes the reflected left wing. **Symmetry Center** moves the mirror axis. |
| **Cols · Layers / Rows · Ripples** | Changes the number of filament layers and the ripples along each curve, respectively. |
| **X / Y Min and Max** | Changes the sampling domain that deforms the curves. |
| **K Divide, K Subtract, Y Wave Divide, Q Add, Wave Power** | Shapes the procedural field by adjusting wave spacing, phase, offset, and strength. |
| **Scale / Center X / Center Y** | Sizes and positions the artwork. |
| **Speed / Pause** | Changes animation speed or pauses the time-based motion. Negative speed reverses it. |
| **Glow / Glow Size / Inner Orange Glow / Density** | Adjusts the brightness, halo width, extra warmth at the core, and visible filament density. |
| **Reset** | Restores the default geometry and lighting settings. |
| **Hide / H** | Hides the interface for a clean view. Click the artwork or press **H** to bring it back. |

## Audio interaction

Click **♪** to open the sound menu. Choose **Share tab / system audio** in a supported browser and enable audio in the sharing picker, or choose an audio input. In Firefox, use an input such as **Stereo Mix** or a loopback device for system audio if your device offers one. A microphone picks up sound around you, including music played through speakers.

The **Input level** meter shows whether sound is reaching the app. Bass, mids, and highs modulate nine geometry parameters in real time. The numbers beside the sliders show the live values, and **Shape response** adjusts how strongly the form reacts. Click **♪** again to stop listening and return to your manual geometry settings.

## Export

- **PNG** saves the current canvas as a still image.
- **Record** captures up to 15 seconds of the canvas. Click again to stop early. The browser determines whether the file is MP4 or WebM. The recording contains the artwork only.

## Files

- `Synthetic_Dream_Blue_Current_Geometry.html` (or `index.html` when published) is the self-contained app.
- `README.md` describes the artwork and its controls.

## Attribution

Created and maintained by **Denisa Durica**. Please retain the artistic credit when sharing, remixing, or adapting the project.
