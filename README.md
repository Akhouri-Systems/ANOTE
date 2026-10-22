<p align="center">
  <img src="https://img.shields.io/badge/Status-Archived-lightgrey?style=for-the-badge" alt="Archived">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/GUI-Tkinter-orange?style=for-the-badge" alt="Tkinter">
  <img src="https://img.shields.io/badge/License-Proprietary-yellow?style=for-the-badge" alt="License">
</p>

<h1 align="center">📝 ANOTE</h1>
<p align="center"><strong>The Notepad Killer.</strong><br>A Premium, Feature-Rich Text Editor for Windows.</p>

<p align="center">
  <a href="https://github.com/Akhouri-Anmol-Kumar/ANOTE/releases/download/ANOTE/ANOTE.zip">
    <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20ANOTE-blue?style=for-the-badge&logoColor=white" alt="Download ANOTE">
  </a>
</p>

---

> **📁 Archive Notice:** This project has been officially archived. ANOTE represents the final, feature-complete iteration of this software. It is preserved here as a showcase of advanced Tkinter UI design, multi-mode editing, meme generation, and built-in translation. No further updates or maintenance will be provided.

---

## 📖 Overview

ANOTE is far more than a text editor. It is a multi-mode desktop experience that combines premium text editing with syntax highlighting, built-in meme generation, real-time translation into 15 languages, password protection with Gen-Z roast messages, and auto-save — all in a single application. Built because Notepad hasn't changed since 1983.

> *"We build what others forgot to fix."* — Akhouri Systems

---

## ✨ Key Features

### 📑 Multi-Tab Workspace
* Work on multiple files simultaneously with a modern tabbed interface
* Each tab maintains its own editor, line numbers, and file state
* Modified tabs are indicated with a `●` marker

### 💻 Syntax Highlighting (Coding Mode)
* Python keyword, string, comment, number, and function highlighting
* Debounced rendering — only the visible region is highlighted for performance
* Matrix-style green-on-black terminal theme

### 🔐 Password Protection
* SHA-256 hashed password lock on application startup
* Gen-Z roast messages on wrong password attempts:
  * *"WHAT HAPPENED BRO? YOU FORGOT PASSWORD BRUHH!! 💀"*
  * *"skill issue detected. wrong password again smh 🤦"*
  * *"ratio + you forgot your password + L + no cap 🤣"*
* Set, change, or remove password from within the app

### 🌍 Built-in Translator (15 Languages)
* Select text and instantly translate into:
  Hindi, English, Tamil, Bengali, Mandarin Chinese, South Korean, Japanese, Russian, Urdu, Odia, French, Spanish, German, Bhojpuri, Portuguese
* Side-panel translation dashboard with copy buttons for each language
* Uses Google Translate free endpoint (no API key needed)

### 🖼️ Meme Canvas (Meme Mode)
* Upload any image as meme base
* Add custom text with Impact font and black outline
* Click-to-place text positioning on canvas
* Adjustable text size and color
* Export memes as PNG or JPEG

### 💾 Auto Save
* Automatically saves modified files every 60 seconds
* Never lose your work to a crash or accidental closure

### 🔍 Find & Replace
* Regex-powered search with match highlighting
* Single replace and Replace All functionality
* Toggleable find bar with keyboard shortcut

### 🎨 Rich Text Formatting
* Bold, Italic, Underline via toolbar or shortcuts
* Dynamic font family selection (15 fonts)
* Font size adjustment
* Zoom In / Zoom Out (50% to 300%)
* Word Wrap toggle

### 📐 Canvas-Based Line Numbers
* High-performance line numbers rendered via Tkinter Canvas
* Only visible lines are drawn (debounced, scroll-synced)
* No lag even on large files

### 🌙 Three Themes
* **Normal** — Sleek dark theme for everyday writing
* **Coding** — Matrix-style green terminal aesthetic with syntax highlighting
* **Meme** — Canvas-based meme creation workspace

---

## 🎨 The 4 Modes of ANOTE

| Mode | Description |
| :--- | :--- |
| **NORMAL** | Clean, dark-themed writing environment with multi-tab support |
| **CODING** | Green-on-black terminal aesthetic with Python syntax highlighting |
| **MEME** | Hides the text editor and reveals a canvas for image manipulation and meme generation |
| **TRANSLATOR** | Splits the screen to provide a 15-language real-time translation dashboard |

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action | Shortcut | Action |
| :--- | :--- | :--- | :--- |
| `Ctrl + N` | New Tab | `Ctrl + F` | Toggle Find/Replace Bar |
| `Ctrl + O` | Open File | `Ctrl + Z` | Undo |
| `Ctrl + S` | Save File | `Ctrl + Y` | Redo |
| `Ctrl + Shift + S` | Save As | `Ctrl + W` | Close Tab |
| `Ctrl + T` | New Tab | `Ctrl + +` / `Ctrl + -` | Zoom In / Out |
| `Ctrl + A` | Select All | `F11` | Toggle Fullscreen |

---

## 🛠️ Technology Stack

* **Core:** Python 3
* **GUI Framework:** Tkinter (ttk, scrolledtext, canvas)
* **Image Processing:** Pillow (PIL) — Meme Canvas, icon generation
* **Translation:** Google Translate free endpoint (urllib)
* **Password Hashing:** hashlib (SHA-256)
* **Data Persistence:** JSON (password config)
* **Threading:** Python threading (non-blocking translation)

---

## 🚀 Installation & Usage

**⚡ Zero-Effort Launch:**
No complex setup. No admin rights. No bloatware.

1. Click the **Download** badge at the top of this README.
2. Extract the `.zip` file.
3. Run `ANOTE.exe`.

*(Requires Windows 10 or later)*

**For Developers (Run from Source):**
```bash
git clone https://github.com/Akhouri-Anmol-Kumar/ANOTE.git
cd ANOTE
pip install Pillow
python ANOTE.py
