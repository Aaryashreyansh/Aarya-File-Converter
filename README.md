# Aarya File Converter

A responsive, browser-based file converter. Files are processed locally in the browser.

## Features
- Image conversion: JPG, PNG, WEBP
- Multiple images into one PDF (A4, Letter, or fit-to-image)
- PDF pages to JPG or PNG
- Batch image conversion
- Responsive mobile and desktop UI
- No upload server; selected files stay on the device

## Deploy with GitHub Pages
This repository includes a GitHub Actions workflow that publishes the root directory to GitHub Pages on pushes to `main`.

After the first workflow run, open **Settings → Pages** and confirm **Build and deployment → Source: GitHub Actions** if Pages is not already enabled.

## Notes
- PDF support uses PDF.js and jsPDF from cdnjs, so an internet connection is needed to load those libraries.
- Supported formats depend on the browser's image decoder/encoder.
- Very large files may exceed available browser memory.
- This is not a universal converter for every proprietary document, audio, or video format.
