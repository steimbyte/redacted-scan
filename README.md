[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/steimerbyte)

> ⭐ If you find this useful, consider [supporting me on Ko-fi](https://ko-fi.com/steimerbyte)!

<img src="https://storage.ko-fi.com/cdn/generated/fhfuc7slzawvi/2026-04-23_rest-162bec27f642a562eb8401eb0ceb3940-onjpojl8.jpg?w=250" alt="steimerbyte" style="border-radius: 5%; margin: 16px 0; max-width: 100%;"/>

## 🕵️ About

**Redacted** is a privacy-focused Android document scanner with powerful redaction tools. Scan documents, black out sensitive information, and export as PDF or JPEG — all without internet access.

Featuring a sleek **CIA Red theme** with pure AMOLED black background for that authentic classified document feel.

---

## 📸 Features

### Scanning
- 📷 **AI-powered document detection** — automatic edge detection
- 🔲 **Perspective correction** — straightens tilted documents
- ✨ **Image enhancement** — automatic contrast and clarity
- ⬛ **Black & White mode** — optional grayscale scanning

### Redaction
- ✏️ **Brush tool** — freehand redaction with live preview
- 📏 **Line tool** — draw straight redaction lines
- 🧹 **Eraser** — remove unwanted redactions
- 🎨 **Color picker** — choose redaction color (default: black)
- 📐 **Adjustable brush size** — fine to bold strokes
- ↩️ **Undo support** — fix mistakes easily

### Export & Privacy
- 📄 **PDF export** — multi-page document support
- 🖼️ **JPEG export** — single image output
- 🔒 **Fully offline** — no internet permission required
- 🚫 **No tracking, no ads** — your documents stay private

---

## 🎨 Theme

**CIA Red** — Pure AMOLED black with red accents

| Background | Buttons | Text |
|------------|---------|------|
| `#000000`  | `#FF0000` | `#FFFFFF` |

---

## 📱 Requirements

- Android 8.0+ (API 26)
- Camera

---

## 🛠️ Build

```bash
# Debug build
./gradlew assembleDebug

# Release build (requires signing config)
./gradlew assembleRelease \
  -PRELEASE_STORE_FILE="path/to/keystore.jks" \
  -PRELEASE_STORE_PASSWORD="password" \
  -PRELEASE_KEY_ALIAS="alias" \
  -PRELEASE_KEY_PASSWORD="password"
```

---

## 🔧 Technical Stack

- [Jetpack Compose](https://developer.android.com/compose) — Modern UI toolkit
- [CameraX](https://developer.android.com/media/camera/camerax) — Camera capture
- [LiteRT](https://ai.google.dev/edge/litert) — Document segmentation AI
- [OpenCV](https://opencv.org/) — Image processing
- [PDFBox-Android](https://github.com/TomRoush/PdfBox-Android) — PDF generation

---

## 👤 Credits

- **Redaction feature** by [alephtex](https://github.com/alephtex)
- **For** jk.bagba
- **Based on** [FairScan](https://github.com/pynicolas/FairScan) by Pierre-Yves Nicolas

---

## 📄 License

This project is licensed under the **GNU GPLv3**. See [LICENSE](LICENSE) for details.

---

<p align="center">
  <b>🔴 CLASSIFIED 🔴</b>
</p>
