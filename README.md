# 📌 Pinterest-Media-Downloader

![License: MIT](https://img.shields.io/badge/License-MIT-green) ![Language: Python](https://img.shields.io/badge/Language-Python-blue) ![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen)

Pinterest Media Downloader is a Streamlit-based desktop/web app to download images and videos from Pinterest pins, boards, and profiles—quickly and reliably.

---

## ✨ What’s New 

- 🎉 **Initial release** with core download and UI functionality  
- 🔄 Improved URL normalization & validation  
- 🕸️ Enhanced fallback scraping for robust media extraction  
- ⚙️ Better error handling and user feedback  
- 🖱️ Cleaner UI with quick-select buttons (“First 5”, “First 10”, “All Files”)  

---

## 🛠️ All Features

- 📥 Download images & videos from Pinterest pins, boards, profiles  
- 🔄 Dual extraction methods: **gallery-dl** + custom BeautifulSoup fallback  
- 📦 Save media as original files or bundled ZIP archive  
- ⚡ Quality & advanced settings: timeout, retries, concurrency  
- 👁️‍🗨️ Media preview cards with progress tracking  
- 🎛️ Professional Streamlit UI with sidebar settings & live metrics  

---

## 🗂️ Folder Structure

```

Pinterest-Media-Downloader/
├── LICENSE                    # MIT license
├── README.md                  # This file
├── requirements.txt           # Python dependencies
├── src/                       # Source directory
|   └── main.py                # Streamlit app entry point
├── favicon.ico            # App icon
└── screenshots/           # UI previews
    └── screenshot.png


````

---

## 📋 Requirements

- **Python 3.8+**  
- **pip** package manager  
- **Streamlit**  
- **gallery-dl**  
- **requests**  
- **beautifulsoup4**  
- **Pillow**  
- **lxml**

Install via:

```bash
pip install -r requirements.txt
````

> Or manually:
>
> ```bash
> pip install streamlit gallery-dl requests beautifulsoup4 pillow lxml
> ```

---

## ⚙️ Installation

1. **Clone** the repo

   ```bash
   git clone https://github.com/UKR-PROJECTS/Pinterest-Media-Downloader.git
   cd Pinterest-Media-Downloader/src
   ```
2. **Install** dependencies

   ```bash
   pip install -r ../requirements.txt
   ```

---

## ▶️ Usage

1. **Run** the app:

   ```bash
   streamlit run src/main.py
   ```
2. **Enter** a Pinterest URL (pin, board, or profile)
3. **Click** “🔍 Analyze URL” to fetch media links
4. **Choose** how many files to download or use quick-select
5. **Click** “🚀 Start Download” to save images/videos (ZIP option available)
6. **Monitor** progress and download individual files or archive

---

## 📸 Screenshot

![Interface](src/screenshots/screenshot.png)

---

## 🤝 How to Contribute

1. **Fork** the repository
2. **Create** a branch:

   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Implement** your changes & **commit**
4. **Push** and **open** a Pull Request

---

## 🙏 Acknowledgments

* **Streamlit** for rapid UI development
* **gallery-dl** for Pinterest extraction
* **BeautifulSoup** for HTML parsing
* **Requests** for HTTP sessions
* **Pillow** for media handling
