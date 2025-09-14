# AI QR Code Generator

## Overview
This project is a **Python-based QR Code Generator** built for the MSCS-633-M50 Hands-On Assignment 2 at University of the Cumberlands.  
It allows users to input any URL, and it generates a **QR code** that can be scanned with any QR reader.

The project demonstrates **AI-related applied programming** and practical use of **Python libraries** such as `qrcode` and `Pillow`.

---

## Features
- Generate QR codes from any URL input.
- Save the QR code as an image file (`qrcode.png`).
- Display the QR code inline (works well in Google Colab or Jupyter Notebook).
- Customizable QR code settings (size, border, error correction).

---

## Technical Requirements
- **Python 3.x**
- Libraries:
  - `qrcode[pil]`
  - `Pillow`
  - `IPython` (for inline display in notebooks)
- IDE: Google Colab, Visual Studio Code, or any Python environment.

---

## Installation
1. Install Python 3 if not already installed.
2. Install required libraries:

```bash
pip install qrcode[pil]
