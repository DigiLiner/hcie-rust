<img width="1819" height="1078" alt="hcie-upload" src="https://github.com/user-attachments/assets/284e8547-c4c1-4a9a-82ce-768b3f3c1894" />


# HCIE

**Pixel-grade image editor** for Windows and Linux — native, GPU-accelerated, closed-source.

> **Status: Alpha** — This is an early development release. It is incomplete, may contain bugs, and is not yet stable. Use it for evaluation only; back up important files before opening or editing them.

---

## Overview

HCIE is a native, pixel-grade image editor designed for painting, compositing, retouching, and project-based image editing. It targets professionals and hobbyists who want responsive, high-performance canvas work on the desktop — including very large (up to 4K and beyond) multi-layer documents.

The editor runs natively on Windows and Linux with GPU-accelerated rendering and a full docking UI.

---

## Features

- **GPU-accelerated canvas** — partial-texture upload keeps large documents smooth (100+ FPS) while panning, zooming, and drawing.
- **Brush engine** — pressure-sensitive tablet support and a rich preset library across paint, dry-media, watercolor, ink, and digital categories.
- **Layers & masks** — full layer management, blending modes, layer masks, opacity, and visibility.
- **Selections** — rectangle, ellipse, lasso, polygon, wand, plus advanced move / resize / rotate transforms.
- **Filters & adjustments** — brightness/contrast, hue/saturation, and more, with live preview.
- **Vector shapes** — circle, ellipse, line, star, polygon, arrow, rhombus, heart, bubble, gear, cross, crescent, cylinder, and more, with edit handles and rotation.
- **Text** — vector text layers with font and alignment options.
- **File formats** — import/export PNG, JPEG, WebP, PSD, KRA, and the native `.hcie` project format.
- **Cross-platform packaging** — native installers and portable builds for Windows and Linux.

---

## Platforms & Downloads

| Platform | Architecture | Artifacts |
|----------|--------------|-----------|
| Windows  | x86_64       | NSIS setup installer, portable zip |
| Linux    | x86_64       | AppImage, DEB, portable tar.gz |

See the [Releases](https://github.com) page for the latest build and install instructions.

---

## Installation

### Windows

1. Download the NSIS installer or the portable zip from the release.
2. Run the installer (or unzip the portable archive) and launch `hcie.exe`.

### Linux

Install the DEB (Debian/Ubuntu) or run the AppImage. Alternatively, extract the portable `tar.gz` and run `./hcie`.

---

## ⚠️ Alpha Status & Known Limitations

This is an **early alpha** — expect rough edges:

- **Stability** — crashes, freezes, or corrupted state may occur. Save and export often.
- **KDE Wayland tablet input** — a known pointer and UI-click limitation exists under KDE Wayland with tablet/stylus input. Mouse input and normal desktop use are unaffected.
- **AI & vision plugins** — AI chat and vision engine plugins are not bundled as required dependencies in this alpha.
- **Deferred tools** are hidden until their production backends are complete (Smart Select, Vision Select, Smart Patch, AI Object Removal, Vectorize Bitmap, Wavelet, advanced transforms, Trim, Variables, Quick Mask, FFT Filter).
- **No guarantees** — performance, correctness, and API compatibility will change before a stable release.

---

## Building from Source

The source is **not** distributed in this closed-source release. Prebuilt binaries are provided on the [Releases](https://github.com) page.

---

## Licensing

HCIE is a **closed-source** product. Binaries are provided under the license accompanying the download; the source code is not included.

---

## Feedback

Since this is an early alpha, your feedback is valuable. Report issues, crashes, and suggestions — attach logs, screenshots, and reproducible steps where possible.

---

## Roadmap

This alpha is the foundation of the HCIE 3.x series. Expect iterative alpha and beta releases covering stability, the complete tool set, the AI/vision pipeline, and cross-platform refinements ahead of a stable release.
