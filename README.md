# Meta Glass Converter 🕶️

A fast, mobile‑first web tool that turns any JPEG into a **Ray‑Ban Meta Smart Glasses** photo – right in your browser. It resizes to **3024×4032**, injects authentic `Meta AI` / `Ray-Ban Meta Smart Glasses 2` EXIF data, strips sensitive metadata (GPS, camera serials, lens info), copies the Base64 string to your clipboard, and lets you save or share the final image – all with one tap.

No uploads. No servers. No tracking. Everything happens on your device.

---

## ⚡ Features

- **All‑In‑One 1‑Click Action**  
  Convert, copy Base64, and trigger download/share sheet in a single tap.

- **Exact Meta Glasses Specs**  
  Automatically resizes and corrects orientation to `3024 × 4032` pixels.

- **EXIF Cleanup & Injection**  
  Removes GPS, MakerNote, Lens info, and software tags, then injects:
  - `Make: Meta AI`
  - `Model: Ray-Ban Meta Smart Glasses 2`
  - `Orientation: 1`
  - `PixelXDimension: 3024`
  - `PixelYDimension: 4032`

- **100% Client‑Side**  
  Built with plain HTML5 Canvas and [piexifjs](https://github.com/hMatoba/piexifjs). No image ever leaves your browser.

- **Mobile‑First UX**  
  Large touch targets, camera/library direct input, native Web Share API integration, and a clean dark UI.

---

## 🚀 Live Demo

[Try it here](https://meta.subhajitmaji.me)

---

## 🛠️ Tech Stack

- **HTML / CSS / JavaScript** – no frameworks, no build step
- **Piexif.js** – EXIF reading/writing
- **Canvas API** – image resizing & orientation correction
- **Web Share API** – native save/share on mobile
- **Clipboard API** – one‑tap Base64 copy

---

## 🔒 Privacy

This tool is intentionally **serverless**. Your photos are processed entirely in your browser’s memory and are never uploaded, stored, or transmitted. The only metadata that is added is the Meta/Ray‑Ban EXIF tags; all original location and device‑specific tags are removed.

---

## 📄 License

MIT – feel free to use, modify, and share. Attribution appreciated but not required.

---

Enjoy! If you find this useful, consider giving the repo a ⭐
