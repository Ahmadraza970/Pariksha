# Pariksha — Free DPP to Mock Test

> Turn any DPP PDF into an NTA-style mock test. Free forever. No account. Works offline.

![Free](https://img.shields.io/badge/free-forever-brightgreen)
![No account](https://img.shields.io/badge/account-not%20required-blue)
![Offline](https://img.shields.io/badge/offline-yes-blue)
![Languages](https://img.shields.io/badge/languages-Hindi%20%E2%80%A2%20English%20%E2%80%A2%20%D8%A7%D8%B1%D8%AF%D9%88-orange)

**Pariksha** is a free app for JEE / NEET aspirants. Upload a DPP (Daily Practice Paper) PDF and take it as a real, timed mock test — with the same look and feel as the NTA exam screen.

- **Website / Download:** https://pariksha-app-murex.vercel.app/
- **Android APK:** see [Releases](../../releases) — `Pariksha-release.apk` (v1.1.1, 10.2 MB)
- **v1.1 note:** if v1.0 is already installed, uninstall it once before installing v1.1 — v1.1 is signed with a fresh key (the original signing key was not recoverable). Future updates will install normally over v1.1.

## Features

- **DPP to mock test in seconds** — upload a PDF, the app reads the questions, options and answer key automatically.
- **Hindi, English and Urdu** — reads PDFs in all three languages, including right-to-left Urdu.
- **Scanned PDFs work too** — image-only PDFs are read with on-device OCR (no internet needed).
- **Two-column papers read correctly** — questions stay in order with their own options.
- **NTA-style test screen** — question palette, mark for review, timer, and JEE/NEET marking presets (+4 / −1).
- **Detailed results** — score, accuracy, time per question, and a full review with correct answers.
- **Check & fix before you start** — preview every question and correct the answer key if anything was misread.
- **Questions & answer key separately (new in v1.1)** — questions in one PDF and the answer key somewhere else? Add the key on its own: upload a separate key PDF, or simply type it in (e.g. `1-B 2-A 3-D`).
- **v1.1.1 fix:** book-style keys like `1. (A)  2. (B)  20. (B, D)` are now accepted, and scanned (photo/DocScan) PDFs in the separate key/questions flow are read with OCR instead of being rejected.
- **Answer key first (new in v1.2 — in preview, not released yet):** the home screen now leads with the answer key — upload any DPP and the full key appears first as a clean Q→answer table with one-tap copy, then start the mock test when you're ready. Saved tests are searchable by name, and tapping one opens its key.
- **Your history stays on your device** — previous tests are saved locally so you can retake them anytime.

## How to use

1. Download the app (Android) or open the website.
2. Upload a DPP PDF.
3. See the answer key first — copy it if you like — then check the preview, fix anything if needed, and start the test.

No sign-up. No ads. No fees — free forever.

## Screenshots

See the download page for real screenshots of the home, preview, test and result screens:
https://pariksha-app-murex.vercel.app/

## Privacy

Everything stays on your device. Your PDFs, answers and test history are never uploaded anywhere. The app works fully offline once installed.

## Honest limits

- OCR on scanned PDFs is best-effort — a few words may need hand-fixing in the preview screen.
- Some maths formulas (superscripts, square roots) can still look scrambled in rare cases.
- Questions whose options are images or graphs are skipped for now.
- The app makes tests from question papers — it does not generate questions from plain notes.

## Built with

Single-file HTML app, [pdf.js](https://mozilla.github.io/pdf.js/), [Tesseract.js](https://tesseract.projectnaptha.com/) (OCR), and [Capacitor](https://capacitorjs.com/) for Android.

## Author

**Ahmad Raza** — [Ahmad Digital Studio](https://ahmadrazaa.me) · [Portfolio — ahmadrazaa.me](https://ahmadrazaa.me) · [GitHub](https://github.com/Ahmadraza970)
