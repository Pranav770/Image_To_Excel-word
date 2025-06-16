# 🖼️ Image to Excel/Word Converter

A simple web-based tool that lets users upload an image containing text or tables, extracts the content using OCR (Optical Character Recognition), and exports it into either a Microsoft Word (`.docx`) or Excel (`.xlsx`) file.

## 🔧 Features

- 📤 Upload images (`.jpg`, `.png`, etc.)
- 🧠 Extract text using Tesseract OCR
- 📄 Export extracted text to:
  - Microsoft Word (`.docx`) – For paragraphs, scanned notes
  - Microsoft Excel (`.xlsx`) – For tables, data grids
- 🌐 Simple web interface using Flask
- 🧹 Basic image preprocessing to improve OCR accuracy

---

## 🖥️ Demo Screenshot

> _( screenshot of  app upload form + download result here once done)_

---

## 📦 Tech Stack

| Part         | Technology                     |
|--------------|---------------------------------|
| Frontend     | HTML, CSS (Bootstrap optional) |
| Backend      | Python + Flask                 |
| OCR Engine   | Tesseract OCR (`pytesseract`)  |
| Image Tools  | PIL (Pillow), OpenCV           |
| Word Output  | `python-docx`                  |
| Excel Output | `openpyxl`, `pandas`           |

---

## 🚀 Getting Started
